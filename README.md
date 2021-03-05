### @explicitHints true

# Turtle Logo - Lesson #2

## Turtle Logo - Lesson #2 @unplugged
**Making the Turtle Move.**

In this lesson you will make your **Turtle** move.
![Hello, World!](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-lesson2/raw/main/assets/move_screenshot.png)

## Step 1
Once again, all our programs begin with an ⇢``on start``⇠ block. Then you need to add the **Turtle** using the ⇢``show turtle``⇠ block.
```blocks
turtle.showTurtle()
```

## Step 2
To move the **Turtle** you will use the ⇢``move turtle forward 25 steps``⇠ block and place it inside the ⇢``on start``⇠ block after the ⇢``show turtle``⇠ block.
```blocks
turtle.showTurtle()
turtle.moveTurtleDirection(TurtleDirection.Forward, 25)
```

## Step 3
** Try it Out**

Notice the number 25 in the block. The number can be changed to move the **Turtle** a different distance. Try moving the **Turtle** some different distances.
```blocks
turtle.showTurtle()
turtle.moveTurtleDirection(TurtleDirection.Forward, 75)
```

## Step 4
You might have also noticed the the word "forward" is actually a menu. If you select it, you have the option to go forwards or backwards.
```blocks
turtle.showTurtle()
turtle.moveTurtleDirection(TurtleDirection.Backward, 25)
```

## Step 5
** Try it Out**

Try moving the **Turtle** some different distances backwards.
```blocks
turtle.showTurtle()
turtle.moveTurtleDirection(TurtleDirection.Backward, 75)
```

## Step 6
Success!

You can now make the **Turtle** move forwards and backwards.

## Step 7
**Your Turn**

Get the turtle to move and then say, "I just moved!"

## Step 8
Done.

You have successfully completed your second lesson in Turtle Logo.
