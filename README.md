### @explicitHints true

# Omarillo Logo - Lesson #5

## Omarillo Logo - Lesson #5 @unplugged
**Making the Omarillo's Pen Move Up and Down.**

In this lesson you will make the **Omarillo** lift it's pen up and down.
![color](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-lesson5/raw/main/assets/pen_up_screenshot.png)

## Step 1
** Follow Along**

Once again, all our programs begin with an ⇢``on start``⇠ block. Then you need to add the **Omarillo** using the ⇢``show omarillo``⇠ block.
```blocks
omarillo.showOmarillo()
```

## Step 2
** Follow Along**

Previously we have learned how to make the **Omarillo** move around the game console and leave a trail. But sometimes we might not want to leave a trail, then what?
```blocks
omarillo.showOmarillo()
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
```

## Step 3
** Follow Along**

To solve this problem you use the ⇢set omarillo's pen up⇠ block. As the name implies, it lifts the **Omarillo's** pen up
```blocks
omarillo.showOmarillo()
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
omarillo.pen(OmarilloPenMode.Up)
```

## Step 4
** Follow Along**

Once the pen is up, if you move again no trail will be left behind.
```blocks
omarillo.showOmarillo()
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
omarillo.pen(OmarilloPenMode.Up)
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
```

## Step 5
** Follow Along**

You can also use the ⇢set omarillo's pen up⇠ block again, and change the "up" to "down" to make it leave a trail again.
```blocks
omarillo.showOmarillo()
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
omarillo.pen(OmarilloPenMode.Up)
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
omarillo.pen(OmarilloPenMode.Down)
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
```
## Step 6
** Try it Out**

Now try moving the **Omarillo** some different distances, different directions, turning, changing color and lifting it's pen up and down.
```blocks
omarillo.showOmarillo()
omarillo.setPenColor(8)
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
omarillo.turnOmarilloDirectionByDegrees(OmarilloTurnDirection.Right, 90)
omarillo.pen(OmarilloPenMode.Up)
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 50)
omarillo.turnOmarilloDirectionByDegrees(OmarilloTurnDirection.Left, 90)
omarillo.setPenColor(7)
omarillo.pen(OmarilloPenMode.Down)
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
```

## Step 7
**Success!**

You can now get the **Omarillo** to lift the pen up and down.

## Step 8
**Your Turn**

Get your **Omarillo** to:
- move
- change its trail color
- turn
- lift the pen up
- move again
- put the pen down
- move again
- then say, "I can lift my pen!"

## Step 9
**Done**

You have successfully completed your fifth lesson in Omarillo Logo.

```ghost
omarillo.say("Hello, World!")
```
