# Undeclared Variable Bug in Solidity

This repository demonstrates a common error in Solidity smart contracts: using an undeclared variable.  The `balanceOf` function incorrectly attempts to access a variable named `balances` without properly declaring it. This leads to a runtime error.

The solution demonstrates the correct way to declare and use the `balances` variable to ensure the function operates as intended.