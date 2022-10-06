<p align="center">
  <img src="https://estudiodigitalbocca.com.br/edb-logo.svg" width="200px">
  <h1 align="center">edb-dom</h1>
  <h4 align="center">
    Um seletor de elementos livre de gorduras.
  </h4>
  <p align="center">
    <img src="https://badgen.net/badge/version/v0.13.0/orange">
    <a href="https://standardjs.com">
      <img src="https://badgen.net/badge/code%20style/standard/yellow">
    </a>
    <a href="https://codeclimate.com/github/digitalbocca/edb-dom/maintainability">
      <img src="https://api.codeclimate.com/v1/badges/30decef694c971b3fc5b/maintainability">
    </a>
    <a href="https://estudiodigitalbocca.com.br">
      <img src="https://badgen.net/badge/produto/EDB/f19b2c">
    </a>
    <a href="https://www.npmjs.com/package/edb-dom">
      <img src="https://badgen.net/npm/v/edb-dom">
    </a>
    <a href="https://www.npmjs.com/package/edb-dom">
      <img src="https://badgen.net/npm/license/edb-dom">
    </a>
    <a href="https://www.npmjs.com/package/edb-dom">
      <img src="https://badgen.net/npm/dt/edb-dom">
    </a>
    <a href="https://github.com/digitalbocca/edb-dom">
      <img src="https://badgen.net/github/tag/digitalbocca/edb-dom">
    </a>
    <a href="https://www.npmjs.com/package/edb-dom">
      <img src="https://badgen.net/david/dep/digitalbocca/edb-dom">
    </a>
    <a href="https://www.npmjs.com/package/edb-dom">
      <img src="https://badgen.net/david/dev/digitalbocca/edb-dom">
    </a>
    <a href="https://www.npmjs.com/package/edb-dom">
      <img src="https://badgen.net/packagephobia/install/edb-dom">
    </a>
    <a href="https://www.npmjs.com/package/edb-dom">
      <img src="https://badgen.net/packagephobia/publish/edb-dom">
    </a>
    <a href="https://www.npmjs.com/package/edb-dom">
      <img src="https://badgen.net/bundlephobia/min/edb-dom">
    </a>
    <a href="https://www.npmjs.com/package/edb-dom">
      <img src="https://badgen.net/bundlephobia/minzip/edb-dom">
    </a>
  </p>
  <p align="center">
    <a href="https://github.com/standard/standard">
      <img src="https://cdn.rawgit.com/standard/standard/master/badge.svg">
    </a>
  </p>
  <p align="center">(c)2018-2022 Estúdio Digital Bocca</p>
</p>

---

# edb-dom - README

---

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

## REGISTRO DE ALTERAÇÕES

- Veja no arquivo [CHANGELOG](CHANGELOG.md)

> Esta é uma versão em desenvolvimento.
> (c)2018-2022 Estúdio Digital Bocca
