# Using the plot command and the Inputs

## Introduction
Please make sure you know the LED co-ordinates on the micro:bit

## Step 1
When the micro:bit starts ``||basic:Clear the Screen||`` and using the ``||led:plot||`` command switch on the LED at the center of
the microbit.


```blocks
basic.clearScreen()
led.plot(2, 2)
```

## Step 2

When the ``||Input:A button||`` is pressed ``||basic:Clear the Screen||`` and using the ``||led:plot command||`` draw a diagonal line starting from top left to the
bottom right - Learn to use the Duplicate command by - Right click on the block and 
select duplicate

```blocks
input.onButtonPressed(Button.A, function () {
    basic.clearScreen()
    led.plot(0, 0)
    led.plot(1, 1)
    led.plot(2, 2)
    led.plot(3, 3)
    led.plot(4, 4)
})
```


## Step 2

When the ``||Input:A button||`` is pressed ``||basic:Clear the Screen||`` and using the ``||led:plot command||`` draw a diagonal line starting from top left to the
bottom right - Learn to use the Duplicate command by - Right click on the block and 
select duplicate

```blocks
input.onButtonPressed(Button.A, function () {
    basic.clearScreen()
    led.plot(0, 0)
    led.plot(1, 1)
    led.plot(2, 2)
    led.plot(3, 3)
    led.plot(4, 4)
})
```



## Step 3

When the ``||Input:B button||`` is pressed ``||basic:Clear the Screen||`` and using the ``||led:plot command||`` draw a diagonal line starting from top right to the
bottom left - Learn to use the Duplicate command by - Right click on the block and 
select duplicate

```blocks
input.onButtonPressed(Button.B, function () {
    basic.clearScreen()
    led.plot(4, 0)
    led.plot(3, 1)
    led.plot(2, 2)
    led.plot(1, 3)
    led.plot(0, 4)
})
```

## Step 4

When the ``||Input:A+B button||`` is pressed ``||basic:Clear the Screen||`` and using the ``||led:plot command||`` draw a Z - Learn to use the Duplicate command by - Right click on the block and 
select duplicate

```blocks
input.onButtonPressed(Button.AB, function () {
    basic.clearScreen()
    led.plot(4, 0)
    led.plot(3, 0)
    led.plot(2, 0)
    led.plot(1, 0)
    led.plot(0, 0)

    led.plot(4, 0)
    led.plot(3, 1)
    led.plot(2, 2)
    led.plot(1, 3)
    led.plot(0, 4)

    led.plot(4, 4)
    led.plot(3, 4)
    led.plot(2, 4)
    led.plot(1, 4)
    led.plot(0, 4)

})
```    

## Step 5

When ``||Input:Shaked||`` using the ``||led:plot command||`` draw your own design  - Learn to use the Duplicate command by - Right click on the block and 
select duplicate

```blocks
input.onGesture(Gesture.Shake, function () {
    basic.clearScreen()
    led.plot(0, 0)
    led.plot(4, 0)
    led.plot(2, 2)
    led.plot(0, 4)
    led.plot(4, 4)


})
```  

## Step 6

Congratulations ! You have completed the task
