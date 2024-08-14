# Lista de Tarefas

## Descrição do Projeto

Este projeto é uma aplicação backend de Lista de Tarefas (To-Do List), onde os usuários podem gerenciar suas tarefas diárias, incluindo a criação, edição, exclusão e marcação de tarefas como concluídas.

## Funcionalidades

- [x] Criar novas tarefas.
- [x] Editar tarefas existentes.
- [x] Excluir tarefas.
- [x] Marcar tarefas como concluídas.
- [x] Filtrar tarefas por status (pendentes ou concluídas).

## Requisitos Funcionais

1. **Cadastro de Tarefas**:
   - O sistema deve permitir que o usuário cadastre uma nova tarefa, fornecendo um título e uma descrição opcional.
   
2. **Edição de Tarefas**:
   - O sistema deve permitir que o usuário edite o título e a descrição de uma tarefa existente.

3. **Exclusão de Tarefas**:
   - O sistema deve permitir que o usuário exclua uma tarefa.

4. **Marcar Tarefa como Concluída**:
   - O sistema deve permitir que o usuário marque uma tarefa como concluída ou desfaça a conclusão.

5. **Filtragem de Tarefas**:
   - O sistema deve permitir que o usuário visualize todas as tarefas, apenas as concluídas ou apenas as pendentes.

## Requisitos Não Funcionais

1. **Desempenho**:
   - O sistema deve responder às solicitações do usuário em até 2 segundos.

2. **Segurança**:
   - O sistema deve garantir que apenas o usuário autenticado possa acessar e manipular suas tarefas.

3. **Manutenibilidade**:
   - O código deve ser modular e seguir boas práticas de programação, facilitando a manutenção e futuras extensões.

4. **Escalabilidade**:
   - O sistema deve ser escalável, podendo suportar um número crescente de usuários e tarefas sem perda significativa de desempenho.

5. **Confiabilidade**:
   - O sistema deve ser robusto e garantir que os dados do usuário não sejam perdidos ou corrompidos.

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução para JavaScript no servidor.
- **TypeScript**: Superset do JavaScript que adiciona tipagem estática.
- **Express**: Framework web para Node.js.
- **SQLite**: Banco de dados leve para armazenar as tarefas.
- **Jest**: Framework de testes para garantir a qualidade do código.

## Instalação

Passos para configurar o ambiente local:

1. Clone o repositório:
   ```bash
   git clone https://github.com/Avranche/repositorio.git
