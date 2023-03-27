# chamadasAssíncronas

Respostas:
1 - o Codigo executaria antes trazendo a mensagem de dados carregados mesmo que ainda não tenha sido finalizada a intrução a cima.
2 - No contexto WEB com JavaScript puro isso não é possivel chamar de forma assincrona um método apenas colocando um await antes da funcão que está sendo chamada se ela não estiver envolvida em uma funcão assíncrona.
3 - Para resolver apenas foi adicionado a mensagem após ó método retornar os dados vindos da API dentro da minha aplicação atraves do metodo .then() e com isso garantimos que só vamos realizar alguma ação após finalizar determinada chamada assíncrona.
