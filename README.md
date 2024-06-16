# Function And Error
This `Error` smart contract is designed to demonstrate various error handling mechanisms in Solidity, including `require`, `assert`, and `revert`. This contract also includes basic functionality such as setting a maximum value, incrementing a counter, and dividing two numbers.  I have also included ownership checks to ensure that only the contract owner can perform certain actions and it will be safe from unauthorized
Access.
 <h2>Features</h2>
    <ul>
        <li><b>Public Variables:</b>
            <ul>
                <li><code>maxValue</code>: Stores a maximum value that can be set by the contract owner.</li>
                <li><code>counter</code>: A simple counter that can be incremented.</li>
                <li><code>owner</code>: The address of the contract owner, set during contract deployment.</li>
            </ul>
        </li>
        <li><b>Functions:</b>
            <ul>
                <li><code>FormaxValue</code>: Sets a new maximum value, only executable by the owner.</li>
                <li><code>incrementCounter</code>: Increments the counter with an assertion check.</li>
                <li><code>forRevert</code>: Checks if an address is the owner's address, using <code>revert</code>.</li>
                <li><code>Divide</code>: Divides two numbers with a <code>require</code> check to prevent division by zero.</li>
            </ul>
        </li>
    </ul>
    <h2>Usage</h2>
    <h3>Deploying the Contract</h3>
    <ol>
        <li>Open the Remix IDE or any other Solidity-compatible IDE.</li>
        <li>Copy and paste the contract code into a new Solidity file.</li>
        <li>Compile the contract using the Solidity compiler version 0.8.18.</li>
        <li>Deploy the contract to an Ethereum network.</li>
    </ol>
    <h2>Authors</h2>
    <p>Paras Aggarwal<br>
    Email: parasaggarwal7172@gmail.com</p>

</body>
</html>
