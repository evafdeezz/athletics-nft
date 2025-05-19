# 🏆 Copa de Naciones – Campeonato de Atletismo en Blockchain

Este proyecto es una aplicación descentralizada (dApp) que permite a los atletas **inscribirse en pruebas de atletismo** mediante el uso de tecnología blockchain y tokens no fungibles (NFTs).

La inscripción se gestiona a través de un contrato inteligente desplegado en la red de pruebas **Ethereum Sepolia**, y cada inscripción válida genera un NFT único tipo **ERC-1155**, que representa la participación del atleta en una prueba específica.

## 📌 ¿En qué consiste?

La dApp simula una competición llamada **Copa de Naciones – Liga de Selecciones**, celebrada el 27 de junio de 2025. Los atletas deben:

- Conectar su wallet MetaMask.
- Indicar su sexo (masculino o femenino).
- Introducir su edad (mínimo 16 años).
- Ver las pruebas disponibles para su perfil.
- Inscribirse en una prueba (una sola vez).
- Recibir un NFT como justificante.

Las pruebas están organizadas por:
- **Sexo**: masculino o femenino.
- **Categoría**: Sub18, Sub20, Sub23 y Absoluto.
- **Disciplina**: carrera, salto, lanzamiento, etc.

## ⚙️ Tecnologías utilizadas

- **Solidity**: contrato inteligente con ERC-1155 + Ownable.
- **Remix IDE**: desarrollo y pruebas.
- **JavaScript + Web3.js**: frontend que interactúa con MetaMask.
- **IPFS + Pinata**: almacenamiento de imágenes y metadatos de los NFTs.
- **Azure Web App**: despliegue de la web.
- **Etherscan**: verificación del contrato.
- **OpenSea Testnet**: visualización pública de los NFTs.

## 📁 Organización del contenido

- `imagenes/`: carpeta con las imágenes de las pruebas.
- `metadatos/`: carpeta con archivos JSON para cada NFT (nombre, descripción, imagen y atributos como categoría, sexo y tipo).

## ✅ Estado del proyecto

- [x] Contrato desplegado en Sepolia
- [x] Verificado en Etherscan
- [x] Web funcional y desplegada
- [x] NFTs visibles en OpenSea Testnet
- [x] Recursos correctamente alojados en IPFS

## 🔗 Enlaces importantes

- Contrato en Sepolia:  
  [`0xEa806E56bedBEe07bB8b2b991a21191F44a9005D`](https://sepolia.etherscan.io/address/0xEa806E56bedBEe07bB8b2b991a21191F44a9005D)

- WebApp en Azure:  
  https://blockchain-atletismo-e5h6bqfwhgbva7f0.spaincentral-01.azurewebsites.net/

- Colección en OpenSea Testnet:
    https://testnets.opensea.io/collection/unidentified-contract-e1feb938-5e30-40a7-bbdb-1348
