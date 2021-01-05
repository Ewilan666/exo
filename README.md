# exo

def sum(nbr1, nbr2):
  res = nbr1 + nbr2
  return res

print(sum(5,8))


def oppose(x):
  return -x
print(oppose(6))


def waitInteger(nbr):
  if type(nbr) == int:
    print(True)
  else:
    print(False)

waitInteger(7)
waitInteger("lol")

def isBissextile(nbr):
  return nbr % 4 ==0 and nbr % 100 != 0 or nbr % 400 ==0
print(isBissextile(2000))
