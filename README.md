# hello

Says hello using greet.

Official HTPL gadget. Version 0.1.0.

## Install

```sh
htpl pm install hello
htpl pm install hello@0.1.0
```

## Usage

```html
<import src="gadgets/hello/gadget.htpl" />
```

## API

- `say_hello(name: string) -> string` — Returns greet.hello(name).

## Dependencies

- `greet ^0.1` — installed automatically with this gadget.

## License

MIT — see [LICENSE](LICENSE).
