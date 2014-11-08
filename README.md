chenming
========
    def ispalindromic(s):
    	'''Check if a sequence is palindromic.
    
    	A palindromic sequence reads the same both from left and right
    	'''
    	return all(s[i] == s[~i] for i in range(len(s)//2)) # ~0 == -1, ~1 == -2
    
