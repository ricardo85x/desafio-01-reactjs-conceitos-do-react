# Desafio 01 - Conceitos do React

# 💻 Sobre o desafio

Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no ReactJS

Essa será uma aplicação onde o seu principal objetivo é uma pequena aplicação de atividades a fazer, para treinar um pouco mais sobre manipulação do estado no React.

- Adicionar uma nova tarefa
- Remover uma tarefa
- Marcar e desmarcar uma tarefa como concluída

A seguir veremos com mais detalhes o que e como precisa ser feito 🚀

## Template da aplicação

Para te ajudar nesse desafio, criamos para você esse modelo que você deve utilizar como um template do GitHub.

O template está disponível na seguinte URL: 

[https://github.com/rocketseat-education/ignite-template-reactjs-conceitos-do-react](https://github.com/rocketseat-education/ignite-template-reactjs-conceitos-do-react)

**Dica**: Caso não saiba utilizar repositórios do GitHub como template, temos um guia em **[nosso FAQ](https://www.notion.so/FAQ-Desafios-ddd8fcdf2339436a816a0d9e45767664).**

## O que devo editar na aplicação?

Com o template já clonado, as depêndencias instaladas, você deve completar onde não possui código com o código para atingir os objetivos de cada teste. Nesse desafio, você deve editar apenas o seguinte arquivo para completar as funcionalidades da aplicação:

- [src/components/TaskList.tsx;](https://github.com/rocketseat-education/ignite-template-reactjs-conceitos-do-react/blob/main/src/components/TaskList.tsx)

### components/TaskList.tsx

Esse é o componente responsável por todas as funcionalidades da aplicação, é um componente simples, mas onde botaremos em prática várias partes da manipulação do estado.

Você deve criar as funcionalidades para as três funções presentes nesse arquivo, que são:

- **handleCreateNewTask**: Deve ser possível adicionar uma nova task no estado de `tasks`, com os campos `id` que deve ser gerado de forma aleatória, `title` que deve ser um texto e `isComplete` que deve iniciar como false.
- **handleToggleTaskCompletion:** Deve alterar o status de `isComplete` para uma task com um ID específico que é recebido por parâmetro.
- **handleRemoveTask:** Deve receber um ID por parâmetro e remover a task que contém esse ID do estado.