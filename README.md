# console-mixer

No-nonsense utility converting youtube/soundcloud/bandcamp links to iframes via
the browser console, _as used during Disconomics' quarantine series_.

## How to run this thing

- `git clone` this repo, `cd` into it
- boot up server e.g.

```
$ npm i -g http-server
$ http-server -p 9999

# OR
$ python3 -m http.server 9999
```

- open up http://localhost:9999/
- open console (e.g with `<ctrl-alt-j>`)
- use `addIFrame` and/or `pasteIFrame` to add content
- start mixing !

![demo](demo.gif)

## License

[MIT](./LICENSE)
