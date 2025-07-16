```sh-session
$ wasm-pack build --target web
$ python -m http.server
```
`canvas` is 640x360, but it is resized larger:

<img width="543" height="153" alt="Screenshot 2025-07-16 at 2 40 14 PM" src="https://github.com/user-attachments/assets/0f68d246-eb59-454f-94d5-e9bc435826f4" />

See https://github.com/bevyengine/bevy/issues/20164
