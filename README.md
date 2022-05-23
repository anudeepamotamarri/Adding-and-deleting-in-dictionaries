# Adding-and-deleting-in-dictionaries 
data={'Abc':123,'Def':456,'Ghi':789}

print(data)

data.update({'Def':56})

print(data)

data.popitem()

print(data)

data.pop('Def')

print(data)

del data['Abc']

print(data)
