# &lt;x-random-string&gt;

Generates a random string [0-9][A-Z][a-z].

## Demo

[Check it live!](http://emiljohansson.github.io/x-random-string)

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/x-random-string/dist/x-random-string.html">
    ```

3. Start using it!

    ```html
    <x-random-string></x-random-string>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`length`      | *integer*   | `10`         | The number of characters.

## Events

Event         | Description
---           | ---
`onsomething` | Triggers when something happens.

## History

For detailed changelog, check [Releases](https://github.com/emiljohansson/x-random-string/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
