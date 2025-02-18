# TypeError: Cannot read properties of undefined (reading 'length')

This repository contains a simple JavaScript example demonstrating a common error: attempting to access the `length` property of an undefined variable.

## The Bug

The `foo` function attempts to return the length of the input `x`. However, it does not handle the case where `x` is `undefined`.  This results in a `TypeError` when the code attempts to access `x.length`.

## The Solution

The solution adds a check for `undefined` before attempting to access `x.length`, returning 0 in that case.