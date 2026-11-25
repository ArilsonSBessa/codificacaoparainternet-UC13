# Personal trainer Marina Alves — estático ou dinâmico?

## A página de hoje é estática
Ela só apresenta a Marina. O conteúdo é o mesmo para qualquer visitante e está escrito direto no HTML, sem servidor processando nada nem banco de dados.

## O site do ano que vem será dinâmico
Cada aluno vai ver os próprios treinos e marcar horários. O conteúdo muda conforme quem acessa e conforme os dados salvos, então é preciso um servidor e um banco de dados.

## O que precisa existir para a versão do ano que vem

### Front-end (o que roda no navegador do aluno)
- Tela de login e cadastro do aluno
- Agenda/calendário mostrando os horários livres, com botão para marcar e cancelar
- Página "Meus treinos" que exibe os exercícios do aluno logado
- Formulários com validação dos campos (data, horário, e-mail)
- Comunicação com o back-end (requisições à API) e exibição de mensagens de sucesso ou erro

### Back-end (o que roda no servidor)
- Servidor com uma API (por exemplo, Node.js + Express) que recebe os pedidos do front-end
- Banco de dados com as tabelas de alunos, horários/agendamentos e treinos
- Autenticação: guardar a senha com hash, criar a sessão ou o token e garantir que cada aluno só veja os próprios dados
- Regras de agendamento: impedir dois alunos no mesmo horário e respeitar os horários de trabalho da Marina
- Área administrativa para a Marina cadastrar treinos e gerenciar a agenda
- Hospedagem do servidor e do banco (o site de hoje cabe numa hospedagem estática; o novo, não)
