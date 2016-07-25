# We will be creating a bank account

class BankAccount(object):
    balance = 0
    def __init__(self, name):
      self.name = name
     
    def __repr__(self):
        return "This account belongs to %s and has a balance of %.2f dollars." % (self.name, self.balance)
    
    def show_balance(self):
        print "Your balance is: $%.2f." % (self.balance)
        
    def deposit(self, amount):
        if amount <= 0:
            print "Sorry, but you're broke."
            return
        else:
            print "You have a total of %s." % (amount)
            self.balance += amount
            self.show_balance()
            
    def withdraw(self,amount):
        if amount > self.balance:
            print "Invalid. Try again."
            return
            
        else:
            print " The user is drawing $%.2f." % (amount)
            self.balance -= amount
            self.show_balance()
            
my_account = BankAccount("Jazmeen")
print my_account
my_account.show_balance
my_account.deposit(2000)
my_account.withdraw(1000)
print my_account
