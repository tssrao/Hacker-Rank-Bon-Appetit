#!/bin/python3

import math
import os
import random
import re
import sys

# Complete the bonAppetit function below.
def bonAppetit(bill, k, b):
    ba=0
    for i in range(len(bill)):
        ba += bill[i]
    ba = ba-bill[k]
    bactual = ba/2
    if bactual == b:
        x = 'Bon Appetit'
    else:
        x = int(b-bactual)
    print(x)


if __name__ == '__main__':
    nk = input().rstrip().split()

    n = int(nk[0])

    k = int(nk[1])

    bill = list(map(int, input().rstrip().split()))

    b = int(input().strip())

    bonAppetit(bill, k, b)
