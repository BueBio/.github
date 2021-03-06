# Hola 馃憢. Bienvenidos a BueBio.


### 馃敪 驴Qu茅 es BueBio?
Buebio es una soluci贸n DeFi que ayuda a generar liquidez financiera a productores agroecol贸gicos. El proyecto intenta resolver un problema en los mercados de producci贸n agroecol贸gica: la falta de liquidez.

Los mercados ecologicamente responsables no escalan por falta de financiamiento directo. La propuesta es utilizar herramientas financieras descentralizadas para resolver este paradigma. La herramienta propone m煤ltiples servicios escalables ya sea a travez de vaults de acceso via NFT o a partir de la tokenizaci贸n de un activo de la econom铆a real, se permite la creaci贸n de mercados de liquidez en mercados DeFi.

### 馃尡 Alcance
El alcance inicial de la herramienta es un sistema productivo que valide la hip贸tesis inicial con al menos una industria y un producto. Deber谩 tokenizar una oferta de inversi贸n de producci贸n certificada y permitir el acceso a liquidez.


### 馃懐 Tokenomics
La plataforma permite a un organismo de control otorgue NFTs a modo de llaves para la creaci贸n de Vaults. Un Vault es una oportunidad financiera propuesta por un productor de la econom铆a sustentable.

A partir de un proceso de onbording offchain, se produce una oferta de Vault a uno o distintos organismos de control. Una oferta de vault es un contrato inteligente que se construye con datos de carga: una descripci贸n, rendimiento, per铆odo, etc.

Este Vault tiene el aval y aprobaci贸n del organismo de control y una esytructura de comunicaci贸n que manifiesta o expone un  mercado de la econom铆a sustentable a travez de un marketplace accesible y din谩mico.

Los inversores interesados en depositar valores en cada uno, con un simple click ya est谩n aportando valores directamente a un productor que propone la oferta. Y, a este inversor, se le entrega un NFT de rendimiento para que oferte en un mercado secundario.

### 馃槏 驴Cu谩les son algunos de los Casos de Uso en BueBio?
- Pre Financiaci贸n de producci贸n agroecol贸gica
- Retribuci贸n a donantes y contribuyentes
- Inversi贸n de impacto a cambio de una tasa


## 馃 Avance desarrollo de BueBio

El siguiente informe presenta los avances del Proyecto BueBio.

Esferas de trabajo

1. Landing de presentaci贸n
2. Dashboard: dapp donde el usuario accede y gestiona su cuenta, vaults, llaves y rendimiento.
3. Backend de gesti贸n.

#### 1. Landing de presentaci贸n.

- URL Prod: https://buebio.com

- URL Dev:  https://dev.buebio.com


Portal inicial de la plataforma. Propone el ecosistema de vaults y exhibe una oportunidad de economia sustentable a fondos y productores.
Comunica tambi茅n la secci贸n institucional del proyecto a travez del respaldo de sus partes.
Desarrollado en ReactJS con API de contenidos en Node.JS y MongoDB.

#### 2. Dashboard

- URL Dev: https://dapp.dev.buebio.com

Dapp de gesti贸n para la relaci贸n entre cuentas, NFTs y Vaults. Presenta los vaults disponibles, su nombre, respaldo, propuesta, etc. Presenta los NFTs "llaves" que existen en el ecosistema y qu茅 accesos a vaults permiten. Integraci贸n a metamask por medio de rLogin
Nfts por cuenta loeguada (en la parte de "My Active NFTs"). Para esto se valida en el contrato del nft que la wallet conectada tenga un nft

Muchos de estos puntos est谩n aun en desarrollo, pero las partes iniciales de la arquitectura est谩n ya identificadas y constitu铆das.

#### 3.Backend de Gesti贸n.

La soluci贸n cuenta con una parte offchain de gesti贸n. Desde un backend de contenidos se gestionan los Vaults, NFTs y relaci贸n de estos y llaves para consultas asyncronicas de contenidos.
Almacena IDs de de identidad de distintas wallets y permite escalar en nuevas integraciones futuras.

#### C贸digo de desarrollo.

A continuaci贸n se deja constancia del c贸digo fuente de la plataforma. Sus partes son la API, landing de presentaci贸n y la dapp de gesti贸n.

https://github.com/buebio
