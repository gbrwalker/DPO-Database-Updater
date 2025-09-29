# Atualizar_Gasola.ipynb

Este notebook realiza a integração com a **API do Gasola**, responsável por coletar informações de abastecimento da frota e atualizar um banco de dados em Excel no Google Drive.

## 🚀 Funcionalidades

- Conecta-se à API do Gasola via `requests`
- Baixa registros de abastecimento do período definido
- Normaliza os dados em formato tabular com `pandas`
- Remove registros duplicados pelo número do abastecimento
- Salva em arquivo Excel no Google Drive (`openpyxl`)

## 📂 Estrutura de Funções

- `montar_headers()` → gera cabeçalhos da requisição  
- `requisicao_segura()` → consulta HTTP com tratamento de erro  
- `requisitar_periodo()` → consulta API para intervalo definido  
- `json_para_df_final()` → transforma JSON em DataFrame formatado  
- `montar_drive()` → monta o Google Drive no Colab  
- `atualizar_db()` → salva ou atualiza o banco em Excel  
- `pipeline()` → executa todas as etapas

## 🛠️ Como Usar

1. Abra o notebook no Google Colab.  
2. Configure o `TOKEN` da API.  
3. Execute as células até o final.  
4. O arquivo Excel atualizado estará no caminho:  
   `/content/drive/My Drive/DATABASE_FROTA/DATABASE_GASOLA.xlsx`
