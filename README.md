```python
from github.profile import ReadMe
class ethos ( ReadMe ) :
    def __init__ ( self ) :
        self.username  = "Technical Development"
        self.location  = "Purwokerto"
        self.languages = [ "PHP", "HTML", "Javascript", "CSS", "Phyton" ]
    def about ( self ) :
        print( f"Hi, I'm {self.username}." )
me = ethos()
me.about()
```
