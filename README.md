# python-review
reviewing some basic python

def main(): 
  list = []
  for num in range (2000,3201):
    if num%7==0 and num%5!=0:
      list.append(num)
  print(",".join(list))
