# Estúdio Digital Bocca

## edb-dom

### v0.8.0

> Um seletor de elementos sem gorduras.

[![JavaScript Style Guide](https://cdn.rawgit.com/standard/standard/master/badge.svg)](https://github.com/standard/standard)

[![JavaScript Style Guide](https://badgen.net/badge/code%20style/standard/yellow)](https://standardjs.com)
[![Maintainability](https://api.codeclimate.com/v1/badges/30decef694c971b3fc5b/maintainability)](https://codeclimate.com/github/digitalbocca/edb-dom/maintainability)
[![EDB](https://badgen.net/badge/produto/EDB/f19b2c)](https://estudiodigitalbocca.com.br)
[![NPMv](https://badgen.net/npm/v/edb-dom)](https://www.npmjs.com/package/edb-dom)
[![NPMlicense](https://badgen.net/npm/license/edb-dom)](https://www.npmjs.com/package/edb-dom)
[![NPMdownloads](https://badgen.net/npm/dt/edb-dom)](https://www.npmjs.com/package/edb-dom)
[![GHv](https://badgen.net/github/tag/digitalbocca/edb-dom)](https://github.com/digitalbocca/edb-dom)
[![DVdep](https://badgen.net/david/dep/digitalbocca/edb-dom)](https://www.npmjs.com/package/edb-dom)
[![DVdev](https://badgen.net/david/dev/digitalbocca/edb-dom)](https://www.npmjs.com/package/edb-dom)
[![PPi](https://badgen.net/packagephobia/install/edb-dom)](https://www.npmjs.com/package/edb-dom)
[![PPp](https://badgen.net/packagephobia/publish/edb-dom)](https://www.npmjs.com/package/edb-dom)
[![BPp](https://badgen.net/bundlephobia/min/edb-dom)](https://www.npmjs.com/package/edb-dom)
[![BPp](https://badgen.net/bundlephobia/minzip/edb-dom)](https://www.npmjs.com/package/edb-dom)

## PROPOSTA

Usar uma sintaxe de seletores curta parecida com o jQuery sem as gorduras de uma biblioteca completa.

## EXEMPLO DE USO

- Adicione como uma dependência:

```bash
npm install --save edb-dom
```

- Importe nos arquivos que precisar:

```javascript
import $ from 'edb-dom'
```

- Substitua:

```javascript

// FORMATO ANTIGO. LONGO, CHATO E CANSATIVO:
document.querySelector('#idDoMeuElemento')

// OU AINDA:
document.getElementByID('idDoMeuElemento')

// EDB DOM
$('#idDoMeuElemento')

```

## LOG DE MUDANÇAS

- Veja no arquivo [CHANGELOG](CHANGELOG.md)

> Esta é uma versão em desenvolvimento.
> (c)2018-2019 Estúdio Digital Bocca
