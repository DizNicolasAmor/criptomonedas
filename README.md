# CRIPTOMONEDAS


## 01. INTRODUCCIÓN

### ¿Qué es bitcoin?

- Es un protocolo, es decir, un conjunto de reglas que constituyen un sistema de comunicación. En este caso, uno descentralizado y que permite un intercambio de información p2p.
- Es la primera aplicación de este protocolo.
- También es la unidad monetaria que se utiliza en esta aplicación.
- Para cuestiones más técnicas, recomiendo buscar material de Andreas Antonopoulos.
- El objetivo de esta app es ser una moneda que compita con las fiat. La diferencia más importante es que los bitcoins no pueden ser emitidos, controlados o confiscados por ningún banco o gobierno.
- Fue creada con el objetivo de defender valores como la privacidad, la libertad de expresión y la propiedad privada. En cuanto al aspecto filosófico, pueden buscar información sobre los conceptos de cypherpunk y anarco-capitalismo. Esto permite entender el motivo de las características del protocolo (por ejemplo, la importancia de la descentralización de poder) y cómo funciona su sistema de incentivos.

### ¿Qué son las criptomonedas?

- Son otros proyectos que tomaron como referencia a bitcoin y cambiaron algunas características. 
- Cada uno es distinto: no todos son descentralizados, ni privados, ni open source, ni tienen las mismas propiedades monetarias.
- Sin embargo, podríamos decir que en general comparten las características de que son blockchains y para los usuarios finales comunes, la forma de interactuar con la red es bastante similar.

### ¿Cómo participar en la red de una crypto?

- Forma directa:
    - Ser un validador (crear un nodo).
    - Ser un usuario común (tener una wallet: recibir fondos y crear transacciones).

- Forma indirecta:
    - Usar un servicio que administre tu wallet por vos (exchanges, fintechs, pools que dicen que tienen nodos validadores). Es decir, cuando por ejemplo una persona dice que "tiene BTC en binance o en coinbase", en realidad los fondos los tiene dicha empresa.

### ¿Qué son las Private Keys y por qué son importantes?

- La PK es la parte más importante de una wallet: es una serie de caracteres que sirve para generar la public key (la dirección donde tu wallet puede recibir fondos, algo así como el CBU) y también para firmar/realizar transacciones.
- Quien tiene acceso a la PK tiene acceso a los fondos de esa wallet. Por eso,
"Not your keys not your coins"
- Si perdés la Private Key, perdés acceso a tus fondos y no hay forma de recuperarlos. 
- ¿Cómo se relaciona con las formas de participar que vimos en el punto anterior?

### ¿Cómo crear una wallet?

**software wallets - paper wallets - hardware wallets**

- Algunos softwares sirven de wallets para una blockchain en particular y otros, para varias.
- Algunos softwares permiten administrar tus private keys.
- Algunos softwares permiten importar wallets desde hardware.
- Estas combinaciones permiten, por ejemplo, tener la seguridad de una hardware wallet y poder administrar tus fondos en aplicaciones a través de software (como un exchange descentralizado).

### Comentarios finales

Hoy en día existen muchos proyectos de criptomonedas, cada uno con sus características. El software que te sirve para interactuar con una blockchain puede no servirte con otra... Hay que ver cada caso en particular. Qué haría yo para informarme de alguna crypto que me interese?

- Ir a su página web oficial (buscar en coinmarketcap o en coingecko).
- Leer el Whitepaper.
- Leer el Repositorio en Github.
- Comunicarse con la comunidad en las RRSS oficiales.
- Averiguar qué wallets tiene y cómo funcionan.

Y para participar en esa red?

- Crear una wallet de la cual tenga acceso a la private key.
- Confirmar que puedo recuperar esa wallet.

Tener en cuenta:

- Concepto de "Fee".
- Public key: para cada blockchain es distinta. Quienes comienzan usando exchanges centralizados pueden pensar que la misma dirección sirve para varias blockchains, pero no siempre es así.


