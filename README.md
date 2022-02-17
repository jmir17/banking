# Banking Kata

Implement a class that implements the following interface:

```
Interface Account {
	deposit(amount: int): void;
	withdraw(amount: int): void;
	printStatements(): void;
}
```

Where `printStatements` prints in the console all the record of actions that happened to the account in the following format:

```
Date			Amount	    Balance
22.01.2022	    +500		500
14.02.2022	    -120		380
...
...
``` 
To run the tests, execute:  
`npm i` to install the depencencies and then  
`npm run test` to run the tests
