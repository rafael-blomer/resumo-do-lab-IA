# Resumo do Lab de IA

Este repositório contém um resumo das lições aprendidas durante o desenvolvimento do laboratório de Inteligência Artificial (IA) na DIO.

Durante o laboratório, os principais pontos abordados foram:

- Criar o **AI Search** e configurá-lo no tier **Basic**;
- Criar um **serviço de IA**, assim como feito na aula anterior, utilizando o tier **Standard S0** e marcando a checkbox indicada;
- **Evitar criar recursos na região do Brasil**, devido ao custo mais elevado;
- Criar uma **conta de armazenamento (Storage Account)**:
  - O nome da conta deve ser único;
  - Em **Performance**, selecionar **Standard**;
  - Em **Redundancy**, escolher **LRS**;
- A conta de armazenamento aceita diversos tipos de recursos, mas é necessário **pré-definir** qual recurso será utilizado;
- Por padrão, a conta de armazenamento possui **regras de segurança** que, para fins do laboratório, precisarão ser ajustadas. Um exemplo é habilitar o **"Allow Blob anonymous access"**;
- No menu **Data Storage**, dentro de **Containers**, é necessário:
  - Criar um container com nome definido;
  - Alterar o **Anonymous access level** para **Container**;
- Realizar o **upload dos arquivos** no container criado;
- Acessar o mecanismo de busca (AI Search) e utilizar a opção **Import data** para importar os dados do Storage Account;
- Após responder um questionário para conectar o Storage Account ao mecanismo de busca, é possível realizar **consultas sobre os dados**;
- Neste laboratório, utilizamos os seguintes recursos:
  - Um serviço de busca (IA Search);
  - Um Storage Account;
  - Um serviço de IA para automação;
- O próximo passo será **integrar essa solução em uma aplicação**.
