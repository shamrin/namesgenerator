namesgenerator
==============

Docker-style names generator, ported to Python and JavaScript/TypeScript.

### JavaScript

Just copy `namesgenerator.js` to your project: 

```
curl -O https://raw.githubusercontent.com/shamrin/namesgenerator/master/namesgenerator.js
```

Or as TypeScript module:

```
curl -o namesgenerator.ts https://raw.githubusercontent.com/shamrin/namesgenerator/master/namesgenerator.js
```

Or install [`namesgenerator` npm package](https://www.npmjs.com/package/namesgenerator):

```
npm install --save namesgenerator
```

#### Usage

```js
import getRandomName from './namesgenerator';

console.log(getRandomName()) // hopeful_morse
```

### Python

Just copy `namesgenerator.py` to your project: 

```
curl -O https://raw.githubusercontent.com/shamrin/namesgenerator/master/namesgenerator.py
```

Or install [`namesgenerator` PyPI package](https://pypi.org/project/namesgenerator/):

```
pip install namesgenerator
```

#### Usage

```python
>>> import namesgenerator
>>> print namesgenerator.get_random_name()
hopeful_morse
>>> for i in range(5):
...   print namesgenerator.get_random_name()
...
angry_torvalds
jolly_nobel
happy_almeida
sleepy_kowalevski
happy_almeida
```

### Other implementations

* [Go][2] (original)
* [Alternative JavaScript implementation, Node.js only][1]

[1]: https://github.com/atomiqio/docker-namesgenerator
[2]: https://github.com/docker/docker/blob/master/pkg/namesgenerator/names-generator.go
