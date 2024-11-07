- class Introduction:
    def __init__(self):
        self.skill_level = "noob"
        self.hobbies = ["anime marathons", "YouTube deep dives"]
        self.fuel = {"caffeine": "high", "sleep": "low"}

    def introduce(self):
        print("Hey there! I’m a certified", self.skill_level, "at programming, here to make mistakes and probably write questionable code.")
        print("When I'm not wrestling with error messages, I'm usually deep in", self.hobbies[0], "or my go-to,", self.hobbies[1], ".")
        print("Fueled by", self.fuel["caffeine"], "caffeine and", self.fuel["sleep"], "sleep, so if I seem extra enthusiastic at 3 a.m., you know why!")
        print("Here to learn, laugh, and maybe actually debug something—let's see what happens!")

me = Introduction()
me.introduce()
  

<!---
ByteShogun/ByteShogun is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
