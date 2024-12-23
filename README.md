# Análise Flask

Este repositório contém o projeto de Análise de Dados e Visualização, desenvolvido pela equipe Serra Rocketry.

## Descrição

O Analise Flask é uma aplicação web desenvolvida com Flask. O objetivo do projeto é fornecer uma interface para gerenciar e visualizar dados relacionados aos projetos de Foguetemodelismo.

## Estrutura do Projeto

- `app.py`: Contém o código-fonte da aplicação Flask.
- `static/`: Arquivos estáticos: CSS, JavaScript e imagens.
- `templates/`: Templates HTML utilizados pela aplicação.
- `archives/`: Arquivos salvos de análises.
- `requiriments.txt`: Pacotes python necessários para rodar o programa.

## Instalação

1. Clone o repositório:
   ```bash
   git clone 
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd Analise_Flask
   ```
3. Crie um ambiente virtual:
   ```bash
   python3 -m venv venv
   ```
4. Ative o ambiente virtual:
   - No Linux/Mac:
     ```bash
     source venv/bin/activate
     ```
   - No Windows:
     ```bash
     venv\Scripts\activate
     ```
5. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

## Uso

1. Execute o arquivo:
   ```bash
   python3 app.py
   ```

A aplicação estará disponível em `http://127.0.0.1:5000` (endereço local) ou para outros dispositivos acessando o IP da máquina Host e a porta `5000`.

## Contribuição

1. Faça um fork do projeto.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`).
4. Faça push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.
