namesgenerator
==============

Docker-style names generator, ported to Python and JavaScript/TypeScript.

This is a fork of https://github.com/shamrin/namesgenerator

The only difference is that it has fixed for Pyhton 3 and made avalilable via pip:

```pip install namesgenerator```

### JavaScript

Just copy `namesgenerator.js` to your project: 

```
curl -O https://raw.githubusercontent.com/shamrin/namesgenerator/master/namesgenerator.js
```

Or as TypeScript module:

```
curl -o namesgenerator.ts https://raw.githubusercontent.com/shamrin/namesgenerator/master/namesgenerator.js
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

[1]: https://github.com/tonypujals/docker-namesgenerator
[2]: https://github.com/docker/docker/blob/master/pkg/namesgenerator/names-generator.go
