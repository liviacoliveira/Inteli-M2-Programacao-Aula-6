# Inteli-M2-Programacao-Aula-6


1. Papel de cada camada da arquitetura MVC:
Model: cuida dos dados e do acesso ao banco.

View: mostra as informações na tela.

Controller: recebe as requisições, chama o Model e envia dados para a View.

2. Como Model, Controller e View interagem entre si?
O Controller recebe a requisição, consulta ou envia dados ao Model e repassa esses dados para a View exibir.

3. Como ocorre o envio e recebimento de dados em JSON?
O backend usa res.json() para enviar e req.body (com express.json() habilitado) para receber JSON nas requisições.
