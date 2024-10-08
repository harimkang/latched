# Contributing to Latched

We utilize poetry to manage the dependencies and virtual environment. Check the [poetry documentation](https://python-poetry.org/docs/) for more details. Basic usage is as follows:

### How to use Poetry
1. Install the Poetry
    ```shell
    # Liunux
    curl -sSL https://install.python-poetry.org | python3 -
    # Window
    (Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | py -
    ```
2. Update the poetry
    ```shell
    poetry self update
    ```

3. Install the dependencies
    ```shell
    poetry install --with dev
    ```

4. Run the poetry virtual environment
    ```shell
    poetry shell
    python your_code.py
    ```

5. Deactivate
    ```shell
    deactivate
    ```

### Run pre-commit
```shell
poetry run pre-commit run --all-files
```
