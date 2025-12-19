<h1>About Me</h1>

```python
class Developer:
    def __init__(self):
        self.name = "Narges Shahmoradi"
        self.degree = "B.Sc. in Computer Science"
        self.role = "Backend Developer (Python)"
        self.mindset = "Always learning, always improving"
        self.current_focus = "Leveling up my current project"

        self.skills = {
            "Languages": {
                "Python": "Intermediate",
                "HTML": "Basic",
                "CSS": "Basic"
            },
            "Frameworks": {
                "Django": "Intermediate"
            },
            "Databases": {
                "PostgreSQL": "Basic"
            },
            "DevOps": {
                "Docker": "Basic",
                "Deployment": "Railway (Free Tier)"
            },
            "Testing": {
                "Unit Testing": "Good understanding"
            },
            "Other": {
                "GIS": "Basic",
                "Git": "Daily usage"
            }
        }

        self.interests = [
            "Backend Development",
            "Clean Code",
            "Testing",
            "Project-based Learning",
            "Improving Software Quality"
        ]

        self.language = {
            "English": "Intermediate"
        }

    def about_me(self):
        return (
            f"Hi, I'm {self.name} 👋\n"
            f"I have a {self.degree} and work mainly with Python and Django.\n"
            f"My current focus is on {self.current_focus}.\n"
            f"My mindset: {self.mindset}."
        )

    def show_skills(self):
        return self.skills

    def get_interests(self):
        return self.interests

if __name__ == "__main__":
    me = Developer()
    print(me.about_me())


)
```
