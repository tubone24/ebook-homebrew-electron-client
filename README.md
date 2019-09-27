# ebook-homebrew-electron-client

## Run

```
npx electron ./src
```

## Deploy to binary file

For Mac
```
npx electron-packager src FirstApp --platform=darwin --arch=x64 --overwrite
```

For Windows
```
npx electron-packager src FirstApp --platform=win32 --arch=x64 --overwrite
```
