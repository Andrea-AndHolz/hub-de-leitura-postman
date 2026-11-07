Gerado dois arquivos de testes, para evitar que alguns testes não interfiram nos demais.
Primeiro arquivo possui testes referente ao usuario comum e o segundo arquivo para usuario administrador. 
Arquivo de usuario possui variaveis utilizando random e outros testes utilizando variaveis fixas para gerar um ciclo completo.
Para que seja possivel mais teste deste ciclo, deve ser alterado email da variavel global, para cadastro de um novo usuario.
Para testes de atualização do usuario, deve ser alterado o codigo de usuario da url (que corresponda ao usuario logado anteriormente) 
e o email localizado no body do teste. 
Referente ao segundo arquivo, em Gestão,  para deletar o usuario tammbem deve ser alterado o id do usuario existente na url.
No arquivo de reserva, em cancelamento tambem deve haver alteração do id especificado na url.
Para criar reserva deve alterar id no body do teste.
