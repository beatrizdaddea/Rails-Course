# Study Content - Ruby on Rails

Este documento aborda uma série de tópicos relacionados ao desenvolvimento com Ruby on Rails. Aqui, você encontrará informações sobre instalação, criação de projetos, estrutura de diretórios, gems, autenticação, Sidekiq, Cancancan, modelos, ActiveRecord, conexão com o banco de dados, views, rotas, layouts, controllers e construção de aplicações web com RoR.

## Instalação, Criação de Projetos e Estrutura de Diretórios

- **Instalação**: Instruções para instalar Ruby on Rails podem ser encontradas na [documentação oficial](https://guides.rubyonrails.org/getting_started.html#installing-rails).
- **Criação de Projetos**: Utilize o comando `rails new nome_do_projeto` para criar um novo projeto Rails.
- **Estrutura de Diretórios**: Rails segue uma estrutura de diretórios padrão para organizar seu código fonte, configurações e recursos. Consulte a [guia oficial](https://guides.rubyonrails.org/getting_started.html#the-rails-directory-structure) para mais detalhes.

## Gems, Gemfile e Gemfile.lock

- **Gems**: Gems são pacotes de software reutilizáveis escritos em Ruby. Elas são gerenciadas pelo RubyGems.
- **Gemfile**: O Gemfile é onde você lista as dependências do seu projeto Rails.
- **Gemfile.lock**: O Gemfile.lock é gerado automaticamente e contém as versões exatas das gems e suas dependências.

## Autenticação, Sidekiq, Cancancan

- **Autenticação**: Rails oferece várias opções para autenticação, incluindo gems como Devise e Authlogic.
- **Sidekiq**: Sidekiq é uma biblioteca para processamento de background em Ruby que funciona bem com Rails.
- **Cancancan**: Cancancan é uma biblioteca de controle de acesso que simplifica a autorização em Rails.

## Models e ActiveRecord

- **Associações**: ActiveRecord permite definir associações entre modelos, como has_many, belongs_to, has_one, etc.
- **Validações**: Você pode definir validações nos modelos para garantir a integridade dos dados.
- **Callbacks**: Callbacks são métodos que são chamados em momentos específicos do ciclo de vida de um objeto ActiveRecord.

## Conexão com o Banco, database.yml, Migrações e Interface de Query

- **Conexão com o Banco**: Configurações de conexão com o banco de dados são especificadas no arquivo `database.yml`.
- **Migrações**: Migrações são usadas para modificar o esquema do banco de dados de forma controlada.
- **Interface de Query**: ActiveRecord fornece uma interface orientada a objetos para interagir com o banco de dados.

## View, Rotas, Layouts e Render

- **View**: As views são responsáveis por renderizar a interface do usuário.
- **Rotas**: As rotas são definidas no arquivo `routes.rb` e mapeiam URLs para controladores e ações.
- **Layouts**: Layouts definem a estrutura comum de uma página, como cabeçalho e rodapé.
- **Render**: Render é usado para renderizar views ou parciais em um controlador.

## Controller, ActionController, Métodos CRUD, Presenters e Service Objects

- **Controller**: Controladores são responsáveis por receber requisições do navegador, processá-las e enviar uma resposta.
- **ActionController**: ActionController é a base para controladores em Rails.
- **Métodos CRUD**: Os controladores geralmente implementam os métodos CRUD (Create, Read, Update, Delete) para interagir com os modelos.
- **Presenters e Service Objects**: São padrões de design comuns para manter a lógica de negócios fora dos controladores.

## Constrói Aplicações Web com RoR

Ruby on Rails é um framework poderoso para construir aplicações web de todos os tamanhos e complexidades. Utilizando os conceitos e práticas mencionados acima, você estará bem equipado para desenvolver aplicações web robustas e escaláveis utilizando Ruby on Rails.

**[documentação oficial](https://guides.rubyonrails.org/)**
