# MOBJECT

- Mobject is an object inside your "canvas"
- For example a square is "Square()" and if i wanted to add it on my scene i would do it as this:

from manim import *

class *Scene_name*(Scene):
    def construct(self):
        s = Square()

        self.play(Create(s))

- The self.play command adds to our canvas

- Objects have also parametres/attributes for example:

from manim import *

class *Scene_name*(Scene):
    def construct(self):
        s = Square()

        s.fill_opacity = 1
        s.set_color(RED)
        s.scale(0.5)

        self.play(Create(s))

