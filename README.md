# Calculdaora Online
 

   Este projeto é uma aplicação de serviço web (API) que fornece quatro operações matemáticas básicas: soma, subtração, multiplicação e divisão. A API recebe os números de entrada através de parâmetros de consulta (query parameters) em uma solicitação HTTP.

   ![image](https://github.com/joaodoprado/calculdaora-online/assets/129133080/b4488b25-bb1f-4934-b6a2-f8cccea838bb)



   Cada operação (soma, subtração, multiplicação e divisão) é tratada por uma função diferente. Primeiro, verifica se os números de entrada são válidos (ou seja, se são números). Se os números forem válidos, a função realiza a operação correspondente e envia o resultado como resposta HTTP. Caso contrário, se os números não forem válidos, a API retorna uma mensagem de erro informando que os números são inválidos.

   ![image](https://github.com/joaodoprado/calculdaora-online/assets/129133080/d9ff9b07-e808-4516-a887-a8d24598c7d2)
   ![image](https://github.com/joaodoprado/calculdaora-online/assets/129133080/57826526-57cf-4336-a931-2467e2377a21)

   
   Para executar este projeto, é necessário clonar o repositório em sua máquina e instalar as bibliotecas ou dependências utilizadas. Para fazer isso, utilize o comando npm install no terminal.

   ![image](https://github.com/joaodoprado/calculdaora-online/assets/129133080/38746f06-9a7b-4538-b09a-ae8ac96cdb13)


   Após isso será necessário iniciar o servidor através do comando node ./src/index.js.

   ![image](https://github.com/joaodoprado/calculdaora-online/assets/129133080/f1f47b51-2480-45d8-9dc6-d6e973e3ae3d)


   Para testar a API, é altamente recomendável que você utilize ferramentas como Insomnia, Postman, Thunder, etc. Ao fazer isso, forneça os parâmetros de consulta na URL conforme solicitado, utilizando o método GET na porta 3000, como foi definido no arquivo index.js do projeto.
   
   ![image](https://github.com/joaodoprado/calculdaora-online/assets/129133080/caa3e8f7-694a-476e-bc44-cdcb91258292)

   ![image](https://github.com/joaodoprado/calculdaora-online/assets/129133080/67967897-2ab4-4292-96d5-f83599de284f)
