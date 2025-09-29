# Atualizar_Promax.ipynb

Este notebook integra dados do sistema **Promax**, coletando relatórios e atualizando uma base em Excel no Google Drive.

## 🚀 Funcionalidades

- Conecta-se à API do Promax (ou endpoint interno)  
- Baixa dados de relatórios ou métricas operacionais  
- Normaliza em DataFrame (`pandas`)  
- Atualiza planilha Excel no Google Drive  
- Garante integridade removendo registros duplicados  

## 📂 Estrutura de Funções

- Funções de conexão com API do Promax  
- Conversão de JSON/CSV para DataFrame  
- Montagem do Google Drive  
- Atualização incremental do banco de dados  
- Execução via `pipeline()`

## 🛠️ Como Usar

1. Suba no Google Colab.  
2. Configure parâmetros de autenticação (`TOKEN` ou credenciais).  
3. Execute até o final.  
4. Arquivo Excel atualizado será salvo no Drive, dentro de:  
   `/content/drive/My Drive/DATABASE_PROMAX/`
