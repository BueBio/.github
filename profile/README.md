# Hola 👋. Bienvenidos a BueBio.


### 🔭 ¿Qué es BueBio?
Buebio es una solución DeFi que ayuda a generar liquidez financiera a productores agroecológicos. El proyecto intenta resolver un problema en los mercados de producción agroecológica: la falta de liquidez.

Los mercados ecologicamente responsables no escalan por falta de financiamiento directo. La propuesta es utilizar herramientas financieras descentralizadas para resolver este paradigma. La herramienta propone múltiples servicios escalables ya sea a travez de vaults de acceso via NFT o a partir de la tokenización de un activo de la economía real, se permite la creación de mercados de liquidez en mercados DeFi.

### 🌱 Alcance
El alcance inicial de la herramienta es un sistema productivo que valide la hipótesis inicial con al menos una industria y un producto. Deberá tokenizar una oferta de inversión de producción certificada y permitir el acceso a liquidez.


### 👯 Tokenomics
La plataforma permite a un organismo de control otorgue NFTs a modo de llaves para la creación de Vaults. Un Vault es una oportunidad financiera propuesta por un productor de la economía sustentable.

A partir de un proceso de onbording offchain, se produce una oferta de Vault a uno o distintos organismos de control. Una oferta de vault es un contrato inteligente que se construye con datos de carga: una descripción, rendimiento, período, etc.

Este Vault tiene el aval y aprobación del organismo de control y una esytructura de comunicación que manifiesta o expone un  mercado de la economía sustentable a travez de un marketplace accesible y dinámico.

Los inversores interesados en depositar valores en cada uno, con un simple click ya están aportando valores directamente a un productor que propone la oferta. Y, a este inversor, se le entrega un NFT de rendimiento para que oferte en un mercado secundario.

### 😍 ¿Cuáles son algunos de los Casos de Uso en BueBio?
- Pre Financiación de producción agroecológica
- Retribución a donantes y contribuyentes
- Inversión de impacto a cambio de una tasa


## 🤔 Avance desarrollo de BueBio

El siguiente informe presenta los avances del Proyecto BueBio.

Esferas de trabajo

1. Landing de presentación
2. Dashboard: dapp donde el usuario accede y gestiona su cuenta, vaults, llaves y rendimiento.
3. Backend de gestión.

#### 1. Landing de presentación.

- URL Prod: https://buebio.com

- URL Dev:  https://dev.buebio.com


Portal inicial de la plataforma. Propone el ecosistema de vaults y exhibe una oportunidad de economia sustentable a fondos y productores.
Comunica también la sección institucional del proyecto a travez del respaldo de sus partes.
Desarrollado en ReactJS con API de contenidos en Node.JS y MongoDB.

#### 2. Dashboard

- URL Dev: https://dapp.dev.buebio.com

Dapp de gestión para la relación entre cuentas, NFTs y Vaults. Presenta los vaults disponibles, su nombre, respaldo, propuesta, etc. Presenta los NFTs "llaves" que existen en el ecosistema y qué accesos a vaults permiten. Integración a metamask por medio de rLogin
Nfts por cuenta loeguada (en la parte de "My Active NFTs"). Para esto se valida en el contrato del nft que la wallet conectada tenga un nft

Muchos de estos puntos están aun en desarrollo, pero las partes iniciales de la arquitectura están ya identificadas y constituídas.

#### 3.Backend de Gestión.

La solución cuenta con una parte offchain de gestión. Desde un backend de contenidos se gestionan los Vaults, NFTs y relación de estos y llaves para consultas asyncronicas de contenidos.
Almacena IDs de de identidad de distintas wallets y permite escalar en nuevas integraciones futuras.

#### Código de desarrollo.

A continuación se deja constancia del código fuente de la plataforma. Sus partes son la API, landing de presentación y la dapp de gestión.

https://github.com/buebio
