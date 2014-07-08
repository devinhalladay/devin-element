# &lt;hn-button&gt;

Web Component wrapper for [Segment.io's Hacker News Button](http://www.hn-button.com/) using Polymer.

> Maintained by [Devin Halladay](https://github.com/devinhalladay).

## Demo

![Hacker News Button Button](http://f.cl.ly/items/361j1H0e0E1s0H190h07/Image%202013-09-09%20at%203.05.06%20PM.png)

> [Check it live](http://devinhalladay.github.io/hn-button).

## Usage

1. Import Web Components' polyfill:

  ```html
  <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
  ```

2. Import Custom Element:

  ```html
  <link rel="import" href="src/hn-button.html">
  ```

3. Start using it!

  ```xml
  <hn-button></hn-button>
  ```

## Options

Attribute | Options       | Default                             | Description
---       | ---           | ---                                 | ---
`title`   | *string*      | `Show HN: The Hacker News Button`   | The title of the Hacker News post
`count`   | `horizontal`, `vertical` | `horizontal`             | The direcition of the button count
`href`    | *string*      | `http://www.hn-button.com/`         | The URL on the Hacker News post
`height`  | *int*         | `20`                                | The height of the button
`width`   | *int*, `auto` | `auto`                              | The width of the button

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request!

## Roadmap

* Add support for the [Style attribute](http://www.hn-button.com/)

## History

* v0.0.2 September 10, 2013
  * Formatted source to fit customelement.io standards.
* v0.0.1 September 9, 2013
  * Started project. Inital release.

## License

[MIT License](http://opensource.org/licenses/MIT)
