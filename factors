#!/usr/bin/python3
from sys import argv
import random
"""Factorize as many numbers as possible into a product of 2 smaller nums"""
def generator(number):
        """Takes the number and factorize it into procuct of two small numbers"""
    largest_number = random.getrandbits(128)
    for i in range(2, largest_number):
        if number % i == 0:
            print("{}={}*{}".format(number, int(number/i), i))
            return
def factors(filename):
        """read_file and prints them out"""

        with open(filename, encoding="utf-8") as my_file:
            for i in my_file.readlines():
                n = int(i)
                result = generator(n)

if __name__ == "__main__":
    factors(argv[1])
