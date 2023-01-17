# my-python-coding
#Class 1.
#fourcalculation.py
"""A class for four arithmetic calculations"""

class FourCalculation:
    """A class for four arithmetic caluclations"""
    
    def __init__(self,first,second):
        self.first=first
        self.second=second
        #if second is zero, raise an exception
        if second==0:
            raise ValueError('The second number must not be 0')
            
    def add(self):
        return self.first+self.second
    
    def mul(self):
        return self.first*self.second
    
    def sub(self):
        return self.first-self.second
    
    def div(self):
        return self.first/self.second

b=FourCalculation(8,2)
print(b.first,b.second)
print(b.add(),b.mul(), b.sub(),b.div())
