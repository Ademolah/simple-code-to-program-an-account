# simple-code-to-program-an-account
account
class Account:
    
    def __init__(self, owner,balance):
        self.owner=owner
        self.balance=balance
        
    def __str__(self):
        
        return 'account owner is {}'. format(self.owner)
        return 'account balance is {}'. format(self.balance)
    
    def deposit(self, dep):
        
        self.balance +=dep
        
        print('i just deposited')
    
    
    
    
    def withdraw(self, wid):
        if self.balance >= wid:
            self.dep -=wid
            print('Withrawal accepted')
            
        else:
            print('insufficient balance')
            
    
    
