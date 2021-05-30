# JABAR-DIGITAL-3
jawaban untuk DE-Phyton 1

def unique_names(names1, names2):
   return list(set(names1).union(set(names2)))

names1 = ["Ava", "Emma", "Olivia"] 
names2 = ["Olivia", "Sophia", "Emma"] 
print(unique_names(names1, names2))
