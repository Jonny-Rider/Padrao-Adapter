# Padrao-Adapter

Um padrão de adapter também é conhecido como padrão Wrapper. O design do adaptador é muito útil para a integração do sistema quando alguns outros componentes existentes precisam ser adotados pelo sistema existente sem modificações no código fonte.

Uma interação típica acontece assim:

![alt text](https://howtodoinjava.com/wp-content/uploads/2014/05/adapter_sequence.png)

Participantes do Adapter Design Pattern

As classes e / ou objetos que participam desse padrão estão listados a seguir:

-Target (BufferedReader): Define a interface específica do aplicativo que o Cliente usa diretamente.

-Adapter (InputStreamReader): Adapta a interface Adaptee à interface de destino. É o intermediário.

-Adaptee (System.in): Define uma interface incompatível existente que precisa ser adaptada antes de usar no aplicativo.

-Client: É o seu aplicativo que funciona com a interface Target.

Onde usar o Adapter Design Pattern?

O principal uso desse padrão é quando uma classe que você precisa usar não atende aos requisitos de uma interface. por exemplo. Se você deseja ler a entrada do sistema por meio do prompt de comando em java.

No arquivo deste repositório, tem o código de exemplo implementando o padrão em JAVA.

