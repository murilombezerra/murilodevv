## Murilo M. Bezerra: Computer science student, Back-end Developer

```python
import json
from datetime import datetime

data_inicial = datetime(2000, 1, 15)  # Data inicial específica
data_final = datetime.now()  # Data atual
diferenca = data_final - data_inicial  # Calcula a diferença entre as datas
anos = diferenca.days // 365  # Calcula o número de anos
meses = (diferenca.days % 365) // 30  # Calcula o número de meses

class MuriloMBezerra:
  def __repr__(self):
    return json.dumps({
      'education': {
                    'university': 'Federal University of ABC',
                    'course': 'Science and Technology',
                    'time': '2021-2025'
                   },
      'experience': {
                     'company': 'Logical IT',
                     'position': 'Junior Back-end Developer',
                     'time': f'{anos} years and {meses} months'
                    },
      'code': ['Python', 'Node.js'],
      'database': ['PostgreSQL'],
      'tools': ['FastAPI', 'Linux'],
      'been_at_it_since': 2019
    })
me = MuriloMBezerra()
print(me)
```

[![Linkedin: murilomb](https://img.shields.io/badge/-murilomb-blue?style=round-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/murilomb/)](https://www.linkedin.com/in/murilomb/)
[![GitHub murilodevv](https://img.shields.io/github/followers/murilodevv?label=follow&style=social)](https://github.com/murilodevv)

<div align="center">
  <a href="https://beacons.ai/murilodev">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=murilodevv&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
  <img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=murilodevv&layout=compact&langs_count=16&theme=dark"/>
</div>
  
<!--
**murilodevv/murilodevv** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
-->
