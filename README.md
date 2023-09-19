# Node.js-
Primeiro é necessário ativar o nodejs colocando o seguinte código (source ./nodejs-env/bin/activate), logo após adicione (sudo nano index.js),
em seguida copie o código base passado pelo professor:

(var http = require('http');
http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Gabriela Boarati Macedo  19/09/2023');
}).listen(8016);

Abra o terminal da máquina virtual e edite de acordo com o que foi pedido.

Para ver se realmente funcionou, abra um novo terminal e digite o código (ip addr) para saber seu ip do usuário, depois abra o firefox e digite seu ip 
e sua porta de entrada edita de acordo com o que foi passado:

EX: 192.168.40.43:sua porta de entrada - ( }).listen(8016); )
EX: 192.168.40.43:8016
