# 🔍 Image Recommendation System

## 📌 Descrição
Este projeto implementa um **sistema de recomendação baseado em imagens**.  
A ideia é simples: dado um produto de entrada (por exemplo, um tênis), o modelo sugere os itens mais parecidos visualmente no dataset, analisando **cor, textura e formato** ao invés de preço ou marca.  

O projeto foi desenvolvido no **Google Colab**, utilizando **Deep Learning** com uma rede pré-treinada (**ResNet50**) para extrair embeddings de imagens. Em seguida, utilizamos **similaridade de cosseno** para encontrar os produtos mais próximos.

---

## ▶️ Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/image-recommender.git

2. Abra o notebook no Google Colab:
```
  image_recommender.ipynb
```

3. Execute as células sequencialmente:

  * Carregamento do dataset
  * Extração de embeddings com ResNet50
  * Cálculo de similaridade
  * Geração das recomendações

📊 Exemplo de Saída

A partir de uma imagem de entrada, o sistema retorna os produtos mais semelhantes:

![Exemplo de Predição](/predictions.png)

🛠️ Tecnologias

    * Python
    * TensorFlow / Keras
    * ResNet50 (pré-treinada no ImageNet)
    * Scikit-learn
    * Matplotlib / Seaborn

✅ Conclusão

Este sistema mostra como técnicas de aprendizado profundo podem ser aplicadas em cenários de recomendação sem depender de dados textuais.
O mesmo conceito pode ser expandido para e-commerce, busca por similaridade ou até mesmo curadoria automática de catálogos.

👩‍💻 Autoria: Enaile Lopes