## 02. BLOCKCHAINS CON Y SIN SMART CONTRACTS

- Sin SM
  - La red descentralizada sólo procesa y guarda datos de las transacciones en su moneda nativa.
  - Ejemplos: bitcoin, bitcoin cash, litecoin, dogecoin, monero.

- Con SM
  - La red descentralizada, además de eso, también almacena y ejecuta código, lo que se conoce como Smart Contracts. A partir de los SM, se puede crear otro tipo de criptomonedas que se llaman tokens.
  - Ejemplos de blockchains con SM: ethereum, bsc, polkadot, kusama, polygon, avalanche, cosmos, terra, próximamente cardano.
  - Ejemplos de tokens: DAI, USDC, USDT, UNI, CAKE, AAVE, MANA, COMP, WBTC.

### ¿En qué se diferencia una crypto nativa de un token?

Una criptomoneda nativa es aquella que está vinculada a una red blockchain a nivel fundacional y se usa para pagar a los nodos que validan las transacciones. Por ejemplo, en bitcoin es el BTC, en ethereum el ETH. Cada vez que se mina un bloque en bitcoin, el minero que generó ese bloque recibe BTC como recompensa.
Un token, por otro lado, es aquel creado dentro de una blockchain a partir de un smart contract. Por ejemplo, en ethereum, la crypto nativa que es el ETH, pero muchos tokens.

En general, en las redes que corren Smart Contracts, las fees de las transacciones se pagan en la moneda nativa. Por ejemplo, en ethereum, para enviar el token UNI de una wallet a otra, se necesita pagar una fee en ETH. Si el usuario no tiene ETH en su wallet, no puede enviar esos tokens.

### ¿Qué tipos de tokens existen?

- Stablecoins: buscan una paridad con el dólar u otra moneda estable.
- Derivados o activos sintéticos: buscan representar el precio de acciones, índices, metales, otras cryptos u otros activos financieros.
- NFT (tokens no fungibles): sirven para representar coleccionables, arte, registros de propiedad, servicios de identidad.
- Otras cryptos: vinculadas a servicios, por ejemplo dapps de juegos, de finanzas, de gobernanza de proyectos, de financiación de proyectos, de deportes, de donación, etc.

### ¿Qué son las stablecoins?

Son tokens en general fungibles que buscan mantener un valor estable, ya sea con el USD, el EUR u otro punto de referencia.

### ¿Cuáles son las stablecoins más importantes?

- DAI: busca garantizar la estabilidad a partir de un algoritmo. Para generar tokens éstos deben estar respaldados por un colateral de otras cryptos (por ejemplo ETH), que quedan bloqueados en un SM. También quema tokens de acuerdo a la variación del precio de los colaterales.
- USDC: emite tokens que en teoría están respaldados por dólares y otros activos. Hay empresas muy importantes detrás de este proyecto, como Circle (vinculada a Goldman Sachs).
- USDT: emite tokens que en teoría están respaldados por dólares y otros activos. Es la stablecoin más usada y de mayor market cap.

### ¿Por qué existen las mismas cryptos en distintas blockchains?

Capaz ya hayan notado que en en ethereum existe una crypto que se llama WBTC, o que en la bsc existen BTC, ETH y ADA entre otras.

En realidad, como ya vimos, en una blockchain existen monedas nativas (por ej, en la bsc es el BNB) y todo lo demás son tokens (en la bsc, BTC, ETH, ADA son tokens, es decir, como un derivado, un sintético, algo que dicen que representa el precio de BTC, ETH o ADA respectivamente).

También las stablecoins tienen tokens análogos en varias blockchains. Por ejemplo, hay USDT en ethereum (donde fue creado originalmente), así como en la bsc, polygon, tron y demás. Si bien en este caso, los USDT son emitidos por la misma empresa que los creó en ethereum, es importante saber que en cada blockchain son tokens distintos.

