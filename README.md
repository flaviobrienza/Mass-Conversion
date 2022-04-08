# Mass-Conversion
How to convert a kg to g and viceversa.
# MASS CONVERTER
def conversion():
    while True:
      x = input('Insert a value: ') 
      y = input('g or kg? ') 
      choice = float(x) 


   
      if y == 'g':
        solution = choice / 1000
        return solution,'kg'
      if y == 'kg':
        solution = choice * 1000
        return solution,'g'     
      else:
          print ('Please enter a valid option. Choose between "g" or "kg"')
          continue

print(conversion()) 
