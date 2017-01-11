# &lt;midori-jsontable&gt;

> Web component that generates plain HTML tables from json sources. [VanillaJS](http://vanilla-js.com/).

![Screenshot](https://raw.githubusercontent.com/midorikocak/midori-jsontable-element/master/screenshot.png)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install midori-jsontable-element --save
```

Or [download as ZIP](https://github.com/midorikocak/midori-jsontable-element/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/midori-jsontable-element/midori-jsontable.html">
    ```

3. Start using it!

    ```html
    <midori-jsontable href="url"></midori-jsontable>
    ```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`href`      | *url*                  | ``             | Should refer to a proper url of json source

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [bower](http://bower.io/) & [polyserve](https://npmjs.com/polyserve):

    ```sh
    $ npm install -g bower polyserve
    ```

2. Install local dependencies:

    ```sh
    $ bower install
    ```

3. Start development server and open `http://localhost:8080/components/hello-world-element/`.

    ```sh
    $ polyserve
    ```

## History

For detailed changelog, check [Releases](https://github.com/midorikocak/midori-jsontable-element/releases).

## License

[MIT License](http://webcomponentsorg.mit-license.org/) © MynameisMidori.com
