# stoner-python-programming
class Introduction:
    def __init__(self, aregbe ayatulah adekunle, web designer, hacking, i wanna make it...):
        self.name = aregbe ayatulah adekunle
        self.profession = web designer
        self.hobbies = hacking
        self.goals = i wanna make it...

    def display_intro(self):
        print(f"Hello! My name is {self.aregbe ayatulah adekunle}.")
        print(f"I am a {self.web designer}.")
        print("In my free time, I enjoy hacking:")
        for hobby in self.i wanna make it :
            print(f"- {hacking}")
        print("My goals are:i just wanna make it in life becoming a certified web designer")
        for goal in self.goals:
            print(f"- {goal}")

if __name__ == "__main__":
    # Customize these variables with your information
    name = "aregbe ayatulah adekunle"
    profession = "web designer"
    hobbies = ["Coding", "Graphic Design", "Reading", "Gaming"]  # Add your hobbies here
    goals = ["Master Python", "Contribute to open-source projects", "Build awesome software"]  # Add your goals here

    intro = Introduction(name, profession, hobbies, goals)
    intro.display_intro()
