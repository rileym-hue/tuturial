# How to display the temp
## First drag the show block to the forever loop.
~~~blocks
basic.forever(function () {
    basic.showNumber(0)
})
~~~

## Second drag the temperature sensor bubble to the forever loop.
~~~blocks
basic.forever(function () {
    basic.showNumber(input.temperature())
})
~~~