namesgenerator
==============

Docker names generator, ported to Python.

### Installation

Just copy `namesgenerator.py` to your project: 

```curl -O https://raw.githubusercontent.com/shamrin/namesgenerator/master/namesgenerator.py```

### Usage

```python
>>> import namesgenerator

>>> namesgenerator.get_random_name()
'trusting_lalande'

>>> [namesgenerator.get_random_name() for _ in range(10)]
['kickass_pike',
 'evil_kowalevski',
 'condescending_lovelace',
 'prickly_hypatia',
 'sleepy_lovelace',
 'drunk_babbage',
 'condescending_mestorf',
 'jolly_galileo',
 'dreamy_wright',
 'naughty_wozniak']
```

### Other implementations

* [Go][2] (original)
* [JavaScript][1]

[1]: https://github.com/tonypujals/docker-namesgenerator
[2]: https://github.com/docker/docker/blob/master/pkg/namesgenerator/names-generator.go
