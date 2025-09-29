# DPO-Database-Updater

Ferramentas de automação para atualização e sincronização de bases de dados utilizadas pela **DPO Revendas**.  
Este repositório centraliza notebooks que integram diferentes sistemas (Gasola, Promax e Checklist) e consolidam informações em planilhas Excel no Google Drive.

---

## 📂 Estrutura do Repositório

- **notebooks/** → Contém os notebooks principais
  - `Atualizar_Gasola.ipynb` → Integração com API do Gasola (abastecimentos da frota)
  - `Atualizar_Promax.ipynb` → Integração com sistema Promax (relatórios operacionais)
  - `Atualizar_Checklist.ipynb` → Atualização de checklists de inspeções
- **docs/** → Documentações e instruções complementares
- **README.md** → Apresentação do repositório

---

## 🚀 Como Utilizar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/DPO-Database-Updater.git
   cd DPO-Database-Updater
   ```

2. Abra os notebooks no **Google Colab** (ou outro ambiente compatível).

3. Configure tokens/credenciais de cada integração (não versionar no GitHub).

4. Execute todas as células até o final.

5. Os arquivos serão gravados no **Google Drive**, organizados por sistema.

---

## ⚙️ Dependências

- Python 3.10+  
- Bibliotecas principais:
  - `pandas`  
  - `openpyxl`  
  - `requests`  
  - `google.colab` (quando usado no Colab)

Instalação local:
```bash
pip install pandas openpyxl requests
```

---

## ✅ Boas Práticas

- Não versionar tokens/credenciais no repositório.  
- Utilizar variáveis de ambiente ou arquivos `.env`.  
- Documentar cada atualização ou novo notebook adicionado.  

---

## 📌 Objetivo

Manter um fluxo de **atualização automatizada de bases de dados** da DPO Revendas, garantindo consistência, rastreabilidade e eficiência no processamento das informações.
