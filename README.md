# Estúdio Digital Bocca

## edb-dom

### v0.2.0

> Um seletor de elementos sem gorduras.

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

### Mudanças na v0.2.0

- Automatizado o controle de versão.

> Esta é uma versão em desenvolvimento.
> (c)2018 - Estúdio Digital Bocca