# bluetooth-menu
A Linux system tray app to display bluetooth devices and allow to connect/disconnect

## build
```
go get -u ./...
go build .
```

## running
```
./bluetooth-menu
```
## troubleshooting
If you see an error for `version GLIBCXX_3.4.29 not found` you can install `libgtk-4-dev`
You can then set the `GTK_PATH` env to `/usr/lib/x86_64-linux-gnu/gtk-4.0`