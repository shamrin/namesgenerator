namesgenerator
==============

Docker names generator, ported to Python.

### Installation

Just copy `namesgenerator.py` to your project: 

```curl -O https://raw.githubusercontent.com/shamrin/namesgenerator/master/namesgenerator.py```

### Usage

```python
import namesgenerator

print namesgenerator.get_random_name()
```

### Other implementations

* [Go][2] (original)
* [JavaScript][1]

[1]: https://github.com/tonypujals/docker-namesgenerator
[2]: https://github.com/docker/docker/blob/master/pkg/namesgenerator/names-generator.go
