# electron-digital-art-app
## Get started
### Prepare .env file
```
cp .env.example .env
```
Set value to `API_URL` in `.env` file.

### Install dependencies
```
yarn install
```

### Run the app
```
yarn dev
```

## Build App
### For Raspberry Pi
```
yarn package-pi
```

`/dist/*.AppImage` will be generated and it is the app for Raspberry Pi.

### For Mac
```
yarn package-mac
```

### For Windows(64bit)
```
yarn package-win
```

### For Windows(32bit)
```
yarn package-win32
```
