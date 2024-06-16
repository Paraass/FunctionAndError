# Function And Error
This `Error` smart contract is designed to demonstrate various error handling mechanisms in Solidity, including `require`, `assert`, and `revert`. This contract also includes basic functionality such as setting a maximum value, incrementing a counter, and dividing two numbers.  I have also included ownership checks to ensure that only the contract owner can perform certain actions and it will be safe from unauthorized
Access.
<h2>Features</h2>
<b>1. Public Variables</b><br>
  <br><ul>maxValue: Stores a maximum value that can be set by the contract owner.</ul> </br>
    <ul> counter: A simple counter that can be incremented.<br></ul>
    owner: The address of the contract owner, set during contract deployment.<br>
<b>2. Functions</b>
    FormaxValue: Sets a new maximum value, only executable by the owner.
    incrementCounter: Increments the counter with an assertion check.
    forRevert: Checks if an address is the owner's address, using "revert".
    Divide: Divides two numbers with a "require" check to prevent division by zero.

