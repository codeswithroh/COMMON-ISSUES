# Solving leaflet issues

```
"leaflet": "^1.8.0",
"react-leaflet": "^3.0.0",
"@react-leaflet/core": 1.1.1

```

1) check the package.json to look for duplicate entries of any packages
2) there could be two versions of a similar package needed
3) according to that vary your package version


## Commom error

```
react-dom.development.js:11340 Uncaught Error: No context provided: useLeafletContext() can only be used in a descendant of <MapContainer>

```