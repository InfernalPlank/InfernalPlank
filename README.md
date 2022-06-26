## Welcome

- 🔭 I’m currently working on **RuneLite Plugin Development**.
- 🌱 I’m currently learning **more about Java**.
- 👯 I’m looking to collaborate on **plugins**.
- 💬 Ask me about **anything except the color Fuchsia**.
- ⚡ Fun fact: **water is wet**.

![My GitHub Stats](https://github-readme-stats.vercel.app/api?username=InfernalPlank&show_icons=true&count_private=true&theme=dark)

```py
## Native Modules
from os import system
import sys

## Local Imports
import reader

## A Graceful Dumbass
class InfernalPlank:
    def __init__(self):
        self.variables = {
            'name': 'redacted',
            'age': 'redacted',
            'profession': 'Versatile Integrative Development',
            'spokenLanguages': ['English', 'French', 'Spanish', 'Russian'],
            'codeLanguages': ['HTML', 'PHP', 'JS', 'C/C++', 'C#', 'Python', 'Java', 'Delphi', 'Nim']
        }

    def description(self):
        print('------| InfernalPlank| ------')
        for key, value in self.variables.items():
            if key == "name":
                print(f'Name: {value}')
            elif key == "age":
                print(f'Age: {value}')
            elif key == "profession":
                print(f'Profession: {value}')
            elif key == "spokenLanguages":
                print('Spoken Languages:')
                for language in value:
                    print(f'\t- {language}')
            elif key == "codeLanguages":
                print('Code Languages:')
                for language in value:
                    print(f'\t- {language}')
            else:
                print('Why is this happening?')

    def links(self):
        platforms = {
            'Website': 'redacted',
            'Discord Server': 'redacted'
        }

        print('\n-----| Contact |-----')
        for key, value in platforms.items():
            print(f'{key}: {value}')


if __name__ == '__main__':
    try:
        me = InfernalPlank()
        me.description()
        me.links()
        reader.Mother().finesse()
    except:
        print(f'This is me, but failing.')
        sys.exit(-1)
```
