To see ledger working, simply run the script `./ledger bal`.  The ledger file is a bash script which sets up some parameters for including all of the ledger files in the project.  [Ledger-cli](http://www.ledger-cli.org/) is required for this script to work.

Other commonly used commands:

- `./ledger --sort d reg` to get a list of transactions sorted by date.
- `./ledger --sort d` print  to get an alternate format of transaction sorted by date.
- `./ledger bal Bank:` to see if I am broke or not.
- `./ledger bal Receivable:` to see who owes me money.
- `./ledger bal Payable:` to see who I owe money.

Please read the [ledger documentation](http://www.ledger-cli.org/docs.html) for a complete list of possible ledger commands.
