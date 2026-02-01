# Introduction
Description of the project

# Pseudocode
```
define order (first order is one word per notebook) not necessarily coding logic, more conceptual  
define current_state as beta  
initialize mm with beta (S* from notebook syntax) because all mm will have beta no matter text {S*: None}  
read line  
split line into list of words  
pop first element and store as next state  
give current state next state as dict{"next state": 1} if "next state" not in mm[S*] else mm[current state][next state += 1]  
then create key in mm, "first element": None if "first element" not in mm  
set current state as next state  
go to line 8 unless list empty  
go to line 6 unless file empty
```

# Successes
Description of the team's learning points

# Struggles
Description of the stumbling blocks the team experienced

# Personal Reflections
## Group Leader
Group leader's reflection on the project

## Other member
Other members' reflections on the project

# Generative AI Appendix
As per the syllabus
