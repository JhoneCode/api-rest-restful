- Uma API é uma prestadora de serviços que recebe uma requisição do client e devolve um recurso do banco ou back end, como na metáfora do restaurante.

- Uma API RESTful é aquele que obedece aos 6 requisitos (constraints) REST, que são:

- _Client-server_: Separação do cliente e do armazenamento de dados (servidor), dessa forma, poderemos ter uma portabilidade do nosso sistema, usando o React para WEB e React Native para o smartphone, por exemplo.

- _Stateless_: Cada requisição que o cliente faz para o servidor, deverá conter todas as informações necessárias para o servidor entender e responder (RESPONSE) a requisição (REQUEST). Exemplo: A sessão do usuário deverá ser enviada em todas as requisições, para saber se aquele usuário está autenticado e apto a usar os serviços, e o servidor não pode lembrar que o cliente foi autenticado na requisição anterior. nos nossos cursos, temos por padrão usar tokens para as comunicações.

- _Cacheable_: As respostas para uma requisição, deverão ser explícitas ao dizer se aquela requisição, pode ou não ser armazenada em cache pelo cliente.

- _Layered System_: O cliente acessa a um endpoint, sem precisar saber da complexidade, de quais passos estão sendo necessários para o servidor responder a requisição, ou quais outras camadas o servidor estará lidando, para que a requisição seja respondida.Exemplo prático na URL a seguir:
https://graph.facebook.com/youtube onde youtube é o endpoint e o restante do endereço seria a URI da API.

- _Code on demand (optional)_: Dar a possibilidade da nossa aplicação pegar códigos, como o javascript, por exemplo, e executar no cliente;