Para cada caso hay que analizar qué tan confiables y respaldados están.

También, al enviar o recibir una crypto (tanto nativa como token), es importante prestar atención en cuál blockchain se realiza la transacción. Por ejemplo, si alguien espera recibir BTC en una wallet de bitcoin, pero le envían el token BTC por la blockchain de bsc, esas cryptos nunca le van a llegar, y no hay forma de revertir la transacción. Ese dinero se pierde. Otro ejemplo: si alguien envía USDT por la red de tron y el receptor lo espera en la red de ethereum (erc 20), en este caso también se pierde el dinero.


## 03. ROADMAP PARA UN USUARIO DE CRIPTOMONEDAS

Esta guía, que es una opinión personal, una propuesta, enumera opciones en orden de dificultad creciente, para quien busque comenzar a usar criptomonedas.

### 1. CeFi

  - 1.1. CeFi + Stablecoins
  - 1.2. CeFi + Otra crypto

  Si bien usar un servicio centralizado puede ser algo contrario a la filosofía de bitcoin, considero que sí puede ser un primer paso útil. En empresas como binance, coinbase, nexo u otras, la UI es amigable y además hay material didáctico (artículos, videos, cursos). Uno puede aprender cuestiones básicas sobre cada crypto, cómo funciona y recibir noticias importantes sobre el tema. También va a ver las diferencias entre distintas wallets. Y al realizar envíos, va a conocer las distintas redes (blockchains) por donde se puede enviar un token (relacionar los distintos tokens con sus blockchains) y sus respectivos fees.
  Si a uno le asusta que BTC pueda caer 30% en un día, puede ser una buena opción comenzar con stablecoins. Además hay plataformas como nexo o binance que permiten generar ingresos pasivos con esos tokens.

### 2. Software wallet personal

  - 2.1.	SW personal + crypto nativa
  - 2.2.	SW personal + crypto nativa + DeFi
  - 2.3.	SW personal + crypto nativa + Token + DeFi

  En esta etapa la idea es aprender a: generar una wallet de la cual uno tenga posesión de las private keys, tener conceptos básicos sobre su seguridad, poder restaurar una cuenta, enviar y recibir cryptos desde ella. Nota: es importante usar la crypto nativa, ya que es la que sirve para pagar las fees.

  Ejemplos: metamask para ethereum, yoroi para cardano, polkadot.js para polkadot y kusama. Exodus para varias blockchains.

### 3.	Paper wallet

  - 3.1.	Paper wallet + software wallet

  En esta etapa la idea es aprender cómo funciona una paper wallet y cómo se puede recuperar (importar en una SW). Si después de importarla uno quiere volver a la seguridad de una paper wallet, puede volver a enviar los fondos a una PW cuya private key no haya sido expuesta.

  Ejemplos: paper wallet de BTC se puede importar en blockchain.info , mientras que paper wallet de ethereum se puede importar en metamask.

### 4.	Hardware wallet

  - 4.1.	HW + crypto nativa
  - 4.2.	HW + crypto nativa + delegating
  - 4.3.	HW + crypto nativa + DeFi

  Ejemplos: trezor y ledger. Cada una tiene su UI nativa.

### 5.	Hardware wallet + software wallet

  - 5.1. HW + SW + DeFi + Staking o delegating + NFT

  Ejemplo: importar una HW de ADA en Yoroi y delegar algunos ADA (no todos, ya que se necesitan cryptos nativas para las fees).

  Otro ejemplo: importar una HW de Cosmos en Keplr y delegar algunos ATOM (no todos, ya que se necesitan cryptos nativas para las fees).

### 6.	HW + SW + configurar una Layer 2 o una blockchain secundaria

  Ejemplo: usar una HW e importarla en Metamask. Luego, configurar MM con la bsc o polygon. Luego usar DeFi en esas blockchains.
