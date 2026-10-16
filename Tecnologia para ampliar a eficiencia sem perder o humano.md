Técnicas de I.A utilizadas:
Utiliza a base de dados, informações, histórico do Cliente dentro da plataforma para agendamentos 

Algoritmo: XGBoost, que é o melhor para basea em árvores de decisão
Tipo de problema: classificação binária, com
estimativa probabilística.

Treinamento supervisionado: cada agendamento
histórico é associado a um resultado conhecido:
compareceu ou não compareceu.

Inferência: quando um agendamento é criado, o
modelo analisa suas características e retorna uma
probabilidade de falta, que o sistema apresenta em
faixas de risco. 

Target: (X, Y) 0 ou 1
Cliente: (VAI) ou (NÃO Vai) na consulta.

Copiloto clínico: É a I.A do Profissional(médico), que ele faz a criação, utilizando a sua base de conhecimentos e buscando fazer um relatório com agilidade sobre tal cliente, usando a base de dados do paciente.

Cenários:
Identificando o cliente, estudando as informações sobre o próprio.

Função da I.A: Aprimorar, ajudar no objetivos e não substituir o trabalho feito pelo Humano
A I.A utiliza a questão da IMAGEM, Pesquisa e Clínica, ajudando a agilizando o processo, a descoberta e desenvolvimento de medicamentos 
Cuidados com I.A, ela pode dar uma resposta não esperada, não deixar ela trabalhar sozinha, sempre analisando e comparando se ela não esta adicionando informações erradas ou dados que não existem
