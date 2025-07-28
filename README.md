| #  | Transaction Group | System  | Deposit Type(s)           | Deposit Description                | Withdrawal Type(s)              | Withdrawal Description            |
|----|-------------------|---------|----------------------------|------------------------------------|----------------------------------|-----------------------------------|
| 1  | ATM               | Profile | ProfileATMCashDeposits     | ATM cash deposits                  | ProfileATMCashWithdrawals        | ATM cash withdrawals              |
|    |                   |         |                            |                                    | ProfileForeignATMCashWithdrawals | Foreign ATM withdrawals           |
| 2  | Checks            | Profile | ProfileCheckDeposits       | Check deposits                     | ProfileCheckWithdrawals          | Check-based withdrawals           |
| 3  | P2P               | Profile | ProfileP2PIn               | Incoming P2P transfers (incl. Zelle) | ProfileP2POut                  | Outgoing P2P transfers (incl. Zelle) |
|    |                   |         | ProfileZelleIn             | Incoming Zelle payments            | ProfileZelleOut                  | Outgoing Zelle payments           |
| 4  | Wire              | Profile | ProfileWiresIn             | Incoming wire transfers            | ProfileWiresOut                  | Outgoing wire transfers           |
| 5  | ACH               | Profile | ProfileACHIn               | All ACH credits                    | ProfileACHOut                    | All ACH debits                    |
|    |                   |         | ProfileACHDomIn            | Domestic ACH credits               | ProfileACHDomOut                 | Domestic ACH debits               |
