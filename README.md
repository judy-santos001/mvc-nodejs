Entendendo  o MVC 
 é um padrão de arquitetura de software que divide a aplicação em três camadas: Model, View e Controller.
 M( model) : é onde está o banco de dados da aplicaação
 V (view) :responsável pela interação com o usuário. Nesta camada são apresentados os dados ao usuário.
 Os dados podem ser entregues em vários formatos, dependendo do que for preciso, como páginas HTML, arquivos XML, documentos, vídeos, fotos, músicas etc.
 C (controller) : é responsável por lidar com as requisições do usuário. Ela gerencia as ações realizadas, fala qual Model e qual View utilizar para que a ação seja completada.
 Ela gerencia as ações realizadas, fala qual Model e qual View utilizar para que a ação seja completada.


como funciona ?
o usuario faz um pesquisa no youtube por exemplo,
ai vai verificar o o que e o usuario ao controle,
ai o controle verifics o que o usuario pediu no model e 
devolve o q o usuario o q ele pediu 


package.json possui vários metadados relevantes para o projeto. Este arquivo é utilizado para fornecer informações que permitem identificar o projeto e 
trabalhar com suas dependências.

O arquivo app.js é o arquivo principal do projeto. Primeiramente incluímos as dependências do projeto. Depois configuramos o módulo ejs, que é para trabalharmos com as views. Após isso configuramos o módulo consign, que faz o carregamento automático dos scripts do nosso projeto. E por fim configuramos o servidor web do framework express para escutar requisições http na porta 3000

O arquivo data/noticias.json é o JSON que estamos utilizando como base de dados do projeto, para armazenar as notícias que serão exibidas.

Como o código é dividido em partes distintas, torna- se fácil adicionar novas funcionalidades e alterar características antigas. O código também fica mais fácil de ser compreendido por outros desenvolvedores.

dependencias :
 
    "consign":, - O Consign pode ser usado para carregar automaticamente modelos, rotas, esquemas, configurações, controladores, mapas de objetos... etc..
    "ejs": 
    "express": ,
    "fs": 