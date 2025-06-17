class SavingsAccount(Account):
    def __init__(self):
        Account.__init__(self)

    def savingsWithdraw(self, amount):
        if (amount < 1000):
            super().withdraw(amount)
        else:
            print("Amount exceeds withdrawal limit")


savings = SavingsAccount()
savings.savingsWithdraw(2000)
