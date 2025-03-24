&nbsp;<div align="center">
  [![Spotify](https://novatorem.vercel.app/api/spotify?background_color=0d1117&border_color=ffffff)](https://open.spotify.com/user/omnitenebris)
</div>

---

```python

class FirasKahlaoui:
    def __init__(self):
        self.name = "Firas Kahlaoui"
        self.username = "FirasKahlaoui"
        self.location = "Ariana, Tunisia"
        self.twitter = "@firas_kahlaoui"
        self.web = "https://firaskahlaoui.pages.dev"
        self.about = (
            "Hello! I'm Firas Kahlaoui, a passionate Computer Science student specializing in Big Data. "
            "As a data scientist, I thrive on exploring new technologies and enhancing my programming skills."
        )

        self.skills = [
            {"Skill": "Big Data Analysis", "Description": "Extracting insights from large datasets."},
            {"Skill": "Machine Learning", "Description": "Building and optimizing predictive models."},
            {"Skill": "Web Scraping", "Description": "Collecting data from various online sources."},
            {"Skill": "Web Development", "Description": "Designing user-friendly web applications."}
        ]

    def __str__(self) -> str:
        skills_formatted = "\n".join(
            [f"- **{skill['Skill']}**: {skill['Description']}" for skill in self.skills]
        )
        return (
            f"## About Me\n\n"
            f"{self.about}\n\n"
            f"### Skills & Expertise:\n{skills_formatted}\n"
            f"📍 Location: {self.location}\n"
            f"🔗 Website: {self.web}\n"
            f"🐦 Twitter: {self.twitter}\n"
            f"👤 Username: {self.username}"
        )

    def display_skills(self) -> str:
        """Returns a formatted string of skills and descriptions."""
        return "\n".join(
            [f"{skill['Skill']}: {skill['Description']}" for skill in self.skills]
        )


if __name__ == '__main__':
    me = FirasKahlaoui()
    print(me)

```

---

## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="35"><b> Github Stats </b>

<p align="center">
  <!-- Streak Stats -->
  <img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=FirasKahlaoui&theme=dark&hide_border=true&background=000000&stroke=130F40&ring=7A7ADB&fire=2234AE&currStreakLabel=7A7ADB&sideNums=D3D3D3&currStreakNum=7A7ADB&sideLabels=D3D3D3&dates=D3D3D3" />
</p>

<div align="center">
  <!-- GitHub Stats -->
  <a href="https://github.com/FirasKahlaoui/">
    <img src="https://github-readme-stats.vercel.app/api?username=FirasKahlaoui&include_all_commits=true&count_private=true&show_icons=true&line_height=20&title_color=7A7ADB&icon_color=2234AE&text_color=D3D3D3&bg_color=0,000000,130F40" width="450"/>
  </a>
</div>
<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=FirasKahlaoui&theme=github_dark" width="450"/>
</div>

</br>

---

<p align="center">
 <a href="https://github.com/FirasKahlaoui">
  <img src="https://komarev.com/ghpvc/?username=FirasKahlaoui&label=Profile%20views&color=0e75b6&style=flat" alt="FirasKahlaoui" />
 </a>
 <a href="https://github.com/FirasKahlaoui">
  <img src="https://img.shields.io/github/followers/FirasKahlaoui?label=Followers" alt="FirasKahlaoui" />
 </a>
</p>
