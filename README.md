```python
from typing import Tuple, List, Dict, Set

class Stas:
    pass

class Attributes(Stas):
    def contact(self) -> List[str]:
        telegram = ["macronx", "stdoq"]
        return telegram

    def life(self) -> Tuple[List[str], int]:
        langs = ['Russian', 'English']
        age   = 22
        return langs, age

    def tools(self) -> Dict[str, List[str]]:
        return {
            'devops'       : ['docker', 'k8s', 'minikube', 'ansible', 'orbstack'],
            'observability': ['grafana', 'prometheus', 'loki'],
            'dev'          : ['git', 'gitkraken', 'tmux', 'neovim', 'nginx'],
            'ai'           : ['ai_agents', 'openclaw', 'n8n'],
            'databases'    : ['postgres', 'sqlite'],
            'lab'          : ['containerlab', 'postman'],
        }

    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str], Dict[str, Set[str]]]:
        langs = {
            'expert'      : ['python'],
            'intermediate': ['c', 'lua', 'bash'],
            'learning'    : ['go', 'rust', 'assembly']
        }
        specialities = ['Backend', 'NetOps', 'DevOps', 'SRE', 'Frontend']
        ide          = ['VS_Code', 'PyCharm', 'Clion', 'Sublime']
        pc           = {
            'MacOS'       : {'macbook air m4'},
            'Ubuntu_22_04': {'hp'}
        }
        return langs, specialities, ide, pc
```
