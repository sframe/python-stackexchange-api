# Python & StackExchange API

Something whipped up quickly that does nothing but gather and show data from the [StackExchange API](https://api.stackexchange.com)

## :computer: Dependencies

- [StackAPI](https://stackapi.readthedocs.io/en/latest/index.html) - A Python wrapper for the StackExchange API


## :wrench: Setup

Clone this repo.

```sh
git clone git@github.com:sframe/python-stackexchange-api.git
```

```sh
cd python-stackexchange-api
```

### :beginner: Considerations for New Python Users

Use a Python version manager, e.g.[`pyenv`](https://github.com/pyenv/pyenv#installation)

```sh
pyenv install 3.11.2
```

Use Python's built in [`venv`](https://docs.python.org/3/library/venv.html) to keep module installations clean and isolated to this project.

```sh
python -m venv .venv
```

Installing is not enough! [`source`](https://docs.python.org/3/library/venv.html#how-venvs-work) should be run for every new session.

```sh
source .venv/bin/activate
```

### :nut_and_bolt: Install Dependencies

Don't pollute your global python installation with project dependencies. See [Considerations for New Python Users](#considerations-for-new-python-users)

```sh
pip install -r requirements.txt
```

## :sparkles: Usage

```sh
python -m examples.comments
```

```sh
python -m examples.questions
```

```sh
python -m examples.users
```
