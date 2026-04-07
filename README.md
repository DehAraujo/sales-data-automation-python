# 📊 Automação de Relatórios de Vendas

Este projeto automatiza o processo de leitura, tratamento, análise e envio de relatórios de vendas a partir de arquivos Excel.

---

## 🚀 Funcionalidades

- 📥 Leitura de arquivos `.xlsx` com múltiplas abas  
- 🔄 Consolidação de dados em um único DataFrame  
- 🧹 Tratamento e padronização de dados:
  - Remoção de espaços
  - Padronização de texto
  - Correção de nomes de cidades
  - Conversão de datas
  - Garantia de tipos numéricos
- 📊 Recalculo automático do total de vendas  
- 🔍 Aplicação de filtros (valores válidos e positivos)  
- 💾 Geração de relatório final em Excel  
- 📧 Envio automático por e-mail com anexo  

---

## 📁 Estrutura do Projeto

<img width="723" height="404" alt="image" src="https://github.com/user-attachments/assets/88563ca5-69d2-47de-b86c-7880ae05dcd0" />


---

## ⚙️ Como funciona

### 1. Leitura dos dados
O sistema lê um arquivo Excel contendo múltiplas abas:

```python
df = leitura_dados(caminho)
```
### **2. Consolidação**

As abas são unificadas em um único DataFrame:
