Here I will create ERC20 token but first , What is ERC? 
Let me make it easy for you ERC stands for "Ethereum request for comment," and the ERC20 standard was introduced in the year 2015. 
Etherium An ERC20 token is a widely adopted protocol on the Ethereum blockchain, used for crafting and deploying
smart contracts. These smart contracts serve as the foundation for creating digital assets or tokenized properties, providing investment opportunities to individuals. 
This standard define 6 functions that has to be implented must,given below :
    function BalanceOf : This function is used to check and retrieve the balance of tokens that a given _spender address holds.
    function TotalSupply : It returns the total supply of the ERC-20 tokens in circulation.
    function TransferTo : This function is responsible for transferring a specified _Amount of tokens to the _receipt address. It returns a boolean value (true or false) to indicate the success of the transfer.
    function TransferFrom : It facilitates the transfer of a specified _amount of tokens from the _spender address to the _receipt address. This function is commonly used for authorized token transfers.
    function Allowance : This function allows checking the amount of tokens that the _owner has approved the _spender to transfer on their behalf.
    function Approve : It is used to approve a specific _spender to spend or transfer a certain _amount of tokens on behalf of the token owner. This function typically sets the allowance.
