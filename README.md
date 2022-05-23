# beecrowd
---


Para ler as entradas dos exercícios da plataforma Beecrowd em JavaScript, pode-se definir a função `prompt` dessa forma:

```javascript
const fs = require('fs')
const input = fs.readFileSync('/dev/stdin', 'utf8');
const lines = input.split('\n');
const prompt = () => lines.shift();
```

E, então, usar o `prompt` sempre que se quiser ler dados de entrada.

---

To read Beecrowd exercises inputs in JavaScript, you can define the prompt function as follows:

```javascript
const fs = require('fs')
const input = fs.readFileSync('/dev/stdin', 'utf8');
const lines = input.split('\n');
const prompt = () => lines.shift();
```

And then use `prompt` whenever you want to read input data.
