# react demo

## Project setup
```
npm install
```

## For testing local development
Link to local striven-editor project and make sure react dependency isn't polluted from striven-editor-project

### In striven-editor project dir
```
npm install
```
```
rm -rf node_modules/react
```
```
npm link
```
```
npm run dev
```

### in react demo dir
```
npm install
```
```
npm run link
```
```
npm run serve
```
