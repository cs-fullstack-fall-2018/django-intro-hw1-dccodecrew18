# django-intro-hw1





Create a new route and paste it below. Create a blue-or-red route that takes an argument of blue or red. If it's blue, write "Sky". If it's red, write "Fire". If it's anything else write "ERROR".



newfile.py


def purple (request,blue,red):
  if blue:
    print ("Sky")
  else if red:
    print ("Fire")
  else if !red and !blue:
  print"Error"
  
  
  
  
  
  
  urls.py
  
  
  
  path('',newfile.purple,name="purple")
