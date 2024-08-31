## Hi there 👋

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...

  
## Who i am ?

```py
from Univers.Earth import Human

class MehdiSameny(Human):
  signal_language = 'python'

    def __init__(self):
        super().__init__(self)
        self.fname = 'Mehdi'
        self.family = 'Sameni'
        self.age = 37
        self.university = 'Iran, Tehran, Islamic Repoblic'

    def run(self):
        while True:
            x, r = self.calculateXR(1)
            arc = self.arc1
            if arc.direction:
              spanAngle = arc.startAngle-arc.fixedStartAngle+arc.spanAngle
            else:
              spanAngle = 360-(arc.startAngle-arc.fixedStartAngle)
            if spanAngle < 1/16:
              spanAngle = 1/16
            self.painter.drawArc(int(x), int(x), int(r), int(r), -(arc.spacer+arc.startAngle)*16, int(-spanAngle*16))
            
            x, r = self.calculateXR(5)
            self.painter.drawArc(int(x), int(x), int(r), int(r), -(arc.spacer+arc.startAngle)*16, int((360-spanAngle)*16))

```
