#!/bin/python

import math
import os
import random
import re
import sys



if __name__ == '__main__':
    n = int(raw_input().strip())
    if n%2==0:
        
        if n>2 and n<5:
            sys.stdout.write(str("Not Weird")) 
        elif n>6 and n<=20:
            sys.stdout.write(str("Weird")) 
        elif n>20:
            sys.stdout.write(str("Not Weird")) 
    else :
        sys.stdout.write(str("Weird")) 