# Swapping-values-of-two-variables-using-XOR-bitwise-operator


# Description

This repository contains a simple Python program demonstrating how to swap the values of two variables using the XOR bitwise operator. This method is efficient and doesn’t require a temporary variable.

# How It Works

The XOR operator (`^`) can be used to swap two integers without using extra space.

**Logic Used**

a = a ^ b

b = a ^ b

a = a ^ b

Here’s what happens step by step:

a = a^b → stores the XOR of a and b in a

b = a^b → becomes original a

a = a^b → becomes original b
