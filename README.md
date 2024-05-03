# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log. Uses the toolkit <https://github.com/actions/toolkit>.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default "World".

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: actions/hello-world-javascript-action@main
with:
    who-to-greet: 'Mona the Octocat'
```
