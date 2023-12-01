# Plus-Minus
Tugas Plus Minus 
# Plus Minus

Nama : M Huda Noor Setyawan
Nim : 23422035
Kelas : TIF 22A

# Kasus 0
phyton 3

import math
import os
import random
import re
import sys


def plusMinus(arr):
    n = len(arr)
    positive_count = sum(1 for num in arr if num > 0)
    negative_count = sum(1 for num in arr if num < 0)
    zero_count = n - positive_count - negative_count

    positive_ratio = positive_count / n
    negative_ratio = negative_count / n
    zero_ratio = zero_count / n

    # Print the ratios with 6 decimal places
    print("{:.8f}".format(positive_ratio))
    print("{:.8f}".format(negative_ratio))
    print("{:.8f}".format(zero_ratio))

    # Sample Input
    arr = [-4, 3, -9, 0, 4, 1]

    # Function call
    plusMinus(arr)


# Keluaran saya
0,500000
0,333333
0,166667

# kasus 1

import math
import os
import random
import re
import sys


def plusMinus(arr):
    n = len(arr)
    positive_count = sum(1 for num in arr if num > 0)
    negative_count = sum(1 for num in arr if num < 0)
    zero_count = n - positive_count - negative_count

    positive_ratio = positive_count / n
    negative_ratio = negative_count / n
    zero_ratio = zero_count / n

    # Print the ratios with 8 decimal places
    print("{:.8f}".format(positive_ratio))
    print("{:.8f}".format(negative_ratio))
    print("{:.8f}".format(zero_ratio))

    # Sample Input
    arr = [1, 2, 3, -1, -2, -3, 0, 0]
    
    # Function call
    plusMinus(arr)

# Keluaran saya
0,37500000
0,37500000
0,25000000

