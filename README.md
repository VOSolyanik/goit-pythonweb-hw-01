# goit-pythonweb-hw-01

## Init environment:

- Run `poetry install` to install dependencies
- Run `poetry shell` to activate environment

## Task 1: Patterns

### Result:

- Created abstract base `Vehicle` class.
- `Car`, `Motorcycle` classes extended from `Vehicle` and have own implementations of `start_engine` method.
- Created abstract factory `VehicleFactory`
- Created `USVehicleFactory`, `EUVehicleFactory` which extended from `VehicleFactory` and adds specification value to the `model` name on vehicle creation

### Run:

- Run command: `python task_1.py` or `poetry run python task_1.py`

## Task 2: SOLID Principles

### Result:

- SRP: created `Book` class
- OCP: `Library` class refactored, using `Book` class instances
- LSP: Implemented `LibraryInterface` abstract class
- ISP: `Library` extended from `LibraryInterface`
- DIP: `LibraryManager` works with interface, not with particular realization

### Run:

- Run command: `python task_2.py` or `poetry run python task_2.py`
