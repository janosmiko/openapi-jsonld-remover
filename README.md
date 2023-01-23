# OpenAPI jsonld remover

This tool is able to remove jsonld entries from a given OpenAPI yaml file.

## Usage using poetry

```console
$ poetry init
```

```console
$ poetry run python main.py --input openapi.yaml --output output.yaml
```

## Usage using pip

```console
$ pip3 install -r requirements.txt
```

```console
$ python3 main.py --input openapi.yaml --output output.yaml
```

## Examples

The `input.yaml` file contains an example openapi specification with jsonld entries.

The `output.yaml` file contains the same specification without jsonld entries stripped down.