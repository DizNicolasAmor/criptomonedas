# CRIPTOMONEDAS

> El contenido de este archivo no es consejo financiero. En cambio, es meramente informativo: es una colección de apuntes y material relacionado con criptomonedas, basado en distintas fuentes y resumido.

## ÍNDICE

- [01. INTRODUCCIÓN](#cap-01)
  - ¿Qué es bitcoin?
  - ¿Qué son las criptomonedas?
  - ¿Cómo participar en la red de una crypto?
  - ¿Qué son las Private Keys y por qué son importantes?
  - ¿Cómo crear una wallet?
  - Comentarios finales
- [02. BLOCKCHAINS CON Y SIN SMART CONTRACTS](#cap-02)
  - Con SM VS sin SM
  - ¿En qué se diferencia una crypto nativa de un token?
  - ¿Qué tipos de tokens existen?
  - ¿Qué son las stablecoins?
  - ¿Cuáles son las stablecoins más importantes?
  - ¿Por qué existen las mismas cryptos en distintas blockchains?
- [03. ROADMAP PARA UN USUARIO DE CRIPTOMONEDAS](#cap-03)
  - 1. CeFi
  - 2. Software wallet personal
  - 3. Paper wallet
  - 4. Hardware wallet
  - 5. Hardware wallet + software wallet
  - 6. HW + SW + configurar una Layer 2 o una blockchain secundaria
- [04. EJEMPLOS DE OPCIONES PARA UTILIZAR CARDANO (ADA)](#cap-04)
  - 1. Exchange centralizado
  - 2. Software wallet + private key
  - 3. Hardware wallet + passphrase
- [05. EJEMPLOS DE OPCIONES PARA UTILIZAR ETHEREUM (ETH)](#cap-05)
  - 1. Exchange centralizado
  - 2. Software wallet + private key
  - 3. Hardware wallet + passphrase
- [06. GUÍA PARA EL ECOSISTEMA COSMOS (ATOM)](#cap-06)
  - Wallets
  - Delegación
  - Ecosistema
- [07. COMPLETAR](#cap-07)
- [08. COMPLETAR](#cap-08)
- [09. MATERIAL DE INTERÉS](#cap-09)
  - Blockchains principales
  - Divulgadores
  - Exchanges centralizados
  - Exchanges descentralizados
  - Finanzas centralizadas
  - Finanzas descentralizadas
  - Hardware wallets
  - Información del mercado
  - Noticias

<a name="cap-01"/>

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

<a name="cap-02"/>

## 02. BLOCKCHAINS CON Y SIN SMART CONTRACTS

### Con SM VS sin SM

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

<a name="cap-03"/>

## 03. ROADMAP PARA UN USUARIO DE CRIPTOMONEDAS

Esta guía, que es una opinión personal, una propuesta, enumera opciones en orden de dificultad creciente, para quien busque comenzar a usar criptomonedas.

### 1. CeFi

- 1.1. CeFi + Stablecoins
- 1.2. CeFi + Otra crypto

Si bien usar un servicio centralizado puede ser algo contrario a la filosofía de bitcoin, considero que sí puede ser un primer paso útil. En empresas como binance, coinbase, nexo u otras, la UI es amigable y además hay material didáctico (artículos, videos, cursos). Uno puede aprender cuestiones básicas sobre cada crypto, cómo funciona y recibir noticias importantes sobre el tema. También va a ver las diferencias entre distintas wallets. Y al realizar envíos, va a conocer las distintas redes (blockchains) por donde se puede enviar un token (relacionar los distintos tokens con sus blockchains) y sus respectivos fees.
Si a uno le asusta que BTC pueda caer 30% en un día, puede ser una buena opción comenzar con stablecoins. Además hay plataformas como nexo o binance que permiten generar ingresos pasivos con esos tokens.

### 2. Software wallet personal

- 2.1. SW personal + crypto nativa
- 2.2. SW personal + crypto nativa + DeFi
- 2.3. SW personal + crypto nativa + Token + DeFi

En esta etapa la idea es aprender a: generar una wallet de la cual uno tenga posesión de las private keys, tener conceptos básicos sobre su seguridad, poder restaurar una cuenta, enviar y recibir cryptos desde ella. Nota: es importante usar la crypto nativa, ya que es la que sirve para pagar las fees.

Ejemplos: metamask para ethereum, yoroi para cardano, polkadot.js para polkadot y kusama. Exodus para varias blockchains.

### 3. Paper wallet

- 3.1. Paper wallet + software wallet

En esta etapa la idea es aprender cómo funciona una paper wallet y cómo se puede recuperar (importar en una SW). Si después de importarla uno quiere volver a la seguridad de una paper wallet, puede volver a enviar los fondos a una PW cuya private key no haya sido expuesta.

Ejemplos: paper wallet de BTC se puede importar en blockchain.info , mientras que paper wallet de ethereum se puede importar en metamask.

### 4. Hardware wallet

- 4.1. HW + crypto nativa
- 4.2. HW + crypto nativa + delegating
- 4.3. HW + crypto nativa + DeFi

Ejemplos: trezor y ledger. Cada una tiene su UI nativa.

### 5. Hardware wallet + software wallet

- 5.1. HW + SW + DeFi + Staking o delegating + NFT

Ejemplo: importar una HW de ADA en Yoroi y delegar algunos ADA (no todos, ya que se necesitan cryptos nativas para las fees).

Otro ejemplo: importar una HW de Cosmos en Keplr y delegar algunos ATOM (no todos, ya que se necesitan cryptos nativas para las fees).

### 6. HW + SW + configurar una Layer 2 o una blockchain secundaria

Ejemplo: usar una HW e importarla en Metamask. Luego, configurar MM con la bsc o polygon. Luego usar DeFi en esas blockchains.

<a name="cap-04"/>

## 04. EJEMPLOS DE OPCIONES PARA UTILIZAR CARDANO (ADA)

Esta guía, que es una opinión personal, enumera opciones para utilizar Cardano, desde las más sencillas e inseguras, hasta las más complejas y seguras. Criterios similares pueden aplicarse para otras criptomonedas, con la salvedad de que, obviamente, pueden diferir los exchanges, software wallets y hardware wallets que soporta cada una.

### 1. Exchange centralizado

El paso más sencillo desde luego es abrir una cuenta en en un exchange que soporte la criptomoneda que uno busca (en este ejemplo, ADA). Después de crear la cuenta, el exchange crea una wallet y el usuario puede enviar y recibir monedas a esa wallet. Depende del exchange, a veces también se puede comprar y vender a cambio de monedas fiduciarias. Y por supuesto, también se pueden intercambiar (exchange, en inglés) por otras criptomonedas.

- Ejemplos: Binance, Coinbase, Kraken, Huobi, Kucoin, crypto.com.
- Ventajas: mayor sencillez, menor responsabilidad en el acceso a la wallet.
- Desventajas: menor seguridad (las monedas no están en poder del usuario, sino de la empresa que las tiene. Riesgos: pueden cambiar los TyC, pueden hackear el exchange, pueden hackear la cuenta del usuario).
- Otros servicios: depende el exchange, a veces también el usuario puede acceder a servicios financieros con sus ADA dentro del exchange. Por ejemplo, prestarlos (lending, saving) o delegarlos (para el staking) y así generar ingresos pasivos (generalmente en ADA).
- ¿Cuáles serían los pasos a seguir?
  - Registrarse
  - Obtener ADA
  - Usarlos.

### 2. Software wallet + private key

El siguiente paso es utilizar una software wallet del cual el usuario tenga la private key en su poder. El ejemplo más sencillo es "Yoroi": una extensión de Chrome que permite generar o importar wallets de Cardano.

- Ejemplo: Yoroi.
- Ventajas: mayor poder sobre las criptomonedas (ahora las monedas están en posesión del usuario, ya que posee la private key), menos regulaciones y restricciones.
- Desventajas: mayor complejidad (hay que aprender qué es una private key, qué es una seed, cómo protegerlas, cómo hacer un backup, cómo restaurar una cuenta, cómo delegar el voto para el staking), riesgo intermedio (existe aún un riesgo intermedio en este caso, por ejemplo, si la computadora del usuario fue comprometida, o lo fue la extensión de Yoroi, o si el usuario instaló una extensión no oficial).
- Otros servicios: por ahora (Julio 2021) el usuario puede delegar el voto de sus monedas para el staking y así generar ingresos pasivos (pagados en ADA).
- ¿Cuáles serían los pasos a seguir?
  - Instalar la extensión
  - Generar una nueva wallet
  - Guardar la private key o la seed, o ambas, de forma segura (la seed son doce palabras que se utilizan para generar la private key)
  - Borrar la wallet y volver a restaurarla (para confirmar que el backup de la seed es correcto)
  - Recibir y enviar fondos (comenzar con una cantidad mínima)
  - Dependiendo del caso, el usuario puede elegir si intentar delegar una parte de los fondos. No delegar todos los fondos, ya que es necesario mantener una cantidad líquida en la wallet para pagar las fees. Si la wallet se queda sin ADA líquidas, no va a poder retirar las que delegó.

### 3. Hardware wallet + passphrase

- Ejemplo: Ledger.
- Ventajas: mayor seguridad.
- Desventajas: mayor complejidad (hay que aprender qué es una hardware wallet, cómo proteger la seed, cómo hacer un backup, cómo restaurar una cuenta, cómo usar una passphrase).
- Otros servicios: idem anterior.
- ¿Cuáles serían los pasos a seguir?
  - Obtener una hardware wallet. Importante: se recomienda no comprarla de segunda mano ya que puede estar comprometida, sino directo de la empresa que las fabrica. Y deben estar cerradas como se muestra en las páginas oficiales de la empresa fabricante correspondiente.
  - Generar una nueva wallet.
  - Guardar la seed de forma segura.
  - Generar una cuenta con una passphrase.
  - Salir de esa cuenta y volver a entrar, para corroborar que la passphrase es correcta.
  - Dentro de Yoroi se puede importar la hardware wallet, para utilizar las funcionalidades explicadas en el punto anterior.

<a name="cap-05"/>

## 05. EJEMPLOS DE OPCIONES PARA UTILIZAR ETHEREUM (ETH)

### 1. Exchange centralizado

Este punto es similar a la primera parte del [04. EJEMPLOS DE OPCIONES PARA UTILIZAR CARDANO (ADA)](#cap-04)

### 2. Software wallet + private key

Este paso consiste en utilizar una software wallet del cual el usuario tenga la private key en su poder:

- Ejemplos: Metamask, MyEtherWallet, blockchain.info.
- Ventajas: mayor poder sobre las criptomonedas (ahora las monedas están en posesión del usuario, ya que posee la private key), menos regulaciones y restricciones.
- Desventajas: mayor complejidad (hay que aprender qué es una private key, qué es una seed, cómo protegerlas, cómo hacer un backup, cómo restaurar una cuenta), riesgo intermedio (existe aún un riesgo intermedio en este caso, por ejemplo, si la computadora del usuario fue comprometida, o el software hackeado, o si el usuario instaló un software no oficial).
- Otros servicios: el usuario puede interactuar con aplicaciones descentralizadas, como por ejemplo DeFi, juegos y demás.
- ¿Cuáles serían los pasos a seguir?
  - En caso de ser necesario, instalar la extensión o el software.
  - Generar una nueva wallet.
  - Guardar la private key o la seed, o ambas, de forma segura (la seed son doce palabras que se utilizan para generar la private key).
  - Borrar la wallet y volver a restaurarla (para confirmar que el backup de la seed es correcto).
  - Recibir y enviar fondos (comenzar con una cantidad mínima).
  - En una etapa más avanzada, el usuario elegir si interactuar con alguna aplicación descentralizada.

### 3. Hardware wallet + passphrase

- Ejemplo: Ledger o Trezor.
- Ventajas: mayor seguridad.
- Desventajas: mayor complejidad (hay que aprender qué es una hardware wallet, cómo proteger la seed, cómo hacer un backup, cómo restaurar una cuenta, cómo usar una passphrase).
- Otros servicios: idem anterior.
- ¿Cuáles serían los pasos a seguir?
  - Obtener una hardware wallet. Importante: se recomienda no comprarla de segunda mano ya que puede estar comprometida, sino directo de la empresa que las fabrica. Y deben estar cerradas como se muestra en las páginas oficiales de la empresa fabricante correspondiente.
  - Generar una nueva wallet.
  - Guardar la seed de forma segura.
  - Generar una cuenta con una passphrase.
  - Salir de esa cuenta y volver a entrar, para corroborar que la passphrase es correcta.
  - Dentro de Metamask, por ejemplo, se puede importar la hardware wallet, para utilizar las funcionalidades explicadas en el punto anterior.

<a name="cap-06"/>

## 06. GUÍA PARA EL ECOSISTEMA COSMOS (ATOM)

- Wallets

  - Lo más sencillo para comenzar es utilizar la extensión keplr. Es una extensión de Chromium que funciona de manera similar a Metamask o Yoroi, sólo que en las blockchain de Cosmos. Una alternativa a Keplr es Cosmostation.
    - Keplr: https://keplr.app/
    - Cosmostation: https://www.cosmostation.io/
  - Al igual que Metamask y Yoroi, Keplr es una interfaz que permite utilizar por ejemplo una hardware wallet como Ledger. Por lo tanto, el consejo final para utilizar una wallet de Cosmos es: crear una wallet en Ledger con PassPhrase y luego utilizar Keplr como interfaz.

- Delegación

  - Las criptomonedas de tu wallet pueden delegarse a un nodo y de esa forma generar ingresos pasivos.
  - Al delegar, las monedas salen de la wallet delegadora (gran diferencia con ADA).
  - Al delegar, se tarda 21 días en comenzar a recibir recompensas.
  - Al dejar de delegar, se tarda 21 días en que las monedas regresen a la wallet delegadora.

- Ecosistema

  - Con la misma private key que uno generó la wallet de Cosmos (ATOM), también tenés wallets en otras blockchains como Secret Network, Sentinel, Iris, Kava, entre otras.
  - Se puede hacer transferencias entre blockchains utilizando el puente IBC.

<a name="cap-07"/>

## 07. COMPLETAR

<a name="cap-08"/>

## 08. COMPLETAR

<a name="cap-09"/>

## 09. MATERIAL DE INTERÉS

### Blockchains principales

- Bitcoin
  - Página oficial: https://bitcoin.org/
  - Whitepaper: https://bitcoin.org/bitcoin.pdf
  - Source code: https://github.com/bitcoin/
  - Data: https://www.blockchain.com/charts
  - Explorer: https://www.blockchain.com/explorer
- Ethereum
  - Página oficial: https://ethereum.org/
  - Whitepaper: https://github.com/ethereum/wiki/wiki/White-Paper
  - Source code: https://github.com/ethereum
  - Data: https://etherscan.io/charts
  - Explorer: https://etherscan.io/
- Cardano
  - Página oficial: https://cardano.org/
  - Whitepaper: https://docs.cardano.org/introduction
  - Source code: https://cardanoupdates.com/
  - Data: https://cardanoscan.io/
  - Explorer: https://cardanoscan.io/
- BSC
  - Página oficial: https://www.binance.com/en
  - Whitepaper: -
  - Source code: -
  - Data: https://bscscan.com/
  - Explorer: https://bscscan.com/
- Polygon
  - Página oficial: https://polygon.technology/
  - Whitepapers: https://polygon.technology/papers/
  - Source code: https://github.com/maticnetwork/
  - Data: https://polygonscan.com/charts
  - Explorer: https://polygonscan.com/

### Divulgadores

- Andreas Antonopoulos
  - Página oficial: https://aantonop.com/
  - The Internet of Money (book)
  - Mastering Bitcoin (book)
  - Mastering Ethereum (book)
  - The Death of Money - PART 1/2 | London Real: https://www.youtube.com/watch?v=DuoE5CXlIdY
  - Escaping the Global Banking Cartel: https://www.youtube.com/watch?v=LgI0liAee4s
  - Cryptocurrency Explained: All the ships are sinking (Currency Wars II): https://www.youtube.com/watch?v=stN03wk_Wzs
  - The Crypto Airplane: understanding cryptocurrency ownership [bitcoin, ethereum]: https://www.youtube.com/watch?v=tYldJpSPeqg
- Benjamin Cowen
- Bob Loukas
- Charles Hoskinson (Cardano founder)
- Finematics

### Exchanges centralizados

> Recordar que en estos exchanges hay secciones educativas muy recomendables.

- Binance: https://www.binance.com/
- Coinbase: https://www.coinbase.com/
- Kraken: https://www.kraken.com/
- Huobi: https://www.huobi.com/
- Kucoin: https://www.kucoin.com/

### Exchanges descentralizados

- Uniswap (en la ethereum blockchain): https://uniswap.org/
- 1Inch (multichain): https://1inch.exchange/#/
- Sushiswap (multichain): https://sushi.com/
- Pancakeswap (en la bsc blockchain): https://pancakeswap.finance/
- Quickswap (en la polygon blockchain): https://quickswap.exchange/

### Finanzas centralizadas

- Nexo: https://nexo.io/
- BlockFi: https://blockfi.com/
- Celsius: https://celsius.network/
- crypto.com: https://crypto.com/

### Finanzas descentralizadas

- Compound finance (en ethereum): https://compound.finance/
- Aave (multichain): https://aave.com/
- Curve (multichain): https://curve.fi/
- Venus: https://venus.finance/app

### Hardware wallets

> Las páginas oficiales de las hardware wallets en general también poseen secciones educativas muy recomendables.

- Trezor: https://trezor.io/
- Ledger: https://www.ledger.com/

### Información del mercado

- Coingecko: https://www.coingecko.com/
- Coinmarketcap: https://coinmarketcap.com/
- DeFiPulse (sobre DeFi): https://defipulse.com/

### Noticias

- Cointelegraph: https://cointelegraph.com/
- Criptonoticias: https://www.criptonoticias.com/
