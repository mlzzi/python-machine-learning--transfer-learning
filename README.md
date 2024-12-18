# 🐾 Desafio de Machine Learning com Transfer Learning  

Este repositório contém a implementação de um desafio utilizando **Transfer Learning** para classificar imagens de cães e gatos. 🐶🐱  
O projeto foi desenvolvido com base em um exemplo proposto e utiliza o modelo pré-treinado **VGG16**.  

---

## 🚀 Tecnologias Utilizadas  
* **Python** 🐍  
* **TensorFlow/Keras** 🤖  
* **Google Colab** 💻  
* **Dataset de Cães e Gatos da Microsoft** 📂  

---

## 🛠️ Processo de Desenvolvimento  

1. **⚙️ Configuração do Dataset**  
   * Utilizei o dataset sugerido, contendo imagens de cães e gatos.  
   * Limitei o número de imagens por classe (gatos e cachorros) a **150** para reduzir o consumo de RAM no Google Colab.  
   * 🧹 Implementei um algoritmo para remover imagens corrompidas ou inadequadas, garantindo a qualidade dos dados.  

2. **🔄 Transfer Learning**  
   * Utilizei o modelo pré-treinado **VGG16** para realizar Transfer Learning.  
   * Adaptei as camadas finais do modelo para atender ao desafio de classificação binária (cães e gatos).  
   * 📊 Treinei o modelo e visualizei os gráficos de desempenho.  

3. **🧪 Testes Finais**  
   * Desenvolvi um algoritmo para prever imagens externas.  
   * Permiti que o modelo recebesse URLs de imagens de cachorros diretamente da internet. 🌐  
   * 🏆 Realizei testes adicionais e o modelo demonstrou alta precisão, acertando todas as previsões.  

---

## 🌟 O que Aprendi  
* Como trabalhar com **Transfer Learning** usando modelos pré-treinados.  
* A importância de gerenciar recursos computacionais (RAM) em ambientes como o Google Colab.  
* Técnicas para limpar e preparar datasets, removendo imagens corrompidas.  
* Como implementar e testar modelos em cenários reais, utilizando URLs de imagens externas.  

---

📔 **Notebook no Colab:**  
[🔗 Link para o notebook no Google Colab](https://colab.research.google.com/drive/1j_ziBqRR-ywcwGHQo4PVQ4_iNUDY1N1b?usp=sharing)  
