- TheBankStatement
    - Checking.java (line 33)
        - Found bug that I was not incrementing the next available check number when withdrawing only an amount
        - Corrected it by:
            Changing return withdraw(amount, nextCheckNumber); to
                     return withdraw(amount, nextCheckNumber++);
