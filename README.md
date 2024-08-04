
# DESAFIO BEEDOO

## User Story

### 1.Usuário quer cadastrar um novo curso

Como usuário da plataforma Beedoo,  
Eu quero cadastrar cursos preenchendo um formulário com informações detalhadas,  
Para que eu possa adicionar um novo curso à plataforma.


### 2.Usuário quer visualizar uma mensagem de confirmação após cadastrar um curso com sucesso

Como usuário da plataforma Beedoo,
Eu quero visualizar uma mensagem de confirmação após cadastrar um curso,
Para que eu saiba que o curso foi adicionado com sucesso.


### 3.Usuário como Administrador quer ser notificado sobre campos obrigatórios não preenchidos

Como usuário,
Eu quero ser notificado sobre campos obrigatórios não preenchidos,
Para que eu possa preencher corretamente todos os campos necessários ao cadastrar um curso.

### 4.Usuário quer ser notificado sobre erros de formato em campos de data

Como usuário,
Eu quero ser notificado sobre erros de formato nos campos de data,
Para que eu possa corrigir os formatos de data e cadastrar o curso corretamente.

### 5.Usuário quer definir o número de vagas ao cadastrar um curso

Como usuário,
Eu quero definir o número de vagas disponíveis que seja sempre positivo,
Para que eu possa controlar a quantidade de alunos inscritos no curso.

### 6.Usuário quer adicionar uma imagem de capa ao cadastrar um curso

Como usuário,
Eu quero adicionar uma imagem de capa ao curso,
Para que o curso tenha uma apresentação visual atraente para os alunos.

### 7.Usuário quer especificar o tipo de curso (online/presencial)

Como usuário,
Eu quero especificar se o curso é online ou presencial,
Para que os alunos saibam o formato do curso antes de se inscreverem.

### 8.Usuário quer definir as datas de início e fim do curso

Como usuário,
Eu quero definir as datas de início e fim do curso,
Para que os alunos saibam o período de duração do curso.

## Cenários e Casos de Teste

### Testes de Sucesso

Caso de teste 1: Cadastrar um novo curso com sucesso
  Dado que o usuário está na tela de cadastro de curso
  Quando o usuário preenche todos os campos obrigatórios e opcionais corretamente
  E clica no botão "CADASTRAR CURSO"
  Então o curso é cadastrado com sucesso
  E uma mensagem de confirmação é exibida



### Testes de insucesso

Caso de teste 2: Cadastro de um novo curso sem preencher campos obrigatórios
  Dado que o usuário está na tela de cadastro de cursos
  Quando o usuário não preenche um ou mais campos obrigatórios
  E clica no botão "CADASTRAR CURSO"
  Então uma mensagem de erro é exibida solicitando o preenchimento dos campos obrigatórios

Caso de teste 3: Cadastro de um novo curso com data no formato incorreto
  Dado que o usuário está na tela de cadastro de cursos
  Quando o usuário preenche a data no formato incorreto
  E clica no botão "CADASTRAR CURSO"
  Então uma mensagem de erro é exibida solicitando a correção do formato da data

Caso de teste 4: Cadastro de um novo curso com número de vagas negativo
  Dado que o usuário está na tela de cadastro de cursos
  Quando o usuário preenche o campo "Número de vagas" com um valor negativo
  E clica no botão "CADASTRAR CURSO"
  Então uma mensagem de erro é exibida solicitando a correção do número de vagas

Caso de teste 5: Cadastro de um novo curso sem preencher o campo opcional "Número de vagas"
  Dado que o usuário está na tela de cadastro de cursos
  Quando o usuário não preenche o campo opcional "Número de vagas"
  E clica no botão "CADASTRAR CURSO"
  Então uma mansagem de erro é exibida solicitando a correção

Caso de teste 6: Excluir cursos com sucesso
  Dado que o usuário esta na tela de lista de cursos
  Quando o usuário clica no botão "EXCLUIR CURSO"
  Então o curso é excluido com sucesso
  E uma mensagem de confirmação é exibida
  
## Cenários e Casos de Teste
Todos os cenários e casos de teste estão documentados na seguinte planilha do Google Docs:

https://docs.google.com/spreadsheets/d/1aG__W4kAChE0RGQS-ctfkqLvjbiKnF63hiRArUfQxAI/edit?gid=0#gid=0


## Evidências de Teste
As evidências de teste em formato MP4 podem ser acessadas nos seguintes links:

[Caso de teste 1](https://drive.google.com/file/d/1J6fRGi1rdQPNhf9Jn00jNhnI6eAjVhO6/view?usp=drive_link)

[Caso de teste 2](https://drive.google.com/file/d/17apuUR0-qD8vNVSlGaCkOLaeJ8tMs27N/view?usp=drive_link)

[Caso de teste 3](https://drive.google.com/file/d/1g45jCznEPIIlCr0-UXswhKtVURRH-7om/view?usp=drive_link)

[Caso de teste 4](https://drive.google.com/file/d/1NxyMCbFBeDyvX6z311Bw5Vri6IYOJlOv/view?usp=drive_link)

[Caso de teste 5](https://drive.google.com/file/d/1rL1bX3EdrTZOFoJND_8qWSoLh-gpfU9A/view?usp=drive_link)

[Caso de teste 6](https://drive.google.com/file/d/1b1eG6EagyByJDQhJJXkuyqh5CmqRFSYF/view?usp=drive_link)

### Relatorios de Bugs Encontrados

O usuário pode cadastrar um novo curso sem preencher campos do formulário, sem receber mensagens de erro ou de alerta.
O curso não é excluído corretamente quando o botão "EXCLUIR CURSO" é clicado.
O sistema não valida o formato da data corretamente e aceita datas em formatos incorretos.
O campo "Número de vagas" aceita valores negativos sem apresentar mensagens de erro.
O campo "Número de vagas" não impõe um limite mínimo para estabelecer o número de vagas para o curso.
Não há campo obrigatório para criação do cadastro de um curso.


