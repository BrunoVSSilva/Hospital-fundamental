# Hospital-fundamental
Atividade de banco de dados que visa ensinar o banco de dados conceitual:

Analise a seguinte descrição e extraia dela os requisitos para o banco de dados:
O hospital necessita de um sistema para sua área clínica que ajude a controlar consultas realizadas. Os médicos podem ser generalistas, especialistas ou residentes e têm seus dados pessoais cadastrados em planilhas digitais. Cada médico pode ter uma ou mais especialidades, que podem ser pediatria, clínica geral, gastroenterologia e dermatologia. Alguns registros antigos ainda estão em formulário de papel, mas será necessário incluir esses dados no novo sistema.

Os pacientes também precisam de cadastro, contendo dados pessoais (nome, data de nascimento, endereço, telefone e e-mail), documentos (CPF e RG) e convênio. Para cada convênio, são registrados nome, CNPJ e tempo de carência.

As consultas também têm sido registradas em planilhas, com data e hora de realização, médico responsável, paciente, valor da consulta ou nome do convênio, com o número da carteira. Também é necessário indicar na consulta qual a especialidade buscada pelo paciente.

Deseja-se ainda informatizar a receita do médico, de maneira que, no encerramento da consulta, ele possa registrar os medicamentos receitados, a quantidade e as instruções de uso. A partir disso, espera-se que o sistema imprima um relatório da receita ao paciente ou permita sua visualização via internet.

![image](https://user-images.githubusercontent.com/103516597/208522516-b06bb6c3-c6ad-4bbf-8c86-f0d35db9a1d2.png)

# Parte 2: Os Segredos do Hospital

Para cada internação, são anotadas a data de entrada, a data prevista de alta e a data efetiva de alta, além da descrição textual dos procedimentos a serem realizados. 

As internações precisam ser vinculadas a quartos, com a numeração e o tipo. 

Cada tipo de quarto tem sua descrição e o seu valor diário (a princípio, o hospital trabalha com apartamentos, quartos duplos e enfermaria).

Também é necessário controlar quais profissionais de enfermaria estarão responsáveis por acompanhar o paciente durante sua internação. Para cada enfermeiro(a), é necessário nome, CPF e registro no conselho de enfermagem (CRE).

A internação, obviamente, é vinculada a um paciente – que pode se internar mais de uma vez no hospital – e a um único médico responsável.

![image](https://user-images.githubusercontent.com/103516597/208527956-c3873229-1c1c-43fc-bd02-83dfd2e1bf38.png)

# Parte 3

Abastecer o banco com informações fictícias.

# Cargo

![image](https://user-images.githubusercontent.com/103516597/208771692-b2697066-bd49-44ec-a174-51b8ecc5920c.png)


# Consultas
![image](https://user-images.githubusercontent.com/103516597/208771646-6288b610-e8b9-4b49-855a-0d8d3044dc7d.png)


# Convenio
![image](https://user-images.githubusercontent.com/103516597/208771884-24e9cb32-2946-4d4f-a00f-12003e594582.png)


# Endereço
![image](https://user-images.githubusercontent.com/103516597/208771910-4b0ce0d3-76b6-40ed-89d8-ff59ff7a66a0.png)


# Enfermeiro
![image](https://user-images.githubusercontent.com/103516597/208771929-8f35a5e1-3ed9-41b2-9730-ad5fee78ccac.png)


# Especialidade
![image](https://user-images.githubusercontent.com/103516597/208771945-9c749dd5-9e3f-4b5e-a693-12bd09673b85.png)


# Internação
![image](https://user-images.githubusercontent.com/103516597/208771964-bd7e96a6-0b80-4609-9d06-2936aaa1eeb7.png)


# Médico
![image](https://user-images.githubusercontent.com/103516597/208771994-21cac6ff-78d8-4f59-8bed-f5568b3741af.png)


# Paciente
![image](https://user-images.githubusercontent.com/103516597/208772023-456af260-7a16-4b80-8ac1-b5df31664a57.png)


# Quarto
![image](https://user-images.githubusercontent.com/103516597/208772046-27a3374b-e3cd-4f8a-a7b1-f9560b030344.png)


# Receita
![image](https://user-images.githubusercontent.com/103516597/208772083-e4421b5f-9825-4ff7-bf10-177077039f97.png)

# Parte 4

A Ordem do Alterar. 
Hummm... 
Não... Não acabou... 
Um banco de dados pode sofrer alterações ao longo da sua concepção e do seu desenvolvimento. Nesse momento devemos nos preparar para atualizar nossas estratégias. 
Mãos a Obra. 
Pensando no banco que já foi criado para o Projeto do Hospital, realize algumas alterações nas tabelas e nos dados usando comandos de atualização e exclusão:
Crie um script que adicione uma coluna “em_atividade” para os médicos, indicando se ele ainda está atuando no hospital ou não. 
Crie um script para atualizar ao menos dois médicos como inativos e os demais em atividade.

![image](https://user-images.githubusercontent.com/103516597/209404044-5d67e376-b96d-4025-8c77-c78922e95557.png)

# Parte 5

1. Todos os dados e o valor médio das consultas do ano de 2020 e das que foram feitas sob convênio.

![image](https://user-images.githubusercontent.com/103516597/209850099-12a6634f-5096-44de-b14a-608eabdb158d.png)

2. Todos os dados das internações que tiveram data de alta maior que a data prevista para a alta.

![image](https://user-images.githubusercontent.com/103516597/209850147-91ca142c-3986-457b-b6d8-cecbec5e1ac2.png)

3.Receituário completo da primeira consulta registrada com receituário associado.

![image](https://user-images.githubusercontent.com/103516597/209851130-412c44ca-1711-4eba-b909-1cbb4af5bdad.png)

4. Todos os dados da consulta de maior valor e também da de menor valor (ambas as consultas não foram realizadas sob convênio).

![image](https://user-images.githubusercontent.com/103516597/209852728-150cabbb-e883-4a25-a7a8-ea568140b553.png)

5. Data e número de quarto de internações em quartos do tipo “apartamento”.

![image](https://user-images.githubusercontent.com/103516597/209861890-9450fd31-1662-4773-ac69-51709488179d.png)

6. Nome do paciente, data da consulta e especialidade de todas as consultas em que os pacientes eram maiores de 18 anos na data da consulta.

