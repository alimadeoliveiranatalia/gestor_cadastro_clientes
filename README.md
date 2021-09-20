# gestor_cadastro_clientes<br>
 Material da aula disponível em: https://youtu.be/IQBHvQ8gFW0
 <h1>Sistema de Gestão Cadastro de Clientes</h1>
 <h3>Objetivos do Projeto</h3>
 <h5>Manter Cadastro de Cliente</h5>
 <br>
 O Manter Cadastro de Cliente tem como objetivo possibilitar a inserção, alteração e exclusão de clientes no sistema, onde posteriormente serão utilizados durante os processos de que necessitem de informações de clientes.
 <br>
 <h5>Requisitos Funcionais - RF</h5>
 <br>
 RF1 – O sistema deve permitir o registro de dados de cliente físico, sendo eles:  nome, CPF, RG (número), data de nascimento<br>
RF2 - O Sistema deve permitir o registro de dados de cliente jurídico, sendo eles: Razão Social, nome fantasia, CNPJ, inscrição estadual, inscrição municipal, data de abertura da empresa.<br>
RF3 - O sistema deve permitir o registro de contatos do cliente, sendo telefones, celulares, redes( facebook, telegram, linkedin e outros) , telefone.<br>
RF4 - O Sistema deve permitir o registro de endereços do cliente, sendo:  (logradouro, nome, número, complemento, bairro, cidade, estado, CEP, zona, latitude e longitude). <br>
RF5 - O Sistema deve permitir o registro de dados de: data de cadastro do cliente físico ou jurídico,  situação cadastral no sistema com ativo ou inativo.<br>
RF6 - O sistema deve permitir o registro do status de ativo ou inativo de um cliente no sistema<br>
<br>
<h5>Regra de Negócio</h5><br>
RN1 - O Sistema não deve permitir duplicidade de registro de pessoa física ou jurídica. Registrando apenas um ‘id’ único para cada cliente inserido no sistema.<br>
RN2 -  O Nome do Cliente deve ser de preenchimento obrigatório e com mínimo de 3 caracteres e no máximo 70 caracteres.<br>
RN3 - o CPF e ou CNPJ do Cliente deve ser validado, e não permitir inclusão de CPF ou CNPJ inválidos.<br>
	RN4 - O Cliente não poderá ser excluído por afetar o conjunto de dados produzidos na relação com o mesmo. Por este motivo a ação de exclusão de cliente é representada por um status de excluído e a não exibição deste cadastro com este status na listagem, consulta de chamadas do cliente.<br>
	RN5 - Para pessoa física os dados obrigatórios são: nome de cliente (Nome Pessoal), CPF, data de nascimento, número de identidade (RG).<br>
	RN6 - Para pessoa jurídica os dados obrigatórios são nome de cliente( Razão Social, nome fantasia, CNPJ , data de abertura ).<br>
	RN7 - É obrigatório o cadastro de no mínimo um endereço para um cliente.<br>
	RN8 - É obrigatório o cadastro de no mínimo um registro de contato, podendo ser um número de telefone ou celular de contato para pessoa física.<br>
         	RN9 - É obrigatório o cadastro de no mínimo um telefone para contato e o e-mail da empresa.<br>
	RN10 - Para registro de endereço é obrigatório os dados de endereço, número do endereço, bairro , zona, cidade e estado.<br>
	RN11 - Somente após inserção do cliente no sistema, o usuário poderá registrar outros endereços.<br>
	RN12 - O Sistema deve disponibilizar as seguinte formas de consultar os cliente:<br>
		Consultar por dados pessoais e documentos:<br>
		- Para físico ( nome, cpf e rg data de cadastro)<br>
		- Para Juridico( Nome , nome fantasia e cnpj)<br>
		Consultar por dados de contato<br>
		- Telefones, celular, e-mail<br>
		Consultar por dados de endereço<br>
		- endereço, bairro, zona, cep<br>
	RN13 - O Sistema após inserir ou alterar um registro de cliente, deve mostrar uma tela de resumo com os dados do cliente.<br>
	RN14 - O Sistema após uma consulta deve listar os clientes e permitir ao usuário com autorização  alterar, visualizar ou excluir a partir do retorno desta lista.<br>


