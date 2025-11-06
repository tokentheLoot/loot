# theLoot (LOOT) — Whitepaper

**Experimental ERC-20 Token for Decentralized Value and Payments**

---

## 🪙 Overview

**theLoot (LOOT)** es un token experimental ERC-20 desplegado en Ethereum Mainnet, diseñado para explorar nuevos modelos de **creación de valor descentralizado** y su aplicación en **pagos en comercios**, sustituyendo monedas fiat en transacciones reales.

El proyecto combina una temática inspirada en **tesoros, comercio y propiedad digital**, con una tokenómica simple, transparente y completamente auditable.

---

## 🔧 Smart Contract

- **Contract Address:** [0xbcf89b0ee8d06a3c3d9ef5bdd32b61bdbf9ee24f](https://etherscan.io/token/0xbcf89b0ee8d06a3c3d9ef5bdd32b61bdbf9ee24f)
- **Blockchain:** Ethereum Mainnet  
- **Standard:** ERC-20  
- **Name:** theLoot  
- **Symbol:** LOOT  
- **Total Supply:** 21,000,000 LOOT  
- **Decimals:** 18  
- **Owner:** 0x07B1CB59aB9C0D19574696de1ff230f26a2469a7  
- **Verified on:** [Etherscan](https://etherscan.io/token/0xbcf89b0ee8d06a3c3d9ef5bdd32b61bdbf9ee24f#code)

El contrato fue desarrollado con **OpenZeppelin (v4)** y está completamente **verificado en Etherscan**, permitiendo inspección pública y auditorías externas.

---

## 💰 Tokenomics

- **Suministro total:** 21,000,000 LOOT  
- **Emisión inicial:** 100% asignada al creador para establecer liquidez y distribución temprana.  
- **Función mint/burn:** disponibles solo para el propietario, con intención de futura **renuncia de propiedad (renounceOwnership)** una vez completada la etapa experimental.  
- **Objetivo:** fomentar adopción gradual mediante integración en comercios y ecosistemas de pago descentralizado.

---

## 💧 Liquidez y Trading

### Uniswap V3

- **Par activo:** LOOT / USDT  
- **Comisión de pool:** 0.3%  
- **Liquidez inicial:** 8 LOOT ↔ 8 USDT  

**Enlaces:**
- [Comprar LOOT con USDT](https://app.uniswap.org/swap?inputCurrency=0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48&outputCurrency=0xbcf89b0ee8d06a3c3d9ef5bdd32b61bdbf9ee24f&chain=mainnet)  
- [Agregar liquidez LOOT-USDT](https://app.uniswap.org/add/v3/LOOT-USDT/3000)  
- [Vender LOOT por USDT](https://app.uniswap.org/swap?inputCurrency=0xbcf89b0ee8d06a3c3d9ef5bdd32b61bdbf9ee24f&outputCurrency=0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48&chain=mainnet)

---

## ⚙️ Tecnología

theLoot utiliza la arquitectura estándar **ERC-20** con compatibilidad completa con todas las billeteras y DEX de Ethereum.  
El contrato hereda de **ERC20** y **Ownable** de OpenZeppelin para garantizar seguridad y control temporal durante la etapa inicial.

Características clave:
- Código **verificado y auditable públicamente**.  
- Funciones `mint()` y `burn()` opcionales.  
- Preparado para **renuncia de propiedad** (propietario = 0x0) una vez completadas pruebas.  

---

## 🔐 Seguridad y Confianza

Para garantizar la transparencia y evitar clasificaciones erróneas como “honeypot”, el proyecto contempla los siguientes pasos:
1. Mantener el contrato **verificado y público**.  
2. **Publicar el whitepaper y enlaces oficiales** en Etherscan y GitHub.  
3. Proceder al **renounceOwnership()** una vez actualizados todos los metadatos, eliminando control administrativo.  

---

## 🌐 Recursos Oficiales

- **Sitio web:** [https://tokentheloot.github.io/loot/](https://tokentheloot.github.io/loot/)
- **Telegram:** [https://t.me/tokentheLoot](https://t.me/tokentheLoot)
- **GitHub:** [https://github.com/tokentheLoot/loot](https://github.com/tokentheLoot/loot)
- **Correo oficial:** tokentheloot@hotmail.com  
- **Logo:** [https://raw.githubusercontent.com/tokentheLoot/loot/main/logo.png](https://raw.githubusercontent.com/tokentheLoot/loot/main/logo.png)

---

## 📜 Licencia

Código fuente bajo licencia **MIT**, basado en librerías OpenZeppelin.

© 2025
