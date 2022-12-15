O Prisioneiro dos Dados
De que serve o banco sem dados? Então vamos alimentar o banco!

Com o banco de dados para o sistema hospitalar montado completamente, é necessário incluir dados para realizar os devidos testes e validar sua viabilidade quanto ao sistema. Nesta etapa, também é importante realizar a separação de alguns scripts iniciais para o banco, com os dados que serão necessários a um povoamento inicial do sistema.

Jogando nas regras que você criou:
Crie scripts de povoamento das mesas ocorridas na atividade anterior Observe as seguintes atividades:
Inclui ao menos dez médicos de
Ao menos sete especialidades (considere a afirmação de que “entre as
especialidades há pediatria, clínica geral, gastroenterologia e dermatologia”)
Inclui pelo menos 15 pacientes.
Registre 20 consultas de diferentes pacientes e diferentes médicos (alguns pacientes aceitam mais que uma consulta). As consultas devem ter ocorrido entre 01/01/2015 e 01/01/2022. Ao menos dez consultas devem ter receituário com dois ou mais medicamentos.
Inclui ao menos quatro convênios médicos, associação ao menos cinco pacientes e cinco consultas.
Criar unidade de relacionamento entre médico e especialidade.
Criar Entidade de Relacionamento entre internação e enfermeiros.
Arrumar a chave estrangeira do relacionamento entre convênio e médico.
Criar entidade entre internação e enfermeiro.
Colocar chaves estrangeiras dentro da internação (Chaves Médico e Paciente).
Registre ao menos sete internações. Pelo menos dois pacientes devem ter se internado mais de uma vez. Ao menos três quartos devem ser cadastrados. As internações devem ter ocorrido entre 01/01/2015 e 01/01/2022.
Considerando que “a princípio o hospital trabalha com apartamentos, quartos duplos e enfermaria”, incluindo ao menos esses três tipos com valores diferentes.
Os dados do tipo de quarto, convênio e especialidade são essenciais para a operação do sistema e, portanto, devem ser povoados assim que o sistema for instalado.