# Ceangal Hello

The app `ceangal new` makes: a counter, built for the web, macOS, iOS,
Android, Windows and Linux from one Almide source with
[ceangal](https://github.com/almide-graphics/ceangal2).

```sh
ceangal run macos      # or web, linux, windows, ios, android
ceangal build android  # store packages: web macos ios android linux windows
```

`ceangal.toml` describes the app; CI builds every platform with the
framework's reusable workflow (`.github/workflows/app.yml`).
