# 🌱 RecuperaMangue

## Sobre o Projeto

O **RecuperaMangue** é uma plataforma web desenvolvida durante a **Global Solution FIAP 2024**, com o objetivo de utilizar a tecnologia como ferramenta de apoio à **conservação, monitoramento e recuperação dos manguezais**.

A plataforma reúne informações e recursos voltados à preservação desses ecossistemas, buscando facilitar o acesso à informação, incentivar a conscientização ambiental e aproximar a comunidade de iniciativas de conservação.

## 🎯 Objetivo

O projeto busca contribuir para a preservação dos manguezais por meio de uma solução tecnológica que permita:

- Monitorar áreas de manguezais;
- Divulgar projetos de recuperação e conservação;
- Disponibilizar conteúdos educacionais;
- Facilitar denúncias de possíveis ações ilegais;
- Incentivar a participação da comunidade;
- Apresentar informações ambientais de forma acessível.

## 🚀 Funcionalidades

### 📊 Monitoramento
- Mapa interativo de áreas monitoradas;
- Visualização de dados ambientais;
- Informações climáticas;
- Gráficos e relatórios.

### 🌱 Projetos
- Listagem de projetos de conservação;
- Informações sobre cada iniciativa;
- Filtros por localização, status e impacto.

### 📚 Educação
- Conteúdos educativos sobre manguezais;
- Artigos e materiais informativos;
- Divulgação de eventos, workshops e palestras.

### 🚨 Denúncias
- Formulário para denúncias de ações ilegais;
- Registro de informações sobre ocorrências;
- Apoio à fiscalização e conservação dos manguezais.

### 📩 Contato
- Formulário de contato;
- Informações para comunicação;
- Canais de interação com a comunidade.

## 🛠️ Tecnologias

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Django

### Banco de Dados
- PostgreSQL

### APIs e Serviços
- Google Maps API
- OpenWeather API
- Google Analytics

### Infraestrutura
- AWS EC2
- AWS S3
- Docker

### Bibliotecas
- Axios
- D3.js
- Chart.js

## 🔐 Segurança

O projeto considera diferentes mecanismos de segurança, incluindo:

- Autenticação de usuários;
- Controle de acesso baseado em funções;
- HTTPS/SSL;
- Hashing de senhas;
- Validação e sanitização de dados;
- Proteção contra SQL Injection;
- Monitoramento de atividades;
- Logs de segurança;
- Backups dos dados.

## ♿ Acessibilidade

A plataforma foi planejada considerando princípios de acessibilidade digital, incluindo:

- Navegação por teclado;
- Compatibilidade com leitores de tela;
- Atributos ARIA;
- Textos alternativos para imagens;
- Contraste adequado;
- Redimensionamento de texto;
- Legendas para conteúdos audiovisuais;
- Formulários com mensagens de erro claras.

## 📐 Arquitetura

A aplicação utiliza uma arquitetura composta por frontend, backend, banco de dados, APIs externas e serviços em nuvem.

```text
Usuário
   │
   ▼
React.js
   │
   ▼
Python / Django
   │
   ├── PostgreSQL
   ├── Google Maps API
   ├── OpenWeather API
   ├── AWS S3
   └── AWS EC2
