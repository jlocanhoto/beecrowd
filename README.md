# beecrowd

Para ler as entradas dos exercícios da plataforma [Beecrowd](https://www.beecrowd.com.br/) em JavaScript, pode-se definir a função `prompt` dessa forma:

```javascript
const fs = require('fs')
const input = fs.readFileSync('/dev/stdin', 'utf8');
const lines = input.split('\n');
const prompt = () => lines.shift();
```

E, então, usar o `prompt` sempre que se quiser ler dados de entrada.

Por exemplo, para o exercício [BEE 1001](https://www.beecrowd.com.br/judge/pt/problems/view/1001), uma resposta seria:

```javascript
// Configuração

const fs = require('fs')
const input = fs.readFileSync('/dev/stdin', 'utf8');
const lines = input.split('\n');
const prompt = () => lines.shift();

// Solução do Exercício

```
