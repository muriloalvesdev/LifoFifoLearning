Desmistificando LIFO (Last In, First Out) e FIFO (First In, First Out)
- 
LIFO (Last In, First Out) é um algoritmo de pilha, onde o último elemento adicionado é o primeiro a ser removido.

FIFO (First In, First Out) é um algoritmo de fila, onde o primeiro elemento adicionado é o primeiro a ser removido.

Em Java, podemos implementar uma pilha LIFO utilizando a classe `Stack`, enquanto que para implementar uma fila FIFO podemos utilizar a classe `LinkedList` ou `ArrayDeque`.

LIFO (Last In, First Out)
-
LIFO é uma _estrutura de dados_ que segue a ordem `"último a entrar, primeiro a sair"`. 
Isso significa que o último elemento adicionado à estrutura é o primeiro a ser removido. 
Uma classe comum que implementa LIFO é a pilha (stack).

Exemplo de implementação de uma pilha LIFO em Java:

<img height="470" src="https://lh3.googleusercontent.com/d3CAFKmTG38nuvUng5kfXYMPxAn-K6xGM8uMo6wR2u-FtvIZ4Xowth4967B3hW-T5LrtSOx30f6zKH8Nd_j5ZbAJgdIeWHqDsQGRK8L3xsv5jQx1narUbQ67A8mcocJO883vwmLx8IW7eU1mLaFGzSE-9WT4m6QpAM3AopAUDsgwlaRStIbb1sLpMpJZtHGXKW4yth8_hWA15qN_VCr5cnmOsqMeogbv4-ZZLQIORjWZeT2s-iYacYLejPOs90NmcprpHzlQMq2143z_l6URUuoiZGi18DF_LnuCYCai7q8e5OaLUBAkxhKoa50A8D9M2zRZBjYhj9gVsG9Qtzm2gxXVT0mzM65ZeicEXckexuFaMilKfl9xwNaFnfTpsuS4irH7AwlVVLpAbc9pNfHG0xZ_6xLug-VYRPT33B6o-izf-mEP9JeDPCkf92qGu3iGcYjUasqTOLSq5SdoVUfTpAZGpL9cGvq-KkqnIG5L1YyEpzaOLRR5W52O6ZXV-oneAStdkg6h7Ll4qCrkAsl1rVFd3ZIj2bu8Q7VCxiHguolNulq07JNxUzdWBfXk9L_qXG6oQYXErJHbMn-IaLiX4k8WfnXJRxIob3C7jUTqzt5bAXFO_KZTetzloNbaU_y5-tbpaA76quDlea-brVn0J2Yi1uqjQlMcOjnl-WTEGGIx9G0dCIMpcg1EC9L_w3Q_1XWgJEiAcV7lQ4eoDnwVgHhRkK5vgW-HBf5srO-WaRlZ1umiq0eBpRG3GMZh93009SN8TxOABRVY2EZ3-5Pb7EM6uO58Zg27uxC7aMSkBkfHkpC2R06qjACX8SbLKdgstWgeBGho1G78VPx3EN7p6IuRnbnZx58CxQdw9D_Uew_IlSd7kRzg6aSxb62iUt7eIxOQwHd4a67PGdeu_nRV2ONIbuB_SqT3z85R4ok9hoM-jb0Lt5zqmdvh-_LJ40tj37d5vyLkKtX5H0Oyr62fvQo8se9kiA0NzBk_6GYhSQOJjLwaWV0ttQ=w1007-h887-no?authuser=2)">

____________________________________________________________________________________________________________

FIFO (First In, First Out) é uma estrutura de dados que segue a ordem "primeiro a entrar, primeiro a sair". Isso significa que o primeiro elemento adicionado à estrutura é o primeiro a ser removido. Uma classe comum que implementa FIFO é a fila (queue).

Exemplo de implementação de uma fila FIFO em Java:

