```python
from typing import Tuple, List, Dict

class Stas:
    pass

class Attributes(Stas):
    def contact(self) -> Tuple[str, str, str]:
        telegram = "macronx"        
        return telegram

    def life(self) -> Tuple[List[str], int]:
        langs = ['Russian', 'English']
        age   = 20
        return langs, age
    
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str], Dict[str]]:
        langs = {
            'expert'      : ['python'],
            'intermediate': ['c', 'c++'],
            'learning'    : ['go', 'rust', 'lua', 'bash', 'assembly']
        }
        specialities  = ['Backend reverse engineering', 'Network engineering',]
        ide           = ['VS_Code', 'PyCharm', 'Clion']
        pc            = {
            'MacOS': {
                'macbook air m2'
            },
            'Ubunu_22_04': {
                'hp'
        }
        return langs, specialities, ide, pc
```
