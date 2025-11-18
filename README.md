# FIC-DJANGO-2025
# FIC-DJANGO-2025

Este projeto foi desenvolvido durante as aulas do curso FIC (Formação Inicial e Continuada) como uma demonstração prática de como funciona o framework Django.

## Objetivo
O objetivo principal deste projeto é apresentar, de forma didática, os conceitos fundamentais do Django, incluindo:
- Estrutura de um projeto Django
- Criação de aplicativos (apps)
- Configuração de rotas (URLs)
- Definição de modelos (models)
- Utilização do painel administrativo
- Execução de migrações e manipulação do banco de dados

## Tecnologias Utilizadas
- **Python** (versão recomendada: 3.10+)
- **Django** (versão recomendada: 4.x)

## Estrutura do Projeto
- `mercado/`: Configurações principais do projeto Django
- `comercio/`: Aplicativo de exemplo criado em sala de aula
- `db.sqlite3`: Banco de dados SQLite utilizado para testes
- `manage.py`: Script de gerenciamento do Django

## Como Executar
1. Instale as dependências:
	```bash
	pip install django
	```
2. Execute as migrações:
	```bash
	python manage.py migrate
	```
3. Inicie o servidor de desenvolvimento:
	```bash
	python manage.py runserver
	```
4. Acesse o projeto em [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Observações
- O projeto foi criado para fins educacionais e pode ser expandido conforme o interesse dos alunos.
- O painel administrativo pode ser acessado em `/admin` após a criação de um superusuário:
	```bash
	python manage.py createsuperuser
	```

## Créditos
Projeto desenvolvido em sala de aula para demonstração do framework Django.
