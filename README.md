Desafio Técnico: CRUD de Perfis de Funcionários 

Objetivo:Desenvolver um CRUD que permita gerenciar perfis de funcionários internos da empresa.
A aplicação deve permitir criar, visualizar, atualizar e deletar perfis de funcionários. 

Exemplos de perfis : “ Financeiro, Comercial, TI “ 

Requisitos Funcionais 

1. Criar Perfil de Funcionário 

·         O usuário deve ser capaz de adicionar um novo perfil de funcionário. 

·         Campos obrigatórios: Nome, Sobrenome, Usuário,  Departamento, Email. 

·         Para criar um usuário, o perfil do solicitante deve ser "super" ou gestor do departamento. 

2. Visualizar Perfis de Funcionários 

·         O perfil "super" deve poder visualizar todos os usuários. 

·         O gestor de uma área não deve poder ver perfis de outra área. 

·         O "super" e o gestor devem ser capazes de buscar um ou mais perfis pelo endpoint. 

·         O "super" e o gestor devem poder buscar uma lista de perfis relacionados à busca caso tenha parâmetro. 

3. Atualizar Perfil de Funcionário 

·         O Super deve ser capaz de atualizar as informações de um perfil de funcionário existente. 

·         O gestor deve ser capaz de atualizar as informações de um perfil apenas se for do seu departamento 

4. Deletar Perfil de Funcionário 

· O super deve ser capaz de deletar um perfil de funcionário. 

· O gestor deve ser capaz apenas de deletar perfis da sua gestão. 

Requisitos Não Funcionais 

. Segurança 

· O endpoint de login deve gerar um JWT. 

· As rotas para visualizar, criar, atualizar e deletar perfis devem exigir autorização para serem acessadas. 

Tecnologias Usadas

· Backend: Python ( Django ou FastAPI ) 

· Banco de Dados: SQLite

· Autenticação: JWT 
