# Sistema de Gerenciamento de Escola

Este projeto é um aplicativo Java desenvolvido com o Spring Framework que permite o gerenciamento de alunos, cursos, professores e matrículas em uma escola. O projeto inclui uma API com várias funcionalidades para atender às necessidades de gerenciamento da escola.

## Funcionalidades

1. Cadastro de alunos.
2. Cadastro de curso.
3. Cadastro de professor.
4. Listar todos os alunos.
5. Listar todos os professores.
6. Listar todos os cursos.
7. Atualizar curso do aluno.
8. Deletar curso.
9. Deletar aluno.
10. Deletar professor.

## Entidades

### Aluno
- ID
- Nome
- Idade
- E-mail

### Curso
- ID
- Nome
- Carga Horária

### Matrícula
- ID
- Data da Matrícula
- Aluno
- Curso

### Professor
- ID
- Nome
- Idade
- Curso
- Salário

## DTOs

1. AlunoDTO
2. CursoDTO
3. MatriculaDTO
4. ProfessorDTO

## Testes

Os testes dos controllers podem ser realizados usando a biblioteca MockWeb. Certifique-se de criar testes para todas as funcionalidades da API para garantir o seu correto funcionamento.

## Como Executar

1. Clone este repositório.
2. Certifique-se de ter as configurações adequadas do Java e do Spring Framework.
3. Configure o banco de dados de acordo com as especificações do projeto.
4. Execute a aplicação.
5. Utilize ferramentas como o Postman ou o cURL para interagir com a API.

## Contribuição

Contribuições são bem-vindas! Se você encontrar problemas ou tiver sugestões para melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.


