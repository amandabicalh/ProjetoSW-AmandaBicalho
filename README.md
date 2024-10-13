# ProjetoSW-AmandaBicalho

## Resenha do artigo “Big Ball of Mud”

O artigo “Big Ball of Mud”, de Brian Foote e Joseph Yoder, fala sobre um problema muito comum no desenvolvimento de software: sistemas extremamente desorganizados e confusos, chamados de Bola de Lama Gigante. Esse tipo de sistema ocorre quando o código é escrito sem planejamento, resultando em algo difícil de entender e manter. Mesmo sendo considerada uma má prática, essa abordagem é muito usada porque permite que desenvolvedores atendam às demandas rapidamente. 

Os autores explicam que, muitas vezes, a pressão para entregar o sistema no prazo faz com que se crie código desleixado, mas funcional. Isso acontece, grande parte das vezes, quando não há tempo suficiente para pensar em uma solução a longo prazo. A ideia a princípio é fazer funcionar, mesmo que o código acabe se tornando difícil de modificar no futuro. Exemplos de problemas são o Throwaway Code, que começa como um código temporário e acaba ficando no sistema, e o Piecemeal Growth, que é o crescimento desorganizado do sistema ao longo do tempo. 

Embora sistemas assim funcionem no curto prazo, eles eventualmente se tornam difíceis de mexer ou corrigir. Os autores sugerem que, em muitos casos, a única solução é reconstruir o sistema do zero ou fazer uma grande reformulação no código. 

O artigo mostra que, apesar de ser uma solução rápida, construir sistemas dessa forma pode trazer muitos problemas no futuro. No entanto, os autores entendem que nem sempre é possível evitar, especialmente em projetos com prazos apertados. Eles defendem a importância de equilibrar a necessidade de entregar o projeto rápido com o planejamento de uma estrutura de código mais organizada e fácil de manter. 

Em resumo, o artigo explica por que sistemas desorganizados são tão comuns no desenvolvimento de software e propõe algumas formas de melhorar essa situação, incentivando um equilíbrio entre soluções rápidas e um planejamento mais cuidadoso. 


## Resenha do artigo "Technology Radar" 

O artigo Technology Radar, da Thoughtworks traz uma série de inovações e tendências tecnológicas que estão influenciando o desenvolvimento de software. Um dos principais destaques é a técnica de Geração Aumentada por Recuperação (RAG), que melhora a precisão dos resultados de modelos de linguagem como os LLMs. Com a RAG, informações relevantes são recuperadas de documentos e combinadas com o prompt enviado ao modelo, resultando em respostas mais precisas e reduzindo erros como respostas fora de contexto. 

  

Outro ponto interessante é a Geração Automática de Descritores de Entidade no Backstage. Esse processo automatiza a criação de descritores que mapeiam recursos e componentes de um sistema, ajudando a reduzir erros manuais e agilizando o trabalho das equipes de desenvolvimento. 

  

A combinação de PLNs tradicionais com LLMs também foi discutida, ressaltando que em muitos casos, métodos mais simples de Processamento de Linguagem Natural (PLN) são mais econômicos e eficientes para tarefas como classificação de tópicos e sumarização, enquanto os LLMs podem ser utilizados quando necessário. 

  

A Conformidade Contínua é outra prática destacada, que automatiza auditorias de segurança e conformidade com regulamentações ao longo do processo de desenvolvimento, o que é especialmente útil em setores que exigem alta segurança, como a indústria de veículos autônomos. 

  

Essas tendências mostram como o desenvolvimento de software está cada vez mais focado em automação, segurança e eficiência, usando o poder das novas tecnologias para melhorar a qualidade dos projetos. 

## Resenha do artigo: Microsservices
O artigo sobre Microservices fala sobre uma nova maneira de desenvolver softwares que tem ganhado bastante popularidade. A ideia principal é dividir uma aplicação grande em pequenos serviços independentes, chamados de microserviços. Cada um desses serviços cuida de uma parte específica do sistema e pode ser desenvolvido e atualizado separadamente. Isso é diferente da abordagem monolítica, onde toda a aplicação é um único bloco que precisa ser alterado de uma vez só, mesmo para mudanças pequenas. 

  

