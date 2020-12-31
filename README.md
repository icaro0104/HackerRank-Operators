# HackerRank-Operators

import math
import os
import random
import re
import sys

meal_cost = float(input())
tip_percent = int(input())/100
tax_percent = int(input())/100

tip_cost = meal_cost * tip_percent
tax_cost = meal_cost * tax_percent
final_cost = int(round(tip_cost + tax_cost + meal_cost))

print(final_cost)
