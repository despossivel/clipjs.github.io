#### [Clip CLI](https://www.clipjs.com)
##### Agrupador e Gereciador de Console 

##### Inicie toda familia React, Sass ou Docker e qualquer outro serviço necessário no ambiente de desenvolvimento do seu projeto.

Exemplo: Em todo projeto existe a necessidade de "subir" serviços de ferramentas como reactjs, sass, Phonegap serve, Nodejs do lado servidor e varios outros serviços.
E sempre que preciso iniciar o ambiente de desenvolvimento o desenvolvedor tem a tarefa de subir serviço por serviço de forma manual, sendo assim o Projeto Clip nasceu, com o objetivo de automatizar e organizar serviços.

##### Instale com NPM
npm i -g clip-cli

##### COMO USAR:
##### Para criar um novo ambiente ou adicionar comandos a um ambiente já criado:

clip config <nome ambiente> <diretorio projeto> <comando do serviço>

##### Exemplo: 
clip config AppMobile /home/Documentos/clients/com.stream.app npm start


##### Para iniciar um ambiente:
clip run <nome ambiente> 

##### Exemplo:
clip run AppMobile


##### Para listar todos os ambientes e seus comandos
clip list

#### Para editar um ambiente
clip edit <nome ambiente>

#### Para remover um ambiente
clip remove <nome ambiente>



###### [@despossivel](https://instagram.com/despossivel) 