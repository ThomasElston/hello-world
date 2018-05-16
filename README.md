# hello-world
In Class Github discussion

#Random NUmber Generator
from random import *
line = ""
while True:
  for letter in range(1, 50):
    letter = randint(1, 9)
    line += str(letter)
  print line
  line = ""
