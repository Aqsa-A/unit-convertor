import math
import time

conversions = {
                "mm": {"mm": 1, "cm": 1/10, "m": 1/1000, "km": 1/1000000},
                "cm": {"mm": 10, "cm": 1, "m": 1/100, "km": 1/100000},
                "m":  {"mm": 1000, "cm": 100, "m": 1, "km": 1/1000},
                "km": {"mm": 100000, "cm": 10000, "m": 1000, "km": 1},
              }

def  metric_length (x):
    while x in conversions:
        
    





print ('Hi, what would you like to convert ? the program spuort metric system ')
print ('1.length')
print ('2.weight')

choice = input (" Enter choice (1/2): ")

if choice ==('1' or '2'):
    
    unit1 = input ("Which unit would you like to convert from: ")
    unit2 = input ("Which unit would you like to convert to: ")
    num1 = input ("Enter your value: " )
    
