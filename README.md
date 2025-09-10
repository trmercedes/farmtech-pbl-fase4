# FarmTech Solutions - PBL Fase 4

**Aluno:** Tiago Ribeiro Mercedes Valença  
**RM:** 565890  

---

## Entrega 1 - Machine Learning

Este repositório contém o notebook desenvolvido na Fase 4, que utiliza técnicas de Machine Learning para prever o rendimento agrícola com base em variáveis climáticas.

👉 https://github.com/trmercedes/farmtech-pbl-fase4/blob/main/tiagoribeiromercedesvalenca_rm565890_pbl_fase4.ipynb

### Vídeo da Entrega 1
Demonstração do notebook em execução:  
🎥 [Assista no YouTube](https://youtu.be/UHmPTfmen34)

---

## Como executar o Notebook

1. Baixe este repositório :
https://github.com/trmercedes/farmtech-pbl-fase4/blob/main/tiagoribeiromercedesvalenca_rm565890_pbl_fase4.ipynb
   

2. Verifique se o dataset está no caminho correto:

   data/raw/crop_yield.csv

4. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```
   *(se o arquivo `requirements.txt` não estiver disponível, instale manualmente:)*  
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

5. Abra o notebook com Jupyter:
   ```bash
   jupyter notebook tiagoribeiromercedesvalenca_rm565890_pbl_fase4.ipynb
   ```

6. Execute as células de cima para baixo (Shift + Enter em cada uma).

---

## O que o Notebook faz

- **Análise Exploratória (EDA):** estatísticas descritivas, distribuições e correlações.  
- **Clusterização:** identificação de padrões de rendimento com KMeans e detecção de outliers com DBSCAN.  
- **Modelagem Preditiva:** comparação de 5 modelos de regressão (Linear, Ridge, Lasso, Decision Tree, Random Forest, SVR).  
- **Resultados:** tabela com métricas (RMSE, MAE, R²) para avaliar o melhor modelo.  
- **Conclusão:** principais achados e limitações.

---

## Entrega 2 - Computação em Nuvem (AWS)

### Comparação de Custos - AWS EC2 (On-Demand)

| Região                  | Preço estimado / mês |
|-------------------------|-----------------------|
| São Paulo (sa-east-1)   | **US$ 5,55** |
| Virgínia (us-east-1)    | **US$ 3,43** |

### Justificativa Técnica
Apesar de a região da Virgínia (EUA) apresentar custo menor, a escolha correta é **São Paulo (sa-east-1)** porque:  
- Atende às **restrições legais**, evitando armazenamento de dados sensíveis fora do Brasil.  
- Garante **menor latência** e acesso mais rápido aos sensores instalados na fazenda.  
- Mantém a conformidade e a confiabilidade da solução, mesmo com custo ligeiramente maior.

- link video youtube mostrando onde calculei cada custo com as especificações necessarias : https://youtu.be/0uKZairzZ1Q
