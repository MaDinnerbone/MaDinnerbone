#### A Program About Time
Language:Python

    import turtle
    import datetime
    import time

    time_now=datetime.datetime.now().strftime('%Y/%m/%d %H:%M:%S')
    x=turtle.Turtle()
    x.speed(10)
    x.up()
    x.goto(-230,0)
    x.write("time:"+time_now,font=("Arial",30))
    x.goto(300,300)
    time.sleep(1)
