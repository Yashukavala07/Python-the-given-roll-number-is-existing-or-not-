# Python-the-given-roll-number-is-existing-or-not-
X = [10, 20, 30, 40, 50, 60, 70, 80, 90] M = int(input("Enter your roll no: "))  if M not in X:     print("Roll no is not present")     print("New list is formed")     X.append(M)     print(X) else:     print("Given roll no is present")     print(X)  