<img height="470" src="https://lh3.googleusercontent.com/a24oi6wlGvbmWPiX4lt_4NJqrt9rzri7McHAxImQut_7JnUnPOAEYh6tE1lDM_-pjuM0LItsppD5ZJCwcWaBG9UApy6X4lVgz1NzZjl0-eqZLWUhnKW_TvM3XBxCiHNYnPehFZOx3tbB1aucrBfQLBQM-C0Km5w8xUZLFxs74ula4Q_pgfxWo7OTkR9hIGhzBbKeeRJbAaVDpNS5gMpYGQ-HAx5-cwWdfbGTDbkeHKy1Foz1nlrhae7SO7z3VqQwt07JCAS_vR8JqjgLALPWZA8nj3JMHxphsoZlNn34faUF1f5aNIg-kJhBTn4gocBa_0iVZKNDzpEGtF8lcH0r8TSC35Kgq5_V33g_anK_62qJld9LUDpy6Qq2k1pOjAHPRS80Y9zeUKZtSHOHGiihvBtQ-4NY5s9oQIFIZL5hWpDbLHQpz5CgZu-lZshU9mTK9m3BjfamVhkBweKNdLWWF_lwa4O_d4pVl8JqL8gODsHj6RuvIMGsjdEktEdhn63eI1Yga8cM8o6E_HH0Vcrz4PlhCWFgkrYgrk_ocuKGdJ-UXdu09d1PldsdOBsRQfyPbYU4zhfCifrU15-Dwe6fgbLsfyOmzdzB8nOGrzlCID2fTWsfz_ueIsJKzfph0A0m7Q2Wf1V_TWtp3uB_GkLpZ_muGU1smrPQAit3mD49FQD3xrEyGSTY49_pU7-LLZ14V5Q9MRTdAHwibmNUNOky7lwbrekarn2GqHiS3P8SBC28dL7xQeeZ6odKzi02Ua7e_5D6bkKuO5DDBnPRGld1yweUczoZARXRvvzuiq1yvoVDBGX8oWODke9J6a3tz5_4HYKCB3sZkQw4uRJxJDLJxmetlmql3V0nAeYlVMFR4ktJVpTeYWdUkXbfD6wKR9x2gOlKx0-18Bhki8ESOg-VIunTIy8JDDJh5uqARghWsglQZ4lmzi2a_QVVRHpusANw47FF-j9R04sshtHU-VAZYxKJjAJXBRz9jc3ABcgid_tvS6QKzfF9hg=w1009-h887-no?authuser=2">

____________________________________________________________________________________________________________

Pontos positivos
-

LIFO (Last In, First Out)
-
Lifo tem a vantagem de ser simples de implementar e geralmente(não é uma regra) requer pouca memória. 
É comumente usado em situações onde a ordem de remoção dos elementos não é importante, como por exemplo, desfazer operações em um editor de texto.

FIFO (First In, First Out)
-
Fifo tem a vantagem de manter a ordem de entrada dos elementos, o que pode ser importante em situações onde é necessário processar os elementos na ordem em que foram adicionados, como por exemplo, processamento de transações financeiras ou impressão de documentos. Além disso, FIFO é usado comumente para garantir a ordenação dos elementos.

E também, ambos tem a vantagem de ser estruturas de dados lineares, o que facilita a implementação e garante uma boa performance.

____________________________________________________________________________________________________________

Pontos negativos
-

LIFO (Last In, First Out) 
-
- LIFO pode ser ineficiente em situações onde é necessário processar os elementos na ordem inversa em que foram adicionados, pois isso requer que todos os elementos sejam removidos e adicionados novamente na ordem desejada.

FIFO (First In, First Out)
-
- FIFO pode ser ineficiente em situações onde é necessário acessar elementos no meio da fila, pois isso requer que todos os elementos anteriores sejam removidos e também, FIFO pode requerer mais memória do que LIFO para armazenar os elementos devido à necessidade de manter a ordem de entrada.

E ambos possuem limitações de tamanho, onde se a estrutura de dados é limitada e a adição de novos elementos ultrapassa esse limite, é necessário remover elementos antigos antes de adicionar novos, isso pode causar perda de informações importantes.

____________________________________________________________________________________________________________

Alguns exemplos de como FIFO e LIFO são usados em situações cotidianas:
-

Exemplo de LIFO:
-
- Histórico de navegação do seu navegador web, onde ao clicar no botão "voltar" você é levado para a página anterior, mas ao clicar no botão "avancar" você volta para a página seguinte. Isso ocorre porque o histórico de navegação é implementado como uma pilha LIFO, onde a última página visitada é a primeira a ser removida quando se clica no botão "voltar".

- A ferramenta desfazer (undo) em um editor de texto, onde a última ação desfeita é a primeira a ser refeita. Isso ocorre porque o histórico de ações é implementado como uma pilha LIFO, onde a última ação realizada é a primeira a ser removida quando se usa a ferramenta desfazer.

Exemplo de FIFO:
-
- A impressora que processa documentos na ordem em que são enviados para impressão. Isso ocorre porque a fila de impressão é implementada como uma estrutura FIFO, onde o primeiro documento enviado é o primeiro a ser impresso.

- A fila de atendimento de um banco, onde as pessoas são atendidas na ordem em que chegaram. Isso ocorre porque a fila é implementada como uma estrutura FIFO, onde a primeira pessoa a chegar é a primeira a ser atendida.
