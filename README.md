# regex

Some regex review.

## Metacaracters

### []

Specifies a specific set of characters to match

```python
re.search(r'[a-zA-Z]', 'aaa')
```

### dot (.)

Specifies a wildcard

### \w \W

Match a word character. \W matches anything but a word.

```python
re.search(r'\w', '#(.$a@&')  # this will match "a"
```

### \d \D

Matches any decimal digit character.
