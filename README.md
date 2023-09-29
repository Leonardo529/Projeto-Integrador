# Briefing Sistema de Agendamento:
## Resumo:  Sistema de Organização de Aulas
Este projeto tem como objetivo desenvolver um sistema de organização de aulas para resolver um problema já existente, onde a falta de um sistema adequado resulta na confusão no quesito de alocação de salas, laboratórios, horários e professores. O sistema deve permitir que coordenadores e usuários (alunos e professores) acessem informações sobre aulas, laboratórios, horários, disciplinas e professores, dessa forma facilitando o planejamento.

## Requisitos da Primeira Versão (MVP):
- Os coordenadores devem poder cadastrar cursos, incluindo disciplinas e carga horária associada a cada disciplina.
- Os coordenadores devem ser capazes de cadastrar professores e vincular os mesmos a disciplinas específicas.
- O sistema deve permitir a alocação de disciplinas em salas de aula ou laboratórios, tendo a opção de ter ou não um professor atribuído à disciplina.
- Professores e alunos (Usuários) devem ser capazes de visualizar os horários de aulas e laboratórios relacionados às disciplinas do curso.
- O sistema deve permitir a definição de horários para cada ano e semestre, considerando as necessidades de cada disciplina e curso.
- O sistema deve suportar dois tipos de salas: laboratórios e salas de aula padrão.
- O sistema deve definir automaticamente salas para as disciplinas, levando em consideração a disponibilidade das salas e laboratórios.
- O sistema deve possuir dois perfis: coordenadores e usuários (alunos e professores).
- Usuários têm acesso somente à visualização de horários.
- Coordenadores têm acesso total ao sistema, incluindo a manutenção de cursos, disciplinas, professores e alocações.

## Observações:
- É importante manter o histórico das alocações e evitar a remoção de cursos, disciplinas, professores ou salas com alocações existentes.
- A disponibilidade dos professores deve ser mantida ao alterar sua disponibilidade.
- O sistema deve impedir o agendamento de aulas fora do horário e dias da semana de cada professor.
- O sistema não deve permitir agendar duas ou mais aulas no mesmo dia e horário para um professor.
- O sistema deve permitir a visualização de datas e horários disponíveis dentro de um mês.

## Responsividade:
O sistema deve ter um layout responsivo que funcione corretamente em larguras de tela iguais ou superiores a 350px.
Não é necessário suportar larguras de tela menores que 350px.
Este MVP visa atender às necessidades básicas de organização de aulas, sala e laboratório, e fornecer uma base sólida para futuras melhorias e expansões do sistema.

## Diagramas:

End Points:

![image](https://github.com/Leonardo529/Projeto-Integrador/assets/127244289/dd551f48-72d3-404c-b43d-48c994734095)


