# Hi there, I'm Leon - aka tr3x <img width="30px" height="30" src="https://github.com/SatYu26/SatYu26/raw/master/Assets/Hi.gif" />


```python

from datetime import datetime

class ComputerScienceStudent:

    def __init__(self):
        self.name = 'Leon Burghardt'
        self.age = datetime.now().year - 2004
        self.complexity = 'O(n!)'
        self.role = 'Computer Science student'
        self.langs_spoken = ['de_DE', 'en_US']

    def introducing_myself(self):
        for attribute, value in vars(self).items():
            print(f"{attribute}: {value}")


if __name__ == "__main__":
    i_am = ComputerScienceStudent()
    i_am.introducing_myself()

```

