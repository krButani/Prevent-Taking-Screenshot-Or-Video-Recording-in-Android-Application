# Prevent Taking Screenshot Or Video Recording in Android Application


- Add Below Code To prevent taking Screenshot

```
if(android.os.Build.VERSION.SDK_INT >= android.os.Build.VERSION_CODES.HONEYCOMB) {
    getWindow().setFlags(WindowManager.LayoutParams.FLAG_SECURE, WindowManager.LayoutParams.FLAG_SECURE);
}
```

- for ios and flutter refer below link
- [flutter](https://github.com/krButani/Prevent-Take-Screenshort-or-Record-Video-in-Application)
- [IOS](https://medium.com/nerd-for-tech/prevent-screenshot-and-video-recording-in-flutter-93839325d66c)
