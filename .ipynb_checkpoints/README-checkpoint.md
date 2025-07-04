# Evolução da Fronteira de Decisão com Deep Learning

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Este repositório apresenta uma animação mostrando a evolução da fronteira de decisão de um modelo de rede neural durante o treinamento. A animação ilustra como a rede aprende a separar classes ao longo das épocas.

## 🚀 Demonstração

Veja a evolução da fronteira de decisão do modelo:

<p align="center">
  <img src="media/evolucao_fronteira_decisao.gif" alt="Animação da Evolução da Fronteira de Decisão" width="700"/>
</p>

## Tecnologias Utilizadas

* **Python**: Linguagem principal do projeto.
* **TensorFlow / Keras**: Construção e treinamento da rede neural.
* **NumPy**: Manipulação dos dados.
* **Matplotlib & Seaborn**: Visualização da fronteira de decisão e dos dados.
* **OpenCV**: Utilizado para ler e processar os frames salvos.
* **ImageIO**: Essencial para a criação da animação final no formato GIF.
* **Pillow**: Dependência do `imageio` para salvar GIFs.
* **Scikit-learn**: Pré-processamento dos dados (divisão de treino/teste).

## Sobre o Projeto

O código gera um conjunto de dados sintético onde dois grupos de pontos precisam ser classificados. Um modelo de rede neural com camadas densas é treinado e, a cada época, capturamos a evolução da fronteira de decisão.

Ao final, a animação exibe a separação clara das classes, mostrando como a rede aprendeu ao longo do tempo. A legenda das classes foi posicionada fora da área do gráfico para melhor visualização, e uma mensagem final sinaliza a conclusão da separação das classes. Os frames individuais da animação são salvos na pasta `frames/` e a animação final em `media/`.

## 🚀 Como Executar

Para rodar este projeto em seu ambiente local, siga os passos abaixo:

1.  **Clone o repositório**:

    ```bash
    git clone [https://github.com/SeuNomeDeUsuario/Evolucao_Fronteira_de_Decisao.git](https://github.com/SeuNomeDeUsuario/Evolucao_Fronteira_de_Decisao.git)
    cd Evolucao_Fronteira_de_Decisao
    ```

2.  **Instalar as dependências**:
    Certifique-se de ter as bibliotecas necessárias instaladas. Recomenda-se criar um ambiente virtual.

    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

3.  **Rodar o Código**:
    O código principal para a geração da animação está no arquivo `Evolucao_Fronteira_de_Decisao.ipynb`. Você pode executá-lo em um ambiente Jupyter Notebook ou Jupyter Lab:

    ```bash
    jupyter notebook Evolucao_Fronteira_de_Decisao.ipynb
    ```

    Após a execução do notebook, o GIF da animação será salvo na pasta `media/` e os frames individuais na pasta `frames/`.

## 🤝 Contribuições

Contribuições são bem-vindas! Se você tiver ideias para melhorias, novas funcionalidades ou encontrar algum problema, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📧 Contato

Se você tiver alguma dúvida ou sugestão, entre em contato:

* **Nome**: Flávio Henrique Barbosa
* **LinkedIn**: [Flávio Henrique Barbosa | LinkedIn](https://www.linkedin.com/in/fl%C3%A1vio-henrique-barbosa-38465938)
* **Email**: flaviohenriquehb777@outlook.com

---