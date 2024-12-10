<h1>Cálculo de Métricas de Avaliação de Aprendizado</h1>

<img align="right" height="200" style="border-radius:50px;" src="https://assets.dio.me/kCPUcBRKwIhY3--gHdSspiZWdpUXMS2UD0wXM7klMb4/f:webp/h:120/q:80/L3RyYWNrcy81NzQ0ODVlZS0xZTk1LTQzMjAtOThlYy1kMTUyZGQ4ZDk5YmQucG5n">

<h4>Repositório criado para o desafio do bootcamp BairesDev - Machine Learning Practitioner</h4>

<p align="justify">
    Este projeto implementa um modelo de aprendizado profundo utilizando a biblioteca TensorFlow e o dataset MNIST. Além de treinar e avaliar o modelo, são calculadas e visualizadas as principais métricas de avaliação de classificação, como acurácia, sensibilidade, especificidade, precisão e F1-Score.
</p>


<h3>🧠 Objetivo</h3>
<p align="justify">
    Demonstrar como construir um modelo de aprendizado profundo simples e calcular métricas essenciais para a avaliação de métodos de classificação. O projeto também foca na apresentação gráfica dessas métricas de maneira clara e esteticamente agradável.
</p>

<h2>📂 Estrutura do Projeto</h2>
<ul>
    <li><b>Pré-processamento de Dados:</b> Normalização e reformatamento das imagens do MNIST.
    <li><b>Construção do Modelo:</b> Rede neural convolucional com camadas <code>Conv2D</code>, <code>MaxPooling2D</code>, e <code>Dense</code>.
    <li><b>Treinamento:</b> Treinamento e validação do modelo.
    <li><b>Cálculo de Métricas:</b>
        <ul>
            <li>Matriz de Confusão
            <li>Relatório de Classificação (precisão, recall, F1-score)
        </ul>
    <li><b>Visualização Gráfica:</b>
        <ul>
            <li>Matriz de confusão estilizada.
            <li>Curvas de Acurácia e Perda durante o treinamento.
        </ul>
</ul>


<h2>🛠️ Tecnologias Utilizadas</h2>
<ul>
    <li><b>Python</b>
    <li><b>Bibliotecas:</b>
    <ul>
        <li><code>tensorflow.keras</code>: Construção e treinamento do modelo.
        <li><code>numpy</code> e <code>pandas</code>: Manipulação de dados.
        <li><code>matplotlib.pyplot</code> e <code>seaborn</code>: Visualizações gráficas.
        <li><code>sklearn.metrics</code>: Cálculo de métricas.
    </ul>
</ul>

<h2>📊 Métricas Calculadas</h2>
<table>
        <thead>
            <tr>
                <th>Métrica</th>
                <th>Fórmula</th>
                <th>Descrição</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Sensibilidade</td>
                <td>VP / (VP + FN)</td>
                <td>Taxa de verdadeiros positivos entre todos os positivos reais.</td>
            </tr>
            <tr>
                <td>Especificidade</td>
                <td>VN / (VN + FP)</td>
                <td>Taxa de verdadeiros negativos entre todos os negativos reais.</td>
            </tr>
            <tr>
                <td>Acurácia</td>
                <td>(VP + VN) / N</td>
                <td>Proporção de predições corretas.</td>
            </tr>
            <tr>
                <td>Precisão</td>
                <td>VP / (VP + FP)</td>
                <td>Taxa de verdadeiros positivos entre todos os positivos preditos.</td>
            </tr>
            <tr>
                <td>F1-Score</td>
                <td>2 × (P × S) / (P + S)</td>
                <td>Média harmônica entre precisão e sensibilidade.</td>
            </tr>
        </tbody>
    </table>

<h2>📈 Visualizações</h2>
<h3>Matriz de Confusão</h3>
<p>A matriz de confusão é apresentada com uma coloração otimizada e rótulos claros para facilitar a análise das predições.</p>

<h3>Curvas de Acurácia e Perda</h3>
<p>Gráficos que mostram a evolução da acurácia e da perda durante as épocas de treinamento e validação.<p>

<h2>🔍 Exemplos de Saída</h2>
<h3>Matriz de Confusão</h3>
<img src="assets/confusion_matrix.png" alt="Matriz de Confusão" width="600">
<h3>Curvas de Acurácia e Perda</h3>
<img src="assets/training_curves.png" alt="Curvas de Treinamento" width="600">

<h2>📜 Licença</h2>
<p>Este projeto é licenciado sob a licença <a href="https://opensource.org/licenses/MIT">MIT</a>.</p>

<h2>📬 Contato</h2>
<p>
  <a href="mailto:eujulianasilvasoares@gmail.com">
    <img src="https://img.shields.io/badge/-email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Connect via Email" />
  </a>
  <a href="https://www.linkedin.com/in/julianasilvasoares/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>