No decorrer do texto, o autor explica que uma das grandes vantagens dos microserviços é que as equipes podem trabalhar de forma independente. Elas podem escolher as melhores ferramentas e linguagens para cada serviço e fazer atualizações sem precisar mexer em todo o sistema. Além disso, ele destaca a importância da automação, que torna mais fácil e rápido o processo de implantação dos serviços. 

  

Outro ponto interessante é que, em vez de dividir as equipes por função técnica, como front-end e back-end, a arquitetura de microserviços organiza os times em torno das necessidades do negócio. Ou seja, cada equipe foca em resolver problemas específicos e entregar valor diretamente ao cliente, o que acelera o desenvolvimento e a entrega de novas funcionalidades. 

  

Por outro lado, o autor também ressalta alguns desafios dessa abordagem. Gerenciar muitos microserviços pode ser complexo e exige um bom sistema de monitoramento para garantir que tudo funcione bem. Além disso, é necessário que o sistema seja capaz de lidar com falhas sem derrubar toda a aplicação. 

  

No final, o autor conclui que, apesar das dificuldades, a arquitetura de microserviços é uma ótima escolha para empresas que precisam de flexibilidade e que tenham sistemas grandes. Empresas como Netflix e Amazon já adotaram esse modelo com sucesso, mas ele requer uma equipe capacitada para lidar com a complexidade. 

## Resenha Capítulos 6 e 7 do livro “Engenharia de Software Moderna” 

No capítulo 6 do livro Engenharia de Software Moderna, são apresentados os padrões de projeto, que são soluções já conhecidas e testadas para problemas recorrentes no desenvolvimento de software. Esses padrões foram inspirados em ideias da arquitetura tradicional e adaptados para o mundo da programação. Lá, você vai encontrar explicações sobre padrões como Fábrica, Singleton, Adaptador, entre outros. 

A principal função desses padrões é oferecer uma forma mais eficiente e organizada de resolver problemas que surgem com frequência. Porém, o capítulo também alerta que, apesar de serem muito úteis, não é uma boa ideia aplicá-los em qualquer situação. Usar padrões de forma exagerada pode acabar complicando o código ao invés de simplificá-lo, o que vai contra o objetivo inicial. 

No Capítulo 7, é falado sobre a arquitetura de software, que trata da organização geral dos sistemas, com foco nas grandes estruturas em vez dos detalhes menores como classes e funções. Aqui, a preocupação está em como dividir o sistema em partes maiores, como módulos e camadas, para garantir que ele seja fácil de entender, modificar e expandir ao longo do tempo.  

O capítulo apresenta diferentes formas de estruturar sistemas. Um exemplo é o padrão MVC , que separa a interface do usuário, a lógica de controle e os dados, o que facilita o desenvolvimento de sistemas modulares e mais fáceis de modificar. Outro exemplo é  a Arquitetura em Camadas, bastante popular em empresas, que organiza o sistema em diferentes níveis de responsabilidade, ajudando a manter o código mais organizado e permitindo atualizações sem grandes complicações.  

Por último, o capítulo aborda os Microsserviços onde cada parte do sistema funciona de forma autônoma. Essa separação em pequenos serviços independentes facilita o escalonamento, a manutenção e a adição de novas funcionalidades sem interferir no restante do sistema, tornando-o mais flexível e preparado para crescer. 

Esses dois capítulos mostram como padrões de projeto e arquitetura são como as fundações de uma casa: eles garantem que o software seja sólido e que possa crescer sem desmoronar. Os padrões de projeto são como truques que você pode usar no dia a dia para resolver problemas comuns de forma rápida e eficiente, sem reinventar a roda toda vez. Já a arquitetura de software é o plano mestre, ajudando a organizar tudo de uma maneira que faz sentido e que facilita mudanças no futuro, evitando o caos. 
Com esses dois conceitos trabalhando juntos, você consegue construir sistemas que não só funcionam bem hoje, mas que também serão fáceis de atualizar e manter quando novos desafios aparecerem. Em vez de acabar com um software bagunçado e difícil de mexer, você terá algo organizado e preparado para crescer de forma tranquila. 

 

 
