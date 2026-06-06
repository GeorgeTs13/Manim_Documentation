# graphs

- This is just a graph


from manim import *

class *Scene_name*(Scene):
    def construct(self):
        a = Axes(x_range=[-5, 5], y_range=[-5, 5])
        self.add(a)

        p = a.plot(lambda x: 0.5*x**2, x_range=[-4, 4], color=RED)
       self.play(Create(p))


