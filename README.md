# Classificador de Emails Spam/Não Spam

Este é um projeto simples de classificação de emails utilizando SVM.  
O objetivo é demonstrar como é possível identificar emails de spam de forma automatizada e gerar insights básicos sobre os dados.

## Estrutura do projeto

- `emails.csv` – dataset de emails (spam e não spam)  
- `notebook.ipynb` – notebook com pré-processamento, treino do modelo e avaliação 

## Pré-processamento

1. Converter para letras minúsculas
2. Remover o prefixo `"Subject:"`  
3. Remover números e caracteres especiais
4. Limpar espaços extras  

## Modelo

- Algoritmo: Linear SVM (`LinearSVC` do scikit-learn)  
- Features: TF-IDF (representação numérica do texto)   

O modelo atingiu uma boa performance com esse dataset, classificando corretamente a maior parte dos emails de teste.

## Tecnologias utilizadas

- Python  
- pandas  
- scikit-learn  
- Google Colab  

## Observações

Este projeto tem objetivo didático. Não é integrado a nenhum serviço real de email (ainda).
