## Foundation of Computer Science
### The project required solving and explaining these points using the datasets contained in the zipper 
1. Extract all dogs with status that is not adoptable
2. For each (primary) breed, determine the number of dogs
3. For each (primary) breed, determine the ratio between the number of dogs of Mixed Breed and those not of Mixed Breed. Hint: look at the secondary_breed.
4. For each (primary) breed, determine the earliest and the latest posted timestamp.
5. For each state, compute the sex imbalance, that is the difference between male and female dogs. In which state this imbalance is largest?
6. For each pair (age, size), determine the average duration of the stay and the average cost of stay.
7. Find the dogs involved in at least 3 travels. Also list the breed of those dogs.
8. Fix the travels table so that the correct state is computed from the manual and the found fields. If manual is not missing, then it overrides what is stored in found.
9. For each state, compute the ratio between the number of travels and the population.
10. For each dog, compute the number of days from the posted day to the day of last access.
11. Partition the dogs according to the number of weeks from the posted day to the day of last access.
12. Find for duplicates in the dogs dataset. Two records are duplicates if they have (1) same breeds and sex, and (2) they share at least 90% of the words in the description field. Extra points if you find and implement a more refined for determining if two rows are duplicates.
