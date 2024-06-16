# YouTube Video Transcription and Q&A Bot

## Descrição

Este projeto é um script desenvolvido com [LangChain](https://github.com/hwchase17/langchain) que permite a transcrição de vídeos do YouTube a partir da URL fornecida pelo usuário e responde a perguntas sobre o conteúdo do vídeo. Utilizamos a biblioteca `streamlit` para criar uma interface web simples e interativa onde o usuário pode inserir a URL do vídeo e fazer perguntas diretamente.

## Funcionalidades

- **Transcrição de Vídeos**: Obtém a transcrição completa do vídeo do YouTube a partir da URL fornecida.
- **Resposta a Perguntas**: Permite que os usuários façam perguntas específicas sobre o conteúdo transcrito do vídeo.
- **Interface Web Intuitiva**: Utiliza `streamlit` para uma experiência de usuário fácil e direta.

## Instalação

### Pré-requisitos

- Python 3.8 ou superior
- `pip` instalado

### Passos de Instalação

1. Clone este repositório para o seu diretório local:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio

2. Crie e ative um ambiente virtual (opcional, mas recomendado):

   ```bash
   python -m venv .venv
    source .venv/bin/activate  # No Windows use .venv\Scripts\activate
   
3. Instale as dependências necessárias:

   ```bash
   pip install -r requirements.txt

  Uso


4. Para iniciar a aplicação, execute o seguinte comando:

   ```bash
   streamlit run app/front.py

Isso abrirá a interface web da aplicação no seu navegador padrão. Na barra lateral, você poderá inserir a URL do vídeo do YouTube e uma pergunta sobre o vídeo. Clique no botão "Perguntar" para receber a transcrição e a resposta.
Estrutura do Projeto

    app/front.py: Arquivo principal que contém a lógica da interface do streamlit.
    requirements.txt: Lista de dependências do Python necessárias para o projeto.

Contribuição

Contribuições são bem-vindas! Se você tiver sugestões para melhorias, sinta-se à vontade para abrir um issue ou enviar um pull request.
Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.
Contato

Para mais informações, entre em contato pelo e-mail: douglaslundy@gmail.com


### Detalhes:

1. **Descrição**: Fornece uma visão geral clara do que o projeto faz.
2. **Funcionalidades**: Enumera as principais funcionalidades do projeto.
3. **Instalação**: Inclui instruções detalhadas para configurar o projeto, incluindo a criação de um ambiente virtual e a instalação das dependências.
4. **Uso**: Explica como executar o projeto.




   
