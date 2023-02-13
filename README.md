### Hello 👋

```python
from dataclasses import dataclass, field


@dataclass(frozen=True)
class SoftwareEngineer:
    name: str = "Mounir Messelmeni"
    role: str = "Software Engineer and Architect"
    language_spoken: list[str] = field(default_factory=lambda: ["ar", "en", "fr", "de"])
    skills: list[str] = field(
        default_factory=lambda: [
            "Python",
            "Django",
            "Postgresql",
            "Docker",
            "Kubernetes",
            "ArgoCD",
            "AWS",
            "Ansible",
            "Git",
            "Linux",
            "Angular",
            "Typescript",
            "Flutter",
            "Gitlab CI",
            "Github Actions",
        ]
    )
    location: str = "Stuttgart, Germany"
    contact_email: str = "messelmeni.mounir@gmail.com"

    def say_hi(self):
        print(f"Thanks for dropping by, feel free to contact me via email! {self.contact_email}")


me = SoftwareEngineer()
me.say_hi()

```

## 📝 Blogs

- Personal website and blog: https://blog.mounirmesselmeni.de

## 🏆 GitHub Trophies

[![trophy](https://github-profile-trophy.vercel.app/?username=mounirmesselmeni&theme=nord&column=7)](https://github.com/ryo-ma/github-profile-trophy)


## 🗂️ Highlighted Projects

<a href="https://github.com/mounirmesselmeni/django-highlightjs">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=mounirmesselmeni&repo=django-highlightjs&show_icons=true&line_height=27&title_color=6aa6f8&text_color=8a919a&icon_color=6aa6f8&bg_color=22272e" alt="django-highlightjs" />
</a>

## &#x1f4c8; Github stats

[![Mounir's GitHub stats](https://github-readme-stats.vercel.app/api?username=mounirmesselmeni)](https://github.com/anuraghazra/github-readme-stats)
