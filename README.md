Link Youtube -

Link Tinkercad - 

ECOGRID CEV — Sistema de carregamento de veículos elétricos

Sobre o projeto

O ECOGRID CEV simula uma estação de recarga para carros elétricos que pode usar a energia da rede elétrica e, quando selecionado, também a energia solar armazenada em uma bateria extra. O projeto tem duas partes que se complementam: um circuito demonstrativo montado no Tinkercad e uma interface web para representar a experiência de uso da estação.

O Tinkercad permite simular os componentes eletrônicos, mas não criar o site. Por isso, a interface foi desenvolvida separadamente. Mesmo em ambientes diferentes, o site e o circuito seguem a mesma ideia: escolher como a recarga será feita, iniciar o carregamento do carro e indicar o estado do sistema.

Como funciona o site
A pessoa começa escolhendo o veículo e informa quanto deseja carregar, seja por uma quantidade de energia ou por um período. Antes de iniciar, pode conferir uma estimativa de duração e custo. Depois de confirmar, a sessão começa e a tela acompanha o tempo e a energia entregue. Ao terminar ou interromper a recarga, a sessão fica disponível no histórico.

Há duas opções de carregamento:

- Básico: utiliza somente a energia da rede elétrica.
- Sustentável: combina a energia da rede com a energia solar disponível na bateria extra. A contribuição solar reduz o valor estimado da sessão.

Assim, a pessoa pode escolher entre carregar apenas pela rede ou aproveitar a energia solar armazenada para diminuir o custo.

Como funciona o protótipo
No circuito do Tinkercad, o Arduino recebe as escolhas feitas pelos botões e controla os relés, que representam a seleção do fluxo de energia. Ao iniciar a recarga do carro, a bateria extra deixa de receber carga e pode apoiar o carregamento do veículo. A escolha do modo indica se o carro será alimentado somente pela rede ou pela rede com apoio da energia solar.

O painel solar representa a geração de energia para a bateria extra. O display LCD informa o estado selecionado, como carro sem carregamento, recarga pela rede ou recarga com apoio solar. LEDs e relés ajudam a visualizar o funcionamento do circuito.

Objetivo
Demonstrar, de forma simples, como uma estação pode oferecer diferentes opções de recarga e aproveitar energia solar armazenada para apoiar o carregamento de um carro elétrico.
