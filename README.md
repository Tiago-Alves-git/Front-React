# Instruções para Desenvolvimento da Aplicação em React

## Requisitos do Projeto

### Página de Login:
- Layout simples, centralizado e com cores ou imagens coerentes com o tema (fundo verde).
- Opções de login via Google ou por e-mail e senha.
- Campos necessários: e-mail, senha.
- Design semelhante ao seguinte esquema:
  ![Exemplo de Página de Login](exemplo_login.png)

### Página de Cadastro:
- Layout semelhante à página de login.
- Opções de cadastro via Google ou preenchimento de e-mail e senha.
- Campos necessários: e-mail, senha.
- Design similar ao esquema da página de login.

### Página Principal (Chat):
- Layout semelhante ao estilo de conversa do ChatGPT.
- Área de chat à direita para exibir as mensagens.
- Área à esquerda para mostrar as conversas antigas.
- Caixa de texto para digitar mensagens e botão para enviar.
- Design inspirado no seguinte esquema:
  ![Exemplo de Página de Chat](exemplo_chat.png)

## Desenvolvimento

### Configuração do Ambiente:
- Utilize o Create React App ou uma configuração similar para iniciar o projeto.

### Estrutura do Projeto:
- Crie os componentes necessários para cada página (Login, Cadastro, Chat).
- Organize os arquivos em uma estrutura clara dentro da pasta `src`.

### Integração com APIs:
- Utilize APIs do Google para autenticação (OAuth) e para envio de mensagens no chat.
- Implemente um mock para simular as respostas da API do chat durante o desenvolvimento.

### Estilização:
- Utilize CSS ou bibliotecas de estilização (como Styled Components) para aplicar o layout especificado.
- Garanta que o design seja responsivo e amigável para diferentes tamanhos de tela.

### Testes e Deploy:
- Teste a aplicação localmente para garantir o funcionamento correto.
- Faça o deploy da aplicação em um ambiente de desenvolvimento para revisão e teste.

## Observações

- **Bibliotecas e Frameworks:**
  - A escolha de outras bibliotecas e frameworks além do React fica a critério da equipe de desenvolvimento.

- **APIs e Mocks:**
  - Certifique-se de implementar adequadamente as integrações com as APIs do Google e o mock para as respostas do chat durante o desenvolvimento.
