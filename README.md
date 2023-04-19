# Mr Steal Yo Crypto CTF

**Una serie de desafíos para continuar aprendiendo seguridad ofensiva en contratos inteligentes.** Incluyendo desafíos interesantes muy relacionados (o directamente) inspirados en exploits del mundo real.

Creado por [@0xToshii](https://twitter.com/0xToshii)

## Para jugar

Visitar [mrstealyocrypto.xyz](https://mrstealyocrypto.xyz)

Cartilla y consejos: [degenjungle.substack.com/p/mr-steal-yo-crypto-wargame](https://degenjungle.substack.com/p/mr-steal-yo-crypto-wargame)

Nota: El branch main incluye las soluciones del creador, correr <code>git checkout implement</code> para ver los problemas sin sus respectivas soluciones y <code>git checkout explicados</code> para ver soluciones explicadas por mi 😊

## Instrucciones para Foundry

1. Instalación: [foundry-book](https://book.getfoundry.sh/getting-started/installation)

2. Clonar este repo e instalar dependencias
```console
forge install
```

3. Codear tus soluciones y luego correr el archivo test asociado
```console
forge test --match-path test/challenge-name.sol
```

### Reglas & Tips
- En todos los desafíos debes usar la cuenta llamada attacker (a menos que sea especificado).
- En algunos casos, puede ser que necesites codear y deployar contratos inteligentes customizados.
