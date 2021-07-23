```python
class BlueGoldfield:

    def __init__(self) -> None:
        
        self.username = "BlueGoldfield"
        self.name = "Rafael Zaccaro"
        self.occupation = "University student"
        self.location = "Brazil"
        self.languages = {
            'Programming': {
                'frontend': ['HTML', 'CSS', 'JavaScript'],
                'backend': ['Python', 'NodeJS', 'PHP'],
                'database': ['MySQL', 'SQLite3', 'MongoDB'],
                'mobile': ['Dart/Flutter'],
                'other': ['Java', 'C', 'C#']
            },
            'Human': {
                'Portuguese': 'First language', 
                'English': 'Fluent', 
                'German': 'Beginner'
            }
        }
        self.tools = {
            'OS': ['Windows', 'Linux'],
            'IDE/Code Editor': ['VSCode', 'NetBeans', 'Visual Studio 2017'],
            'Community': ['Discord', 'GitHub']
        }
        self.contact = {
            'Twitter': '@BlueGoldfield',
            'Discord': 'Rafaeł#9171',
            'E-Mail': 'rafael.zaccaro2@gmail.com'
        }
    
    def say_hello(self) -> str:
        return "Hello there! Welcome to my GitHub and thank you for dropping by!"

me = BlueGoldfield()
me.say_hello()
```
