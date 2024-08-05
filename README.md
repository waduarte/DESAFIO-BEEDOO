# DESAFIO-BEEDOO
Planejamento e evidências do desafio Beedoo
- Documentação de todos os cenários e casos de teste junto com as evidências dos cenários com erros 
https://docs.google.com/spreadsheets/d/1PeayYiwLtalwKhYDzPdC4PrQHwf1jYVn3TOl9xH0NvE/edit?usp=sharing

---
# ETAPA 1
---
## User Stories para o Módulo de Cursos:

### 1- Implementar a visualização dos cursos cadastrados na plataforma.

### História de usuário
> Como usuário da plataforma do módulo de curso Beedoo.
> 
> Quero visualizar a lista de cursos.
> 
> Para verificar quais cursos estão disponíveis.

 ### Critérios de Aceitação:
1. A página inicial (home) deve apresentar toda lista de cursos cadastrados na plataforma.
2. A lista apresentada de cursos cadastrados na plataforma deve trazer todos os itens do modal de cadastro de cursos, são eles:
  - Nome do curso 
  - Descrição do curso 
  - Instrutor
  - Capa cadastrada no sistema
  - Data de início 
  - Data de fim
  - Número de vagas 
  - Tipo de curso cadastrado.

3. A lista de cursos que será apresentada deve ser consistente com os padrões layout da plataforma (cores, fontes).   
4. Deve haver uma mensagem ou indicação quando não houverem cursos cadastrados.
---
---

### 2- Deve ser possível cadastrar cursos na plataforma.

> Como administrador da plataforma do módulo de curso Beedoo.
> 
> Quero cadastrar novos cursos no sistema.
> 
> Para eu possa oferecer e gerenciar os cursos disponíveis para os usuários.

 ### Critérios de Aceitação:
 
1. Criar campo: (Nome do Curso) O campo deve permitir a entrada de todo tipo de caracteres.
2. Criar campo: (Descrição do Curso) O campo deve permitir a entrada de todo tipo de caracteres.
3. Criar campo: (Instrutor): O campo deve permitir a entrada de todo tipo de caracteres.
4. Criar campo: (URL da Imagem do Curso): O campo deve aceitar um URL válido.
5. Criar dois campos um do lado do outro com: (Data de Início) e (Data de fim) Os campos devem aceitar datas no formato brasileiro (DD/MM/AAAA).  Deve haver a possibilidade de mostrar a data por um selector de datas, e este deve ter um Tooltip escrito: `mostrar seletor de datas´.
6. Criar campo: (Número de vagas) O campo deve permitir apenas a entrada de um número inteiro positivo.
7. Criar campo (Tipo de curso) Deve ser um campo de "combo de seleção" com opções predefinidas (ex: Presencial, Online).
8. Deve ser implementado um botão com a seguinte escrita: (CADASTRAR CURSO), esse botão deve ser clicável e ao clicar deve ser possível salvar os dados.
9. Validação dos Campos: Todos os campos são obrigatórios e devem ser validados antes de salvar o curso.
10. Mensagens de Erro: Deve exibir mensagens de erro apropriadas se os dados inseridos não atenderem aos critérios.
11. Persistência dos Dados: Deve manter os padrões da plataforma.
12. Todos os campos devem conter o placeholder correspondente ao campo criado. E no momento em que o usuário clicar no campo o placeholder deve se deslocar para a parte superior dentro do campo e ficar em azul com a letra de fonte menor.

### Decisões para Criar User Stories:

1. Busquei evidenciar as necessidades dos usuários finais da plataforma. 
2. Pensei na usabilidade e na acessibilidade do usuário ao navegar pelo site garantindo de forma eficiente uma boa navegação para a escolha do curso.

---
