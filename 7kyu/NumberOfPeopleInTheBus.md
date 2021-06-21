# Number of People in the Bus

### Solution:

```
var number = function(busStops){
  // Good Luck!
  let gettingOn = 0
  let gettingOff = 0
  let stillOnTheBus
  for(let i = 0; i < busStops.length; i++){
    gettingOn += busStops[i][0]
    gettingOff += busStops[i][1]
    stillOnTheBus = gettingOn - gettingOff
  }
  return stillOnTheBus
}
```

```
var number = function(busStops){
  let stillOnTheBus = 0
  for (let i = 0; i < busStops.length; i++){
    stillOnTheBus += busStops[i][0]
    stillOnTheBus -= busStops[i][1]
  }
  return stillOnTheBus
}
```