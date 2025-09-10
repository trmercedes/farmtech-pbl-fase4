# FarmTech Solutions - PBL Fase 4

**Aluno:** Tiago Ribeiro Mercedes Valença  
**RM:** 565890  

---

## Entrega 1 - Machine Learning

Este repositório contém o notebook desenvolvido na Fase 4, que utiliza técnicas de Machine Learning para prever o rendimento agrícola com base em variáveis climáticas.

👉 

### Vídeo da Entrega 1
Demonstração do notebook em execução:  
🎥 [Assista no YouTube](https://youtu.be/UHmPTfmen34)

---

## Como executar o Notebook

1. Baixe este repositório ou clone com Git:
   ```bash
   git clone https://github.com/SEU_USUARIO/farmtech-pbl-fase4.git
   cd farmtech-pbl-fase4
   ```

2. Verifique se o dataset está no caminho correto:
   ```
   data/raw/crop_yield.csv
   ```

3. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```
   *(se o arquivo `requirements.txt` não estiver disponível, instale manualmente:)*  
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

4. Abra o notebook com Jupyter:
   ```bash
   jupyter notebook tiagoribeiromercedesvalenca_rm565890_pbl_fase4.ipynb
   ```

5. Execute as células de cima para baixo (Shift + Enter em cada uma).

---

## O que o Notebook faz

- **Análise Exploratória (EDA):** estatísticas descritivas, distribuições e correlações.  
- **Clusterização:** identificação de padrões de rendimento com KMeans e detecção de outliers com DBSCAN.  
- **Modelagem Preditiva:** comparação de 5 modelos de regressão (Linear, Ridge, Lasso, Decision Tree, Random Forest, SVR).  
- **Resultados:** tabela com métricas (RMSE, MAE, R²) para avaliar o melhor modelo.  
- **Conclusão:** principais achados e limitações.

---

## Entrega 2 - Computação em Nuvem (AWS)

➡️ Aqui será adicionada a comparação de custos entre **São Paulo (sa-east-1)** e **Virgínia do Norte (us-east-1)** usando a **AWS Pricing Calculator**.  
➡️ Inclui prints da calculadora, tabela comparativa e justificativa técnica sobre a escolha da região.  
➡️ Também ficará disponível o link para o segundo vídeo (YouTube - não listado).  

---

## Estrutura do Repositório
```
├── tiagoribeiromercedesvalenca_rm565890_pbl_fase4.ipynb   ← Notebook Jupyter
├── data/
│   └── raw/
│       └── crop_yield.csv                                ← Dataset
└── README.md                                             ← Documentação
```

---

## Observações
- O notebook está completo, com código executado e comentado.  
- O dataset usado está em `data/raw/crop_yield.csv`.  
- O vídeo da Entrega 1 já está disponível no YouTube (não listado).  
- Não serão feitos novos commits após a data de entrega.

