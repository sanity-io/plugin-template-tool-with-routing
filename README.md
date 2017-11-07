# plugin-template-tool-with-routing

Plugin template for a tool that includes basic routing.

## Main take-aways

- Tools implement the part named `part:@sanity/base/tool`
- The file that implements the tool part needs to export an object containing properties such as a name, title, icon and React component to render. See `template/index.js`.
- Sanity has a router that can be used to map certain paths to certain actions. See the [router documentation](https://github.com/sanity-io/sanity/tree/master/packages/%40sanity/state-router) for more info.
- A preconfigured Sanity client can be imported from the part `part:@sanity/base/client`. The configuration from the studios `sanity.json` is used.

## Usage

`sanity init plugin https://github.com/sanity-io/plugin-template-tool-with-routing/archive/master.zip`

## License

MIT-licensed. See LICENSE.
