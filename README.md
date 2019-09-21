# Happy and Sad face activity
// Press A for a smile and press B for a frown
input.onButtonPressed(Button.A, function () {

    basic.showLeds(`
. . . . .
# . . . #
. . . . .
# . . . #
. # # # .
`)
})

input.onButtonPressed(Button.B, function () {

    basic.showLeds(`
. . . . .
# . . . #
. . . . .
. # # # .
# . . . #
`)
})


