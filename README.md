# Parity Wallet Example
    This is a simple exmple to show how fallback function may cause vulnerabiliy

## The problem
    if user call the contract with a function name that doesn't exisit within in the contract, will fall into the fallback function.
    If the user call the wallet contract with a function which only exisit in the library only.
    The function call will delegate to call the library.
