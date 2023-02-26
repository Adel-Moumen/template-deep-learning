# Template Deep Learning

This is a template for deep learning projects. Please change the following files:
- `README.md`: This file
- `LICENSE`: The license file
- `setup.py`: The setup file
- `requirements.txt`: The requirements file
- `src/`: The source code directory
- `tests/`: The test directory
- `docs/`: The documentation directory
- `data/`: The data directory
- `notebooks/`: The notebooks directory

### Setup
In a conda env with pytorch / cuda available, run
```
pip install -r requirements.txt
```
Then in this repository
```
pip install -e .
```

### Basic Usage

You can call `Fire` on any Python object:<br>
functions, classes, modules, objects, dictionaries, lists, tuples, etc.
They all work!

Here's an example of calling Fire on a function.

```python
import fire

def hello(name="World"):
  return "Hello %s!" % name

if __name__ == '__main__':
  fire.Fire(hello)
```

### License
See the [LICENSE](LICENSE) file.