# Atualizar_Checklist.ipynb

Este notebook mantém atualizado o **checklist de operações** da frota, integrando dados de inspeções/atividades em um banco Excel no Google Drive.

## 🚀 Funcionalidades

- Coleta registros de checklist (via API ou arquivo)  
- Estrutura e normaliza dados em DataFrame (`pandas`)  
- Remove duplicados para evitar inconsistências  
- Exporta os dados para Excel, integrado ao Google Drive  

## 📂 Estrutura de Funções

- Funções de conexão com API ou leitura de arquivo  
- Tratamento de dados em DataFrame  
- Montagem do Google Drive  
- Atualização da planilha final  
- Execução automatizada via `pipeline()`

## 🛠️ Como Usar

1. Suba no Google Colab.  
2. Configure parâmetros de conexão (se aplicável).  
3. Rode `pipeline()`.  
4. Arquivo final será salvo no Drive, dentro de:  
   `/content/drive/My Drive/DATABASE_CHECKLIST/`
