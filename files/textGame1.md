# TextGame as of Jan 27

```python
def starting_area():
  print("trees in space")
  while True:
    print('Say "spaceship" or "chainsaw!"')
    choice = input()
    if choice == "spaceship":
      spaceship()
    elif choice == "chainsaw":
      chainsaw()
    else:
      print("Try again!")

def spaceship():
  print("You walk over to the spaceship. It's really big.")
  while True:
    print('Say "enter" or "back"')
    choice = input()
    if choice == "enter":
      enter()
    elif choice == "back":
      starting_area()
    else:
      print("Try again!")

def chainsaw():
  print("You walk over to the chainsaw. It's really sharp.")
  while True:
    print('Say "use" or "back"')
    choice = input()
    if choice == "use":
      use_chainsaw()
    elif choice == "back":
      starting_area()
    else:
      print("Try again!")


def use_chainsaw():
  print("""You attempt to activate and use the chainsaw.
Hmmm, that's strange...
It feels impossible to move""")
  while True:
    print('Say "look" or "back"')
    choice = input()
    if choice == "look":
      look_chainsaw()
    elif choice == "back":
      starting_area()
    else:
      print("Try again!")


def look_chainsaw():
  print("""As you bend down to get a closer look,
The chainsaw turns on, lunges in your direction and kills you. Game over!!""")



## TODO: Write the enter function

starting_area()

```
  
  