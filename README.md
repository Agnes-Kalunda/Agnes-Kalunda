#!/usr/bin/python
# -*- coding: utf-8 -*-

class SoftwareEngineer:  

    def __init__(self):
        self.name = "Agnes"  
        self.role = "Software Engineer"
        self.language_spoken = ["Swahili", "English"]

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")   

me = SoftwareEngineer()
me.say_hi()
