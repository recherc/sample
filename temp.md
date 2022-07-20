# How to Display Temperature on the Display
## First drag the show number block to the forever loop.
```blocks
basic.forever(function () {
    basic.showNumber(0)
})
```

## Next drag the temperature sensor bubble to the show number block in the forever loop.
```blocks
basic.forever(function () {
    basic.showNumber(input.temperature())
})
```
