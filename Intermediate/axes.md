# axes

- To add axes on screen do

from manim import *

class *Scene_name*(Scene):
    def construct(self):
        a = Axes(x_range=[-5, 5], y_range=[-5, 5])
        self.add(a)