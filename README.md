```python
from typing import Tuple, List, Dict

class Stas:
    pass

class Attributes(Stas):
    def contact(self) -> Tuple[List[str]]:
        telegram = ["macronx", "stdoq"]         
        return telegram

    def life(self) -> Tuple[List[str], int]:
        langs = ['Russian', 'English']
        age   = 22
        return langs, age
    
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str], Dict[str]]:
        langs = {
            'expert'      : ['python'],
            'intermediate': ['c'],
            'learning'    : ['go', 'rust', 'lua', 'bash', 'assembly']
        }
        specialities  = ['Backend', 'NetOps', 'DevOps', 'SRE', 'Frontend']
        ide           = ['VS_Code', 'PyCharm', 'Clion']
        pc            = {
            'MacOS': {
                'macbook air m2'
            },
            'Ubuntu_22_04': {
                'hp'
        }
        return langs, specialities, ide, pc
```
