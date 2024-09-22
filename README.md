# Queue System

Queue System é um projeto desenvolvido para gerenciar e manipular sistemas de filas, com uma arquitetura robusta utilizando Django, API REST, banco de dados, HTML, CSS, JavaScript e um sistema customizado de usuário e permissões.

## Visão Geral

O sistema foi projetado para facilitar a gestão de filas entre diferentes usuários, com funcionalidades de criação, atualização e monitoramento de filas através de uma interface amigável e responsiva. Ele também oferece uma API REST para integração com outros sistemas e manipulação dinâmica dos dados.

## Tecnologias Utilizadas

- **Django**: Framework web utilizado para o backend.
- **API REST**: Para a comunicação com o frontend e integração com outros sistemas.
- **HTML5, CSS3**: Linguagens utilizadas para a criação da interface de usuário.
- **JavaScript**: Usado para interação dinâmica com a página e atualizações em tempo real.
- **Banco de Dados**: Integração e manipulação eficiente de dados relacionados às filas.
- **Sistema de Usuário e Permissões**: Implementação customizada para controle de acesso e permissões de manipulação de dados.

## Funcionalidades

- Criação e gerenciamento de filas.
- Sistema de permissões customizado que permite diferentes níveis de acesso para usuários.
- API REST para manipulação de dados de forma eficiente e escalável.
- Integração com banco de dados para armazenamento e recuperação de dados de filas.
- Interface responsiva e interativa com atualização dinâmica de filas.

## Como Executar o Projeto

### Pré-requisitos

- Python 3.8+
- Django 3.x
- Django REST framework
- PostgreSQL (ou outro banco de dados de sua escolha)

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/queue-system.git
   
   ```
2. Instalando as dependências:
   ```bash
   pip install -r requeriments.txt
   ```
3. Configure o banco de dados no arquivo settings.py e execute as migrações:
   ```bash
   python manage.py migrate
   ```
4. Execute o servidor:
   ```bash
   python manage.py runserver
   ```
## Como Contribuir
1. Faça um fork do projeto.
2. Crie um branch para sua feature ou correção: **git checkout -b 3. minha-feature.**
4. Faça commit das suas mudanças: **git commit -m 'Adiciona nova feature'.**
5. Faça push para o branch: **git push origin minha-feature.**
6. Abra um Pull Request no GitHub.

## Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais informações.