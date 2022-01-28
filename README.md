#!/usr/bin/python
# -*- coding: utf-8 -*-


class PythonDeveloper:

    def __init__(self):
        self.name = "Vlad Morkovnik"
        self.role = "Python Developer"
        self.language_spoken = ['EN', 'CZ', 'RU']
        self.skills = ['Python 3.9', 'Linux', 'Oracle DB', 'GIT', 'REST API', 'WLS']
        self.currently_learning = 'Microsoft Azure'
        self.email_me = 'morkovnik.vlad@gmail.com'

    def say_hi(self):
        print("Hi! Nice to meet you, hope you find some of my work interesting.")


me = PythonDeveloper()
me.say_hi()
