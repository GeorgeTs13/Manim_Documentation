# Scenes 

- Scene is like your empty canvas and you can create it in foy project folder containing a ".py" file, in that file to get a scene you must write:


from manim import *

class *Scene_name*(Scene):
    def construct(self):

        .....


## You can preview it with 2 ways. 
- In your project folder open a terminal and type "manim -pql *filename.py* *scenename* which extracts a low quality (-pql) mp4 file with your animation if you want 1080p run -pqh instead of pql or if you want 4k do -pqk

- Or in vscode press that play-like button with the green circle that not only previews the file but does the equivalent of manim -pqh *filename.py* *scenename*