import turtle
ekran = turtle.Screen()
ekran.title("Har xil rangli kvadrat")
ekran.bgcolor("white")
chizma = turtle.Turtle()
chizma.speed(5)

ranglar = ["red", "blue", "green", "yellow"]
for i in range(4):
    chizma.color(ranglar[i])
    chizma.forward(100)
    chizma.left(90)
chizma.hideturtle()
ekran.mainloop()
