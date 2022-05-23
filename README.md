# beecrowd

To read Beecrowd inputs in JavaScript, you can define the prompt function as follows:

```javascript
const fs = require('fs')
const input = fs.readFileSync('/dev/stdin', 'utf8');
const lines = input.split('\n');
const prompt = () => lines.shift();
```

And then use `prompt` whenever you want to read input data.
