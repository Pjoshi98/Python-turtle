# Python-turtle
This Python turtle library is very easy and fast to understand
import turtle
t=turtle.Turtle()
screen=turtle.Screen()

t.speed(0)
t.begin_fill()
turtle.bgcolor("cyan")
t.end_fill()
t.pensize(5)
t.pen(pencolor="purple")

# draw H
t.left(90)
t.forward(70)
t.penup()
t.goto(0,35)
t.pendown()
t.right(90)
t.forward(30)
t.penup()
t.goto(30,70)
t.pendown()
t.right(90)
t.forward(70)


t.goto(30,0)
t.rt(90)
t.backward(20)
t.rt(110)
t.fd(70)
t.rt(-60)
t.backward(80)
t.fd(35)
t.left(40)
t.fd(50)

# draw P
t.penup()
t.goto(70,70)
t.pendown()
t.right(40)
t.backward(73)
t.rt(120)
t.fd(30)
t.rt(90)
t.fd(30)
t.backward(70)
t.circle(20,150)
t.left(20)
t.fd(20)
t.left(80)
t.fd(40)
t.rt(80)
t.backward(20)

# draw P
t.penup()
t.goto(20,20)
t.rt(90)
t.fd(175)
t.pendown()
t.rt(100)
t.fd(30)
t.backward(70)
t.circle(20,150)
t.left(20)
t.fd(20)
t.left(80)
t.fd(40)
t.rt(80)
t.backward(20)

# draw Y
t.rt(90)
t.penup()
t.fd(60)
t.left(-30)
t.right(30)
t.pendown()
t.fd(80)
t.rt(50)
t.backward(70)
t.fd(110)
t.rt(70)
t.fd(200)

# HOLI Draw
# H draw
t.penup()
t.rt(90)
t.backward(200)

t.left(90)
t.forward(70)
t.penup()
t.rt(70)
t.pendown()
t.fd(100)
t.backward(50)
t.left(90)
t.backward(40)
t.rt(90)
t.backward(50)
t.fd(30)
t.penup()
t.right(40)
t.fd(30)

# Draw O
t.pendown()
for i in range(25):
    t.right(15)
    t.forward(10)

t.penup()
t.left(110)
t.backward(90)
t.rt(50)
t.pendown()

# Draw L
t.fd(80)
t.backward(80)
t.rt(90)
t.fd(50)
t.penup()
t.fd(50)
t.pendown()

# Draw I
t.fd(70)
t.backward(35)
t.right(90)
t.backward(70)
t.left(90)
t.fd(30)
t.backward(90)

# Draw a circle
t.penup()
t.goto(400,300)
t.pendown()
t.begin_fill()
t.pen(pencolor="red")
t.end_fill()
for i in range(80):
    t.rt(90 * 1.01)
    t.fd(200)

t.penup()
t.rt(90)
t.fd(1000)
t.pendown()


# Draw a Clone

c=t.clone()
t.color("purple")
c.color("green")
t.circle(20)
c.circle(30)
for i in range(40,200,50):
    c.circle(i)
t.rt(90)
t.fd(100)
t.penup()
t.fd(200)

t.pendown()

# Draw Square Shape

t.pencolor("black")

for i in range(6):
    c=t.clone()
    t.color("white")
    c.color("black")
    t.circle(20)
    c.circle(30)
    t.begin_fill()
    t.pencolor("magenta")
    
    t.pensize(10)
    t.end_fill()
    t.begin_poly()
    t.fd(200 *1.01)
    t.rt(90*1.01)
    t.end_poly()
    t.rt(10 * 1.15)
    t.fd(200)

t.penup()
t.rt(90)
t.fd(150)
t.pendown()
t.pencolor("black")
t.dot(100)

t.rt(90)
t.rt(90)
t.penup()
t.fd(500)
t.left(50)
t.pendown()

# Draw Pichkari
t.fd(300)
t.left(90)
t.fd(20)
t.rt(90)
t.fd(200)
t.left(90)
t.fd(30)
t.left(90)
t.fd(200)
t.rt(90)
t.fd(30)
t.left(90)
t.fd(300)
t.left(90)
t.fd(20)
t.rt(90)
t.fd(50)
t.rt(90)
t.fd(50)
t.left(90)
t.fd(30)
t.left(90)
t.fd(130)
t.left(90)
t.fd(30)
t.left(90)
t.fd(20)
t.rt(90)
t.fd(50)

# Draw small circle
t.penup()
t.fd(550)
t.pendown()
t.pensize(0)
t.fillcolor("purple")
t.begin_fill()
t.circle(20)
t.end_fill()

# Draw big Circle 1
t.penup()
t.left(90)
t.fd(150)
t.pendown()
t.pensize(0)
t.fillcolor("white")
t.begin_fill()
t.circle(40)
t.end_fill()

# Draw big Circle 2
t.penup()
t.rt(60)
t.fd(100)
t.pendown()
t.pensize(0)
t.fillcolor("brown")
t.begin_fill()
t.circle(40)
t.end_fill()

# Draw big Circle 3
t.penup()
t.left(30)
t.fd(150)
t.pendown()
t.pensize(0)
t.fillcolor("yellow")
t.begin_fill()
t.circle(60)
t.end_fill()

# Draw big Circle 4
t.penup()
t.left(80)
t.fd(325)
t.pendown()
t.pensize(0)
t.fillcolor("indigo")
t.begin_fill()
t.circle(40)
t.end_fill()




    
    








    






















