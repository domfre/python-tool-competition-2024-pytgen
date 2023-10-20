# Python Tool Competition Implementation Using pytgen

Uses the python-tool-competition-2024 to generate tests using
pytgen.

For more information see
<https://github.com/ThunderKey/python-tool-competition-2024/>.

## Installation

* Install [poetry](https://python-poetry.org/)
* Run `poetry install`

## Development

The entry point called by `python-tool-competition-2024` is the `build_test`
method in `python_tool_competition_2024_pytgen/generator.py`.

## Calculating Metrics

Run `poetry run python-tool-competition-2024 run pytgen`.

With `poetry run python-tool-competition-2024 run -h` you can find out what
generators were detected.
