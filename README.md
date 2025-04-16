# 🐭 Tom & Jerry - Classificação de Imagens com CNN

Este projeto usa redes neurais convolucionais (CNNs) para classificar imagens dos personagens Tom e Jerry em quatro categorias: `tom`, `jerry`, `tom_jerry_0` e `tom_jerry_1`.

---

##  Como Rodar

1. **Ative a GPU no Colab:**
   - Vá em **Ambiente de execução > Alterar tipo de ambiente de execução > GPU**

2. **Execute o notebook célula por célula:**
   - As dependências serão instaladas automaticamente
   - O dataset será baixado do Kaggle
   - O modelo será treinado e avaliado
   - Os resultados (gráficos e métricas) serão exibidos ao final

---

##  Como obter a chave da API do Kaggle

Para baixar o dataset diretamente do Kaggle no Colab, é necessário autenticar com a API:

1. Acesse seu perfil em: [https://www.kaggle.com/account](https://www.kaggle.com/account)
2. Vá até a seção **"API"**
3. Clique em **"Create New API Token"**
4. Será baixado um arquivo chamado `kaggle.json`
5. No Colab, siga as instruções do notebook para fazer upload desse arquivo

---

##  O que o notebook faz

- Carrega e organiza o dataset
- Cria e treina uma CNN do zero
- Apresenta os resultados com gráficos
- Compara com modelos pré-treinados (MobileNetV2)
- Analisa erros de classificação

---
