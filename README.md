# 🗓️ Gerenciador de Tarefas

![Status do Projeto](https://img.shields.io/badge/status-concluído-brightgreen)

Um projeto simples para um sistema de agendamento de tarefas (CRUD), desenvolvido como parte do bootcamp da DIO. A aplicação consiste em uma API RESTful construída com .NET 6 e um frontend de página única utilizando AngularJS.

---
## ✨ Funcionalidades

- [x] **Criar tarefas:** Adicionar novas tarefas com título, descrição, data e status.
- [x] **Listar tarefas:** Visualizar todas as tarefas cadastradas.
- [x] **Atualizar tarefas:** Modificar informações de uma tarefa existente.
- [x] **Deletar tarefas:** Excluir uma tarefa.
- [x] **Filtrar tarefas:** A API suporta buscas por título, data ou status.

---

## 🛠️ Tecnologias Utilizadas

Backend
<div>
<img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET 6" />
<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" />
<img src="https://img.shields.io/badge/Entity%20Framework-4E2579?style=for-the-badge" alt="Entity Framework Core" />
<img src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white" alt="SQL Server" />
</div>

Frontend
<div>
<img src="https://img.shields.io/badge/AngularJS-E23237?style=for-the-badge&logo=angularjs&logoColor=white" alt="AngularJS" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
<img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
</div>

---

## 🌐 Endpoints da API


| Método HTTP | Endpoint              | Descrição                                 |
|-------------|-----------------------|-------------------------------------------|
| `GET`       | `/ObterTodos`         | Retorna uma lista de todas as tarefas.    |
| `GET`       | `/{id}`               | Retorna uma tarefa específica pelo seu ID.  |
| `GET`       | `/ObterPorTitulo`     | Busca tarefas pelo título.                |
| `GET`       | `/ObterPorData`       | Busca tarefas por uma data específica.    |
| `GET`       | `/ObterPorStatus`     | Busca tarefas por um status específico.   |
| `POST`      | `/`                   | Cria uma nova tarefa.                     |
| `PUT`       | `/{id}`               | Atualiza uma tarefa existente.            |
| `DELETE`    | `/{id}`               | Deleta uma tarefa pelo seu ID.            |