# hello-javascript-action
A Github Action build using javascript for greeting a contributer.

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: Jonsy13/hello-javascript-action@v1
with:
  who-to-greet: 'Mona the Octocat'
