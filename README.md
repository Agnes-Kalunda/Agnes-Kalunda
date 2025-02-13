#!/usr/bin/python
# -*- coding: utf-8 -*-

class SoftwareEngineer:
    def __init__(self):
        self.name = "Agnes"
        self.role = "Software Engineer"
        self.language_spoken = ["Swahili", "English"]

    def say_hi(self):
        print("Thanks for dropping by; hope you find some of my work interesting.")


additional_info = {
    "code": ["Javascript", "Reactjs", "Typescript", "HTML", "CSS", "Python", "Django", 
             "Flask", "FASTAPI", "Postgres", "PHP", "Laravel", "Vue.js"],
    "tools": ["stack overflow", "Node", "Styled-Components", "Github", "Music"],
    "techCommunities": {
        "Manager": "my own management",
        "Building stuff": "Writing production code.",
    },
}


me = SoftwareEngineer()
me.say_hi()


me.additional_info = additional_info

print(me.additional_info)
