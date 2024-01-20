Inicio do projeto: 20/01/2024
Fim do projeto: 20/01/2024

Este projeto foi desenvolvido para acompanhar o curso: "Django: templates e boas práticas" da Alura.


O que aprendemos: 

Parte 01: Iniciando a aplicação e subindo o servidor
- Conhecemos o Django 4, sua história e principais aspectos do framework;
- Aprendemos a estabelecer um ambiente virtual de desenvolvimento em Python com o pacote virtualenv;
- Criamos o projeto Django através do comando django-admin startproject setup;
- Subimos o servidor pela primeira vez através do comando python manage.py runserver

Parte 02: Configurações, Git e Github
- Mudamos a timezone e a linguagem do projeto fazendo alterações no arquivo settings.py;
- Aumentamos a segurança do projeto protegendo a SECRET_KEY e instalando o pacote python-dotenv e criando o arquivo .env;
- Subimos o projeto para um repositório remoto no github e tomamos o cuidado de criar o arquivo .gitignore para não
  deixarmos vulneráveis dados sensíveis do nosso projeto.

Parte 03: Projeto, app e views
- Entendemos a diferença de projeto e app no universo de desenvolvimento com Django e criamos a primeira app com o
  comando python manage.py startapp galeria;
- Criamos a primeira página personalizada na web configurando rotas dentro dos arquivos views.py e urls.py;
- Aprendemos a boa prática de criação de um arquivo urls.py para cada app;
- Isolamos o template da app galeria, criando uma nova pasta chamada templates e reconfigurando o settings.py.

Parte 04: Arquivos estáticos
- Aprendemos a como organizar melhor os arquivos estáticos através da criação pastas indicadoras de cada app
  dentro da pasta templates;
- Usamos código Python embedado dentro de arquivos HTML graças ao Jinja2;
- Implementamos um novo template HTML personalizado junto de diversos arquivos estáticos e melhoramos a aparência do site.

Parte 05: Boas práticas e partials
- Aprendemos sobre a prática DRY (Don’t Repeat Yourself - Não se repita) e a colocamos em ação criando uma arquivo chamado
  base.html que irá conter código repetido em diversos templates para evitar essa repetição;
- Utilizamos o artifício das Partials para seguir com a prática DRY, evitando mais repetição de código e tornando mais
  eficiente a escalabilidade do site.


Foram importados de um outro repositório todas as imagens, arquivos .css, arquivos .html.
Realizamos durante o curso a manipulção de alguns arquivos .html para implementar a utilização do framework Django.

Níveis de conhecimento em programação:
Python: intermediário baixo
Django: iniciante
CSS: iniciante
Javascript: iniciante
Git e Github: iniciante
