Teste end2end e backstopJS

Executar o webdrive.io

    1 - clone o repositório através https://github.com/Caio-Cesar-Moraes/webdriveio.git
    2 - execute o comando npm i ou npm install para instalar as dependecias
    3 - execute o comando npm run test para executar os testes

    OBS: Dúvidas olhar o package.json

Executar o backstopJS

    1 - configurar o arquivo backstop.json com a url que quer que seja executado a validação do layout de tela
    2 - executar o comando npm run test:front ou backstop test para verificar o layout indicado na url
    3 - executar o comando npm run approver:front ou backstop approve para aprovar as mudanças
    4 - após aprovar a mudança, depois que houver modificações no layout é só executar o comando npm run test:front ou backstop test validar os testes no layout
