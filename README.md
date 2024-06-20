# Aplicativo de Gerenciamento Orçamentário para Produtora Audiovisual

## Descrição

Este projeto é um aplicativo de gerenciamento orçamentário desenvolvido para uma produtora audiovisual. Ele permite criar, visualizar e gerenciar orçamentos, além de fornecer um dashboard para monitorar metas de vendas e outras funcionalidades essenciais para o gerenciamento financeiro da empresa.

## Funcionalidades

1. **Criação de Orçamentos**
   - Interface para criar novos orçamentos.

2. **Visualização de Orçamentos**
   - Lista de orçamentos com filtros para mostrar:
     - Ativos
     - Aguardando Resposta
     - Aprovados
     - Recusados

3. **Dashboard**
   - Exibição de metas de vendas do mês.
   - Valor atual das vendas.
   - Valor restante para atingir a meta.
   - Responsáveis por cada venda.

4. **Sessão de Configurações**
   - Configurações gerais do aplicativo.

## Tecnologias Utilizadas

### Backend
- **Python**
- **Django** (ou Flask, dependendo da escolha final)
- **Django REST Framework** para criação de APIs RESTful

### Frontend
- **React** para construção da interface do usuário

### Banco de Dados
- **PostgreSQL** (ou outro banco de dados relacional)

## Estrutura do Projeto

```plaintext
.
├── backend
│   ├── manage.py
│   ├── app
│   │   ├── models.py
│   │   ├── views.py
│   │   ├── serializers.py
│   │   └── urls.py
│   ├── project_name
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
├── frontend
│   ├── public
│   ├── src
│   │   ├── components
│   │   ├── App.js
│   │   └── index.js
└── README.md
```

## Etapas de Desenvolvimento
**Backend**

  1. Configuração do Ambiente
        Instalar Python e configurar um ambiente virtual.
        Configurar um projeto Django e um app para orçamentos.

  2. Modelagem do Banco de Dados
        Definir os modelos de dados para orçamentos e vendas.

  3. Criação das APIs
        Implementar as views e serializers para CRUD de orçamentos.
        Implementar views e serializers para o dashboard de vendas.

  4. Testes
        Escrever testes unitários e de integração.

  5. Documentação
        Documentar a API (Swagger ou outra ferramenta).

**Frontend**

  1. Configuração do Ambiente
        Configurar um ambiente Node.js e criar um projeto React.

  2. Desenvolvimento de Componentes
        Criar componentes para:
            Formulário de criação de orçamentos.
            Lista de orçamentos com filtros.
            Dashboard de vendas.
            Página de configurações.

  3. Integração com o Backend
        Conectar o frontend ao backend usando Axios ou Fetch.

  4. Testes e Depuração
        Realizar testes manuais e automatizados.

**Implementação**

  1. Backend
        Implantar o backend em um servidor (Heroku, AWS, etc.).

  2. Frontend
        Implantar o frontend em um serviço de hospedagem estática (Netlify, Vercel, etc.).

  3. Monitoramento
        Configurar monitoramento e logging.

## Como Contribuir

    1. Faça um fork do projeto.
    2. Crie uma branch para sua feature (git checkout -b feature/sua-feature).
    3. Commit suas mudanças (git commit -m 'Adiciona nova feature').
    4. Push para a branch (git push origin feature/sua-feature).
    5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.
