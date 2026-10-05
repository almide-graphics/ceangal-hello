# Ceangal Hello

The app `ceangal new` makes: a counter, built for the web, macOS, iOS,
Android, Windows and Linux from one Almide source with
[ceangal](https://github.com/almide-graphics/ceangal2).

```sh
curl -fsSL https://raw.githubusercontent.com/almide-graphics/ceangal2/main/install.sh | sh
ceangal dev            # http://localhost:8000, rebuilt and reloaded on save
ceangal dev macos      # the desktop app, restarted on save (or linux / windows)
ceangal run ios        # or android
ceangal build android  # store packages: web macos ios android linux windows
```

`ceangal.toml` describes the app; CI builds every platform with the
framework's reusable workflow (`.github/workflows/app.yml`). The
[guide](https://github.com/almide-graphics/ceangal2/blob/main/docs/guide/README.md)
covers the rest.
