# GMX (Guess My X)

## Installing

```bash
$: pip install guess_my_x
```

## Playing

Create a file named `main.py`:
```python
from guess_my_x import GMX

guess_my_number = GMX(list(range(100)))

if __name__ == "__main__":
    guess_my_number.play(rounds=15)
```

Then run it:
```bash
$: python main.py

Your guess:
```

## Developing

Clone this repository to your machine, then:

```bash
$: cd guess_my_x
$: python -m unittest
```
