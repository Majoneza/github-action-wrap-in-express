# github-action-wrap-in-express action

This action wraps the specified program with express.

## Inputs

### `application-path`

**Required** Path from the root of the app repository. Default `"./"`.

### `default-port`

**Required** Port used when process.env.PORT is not defined. Default `8080`.

## Example usage

uses: Majoneza/github-action-wrap-in-express@v1
with:
  default-port: 10000
