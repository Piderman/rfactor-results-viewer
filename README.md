# rfactor-results-viewer

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Run your unit tests
```
npm run test:unit
```

#### Features
- [ ] test
- [ ] view race results
- [ ] test
- [ ] test
- [ ] Graph driver position change over race
- [ ] Compare two driver sector times
- [ ] Compare two driver lap times
- [ ] incident report

#### Notes

- what does `et=` mean in streams/driver data
- point in stream score is sector timing


## Time format of XML

et: event time?

s[1-3]: sector time in seconds
p: position on grid
fuel: fraction of tank remaining

```xml
  <Lap num="2" p="13" et="163.6947" s1="54.6660" s2="47.9458" s3="19.1359" fuel="0.322">121.7477</Lap>
```

`BestLapTime` in seconds, convert to mm:ss.SSS
