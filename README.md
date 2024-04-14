# Sieve of Eratosthenes algorithm##
##The Sieve of Eratosthenes is an e cient algorithm to nd all prime numbers up 
to a speci ed limit, . It works by iteratively marking the multiples of each prime 
starting from 2. Initially, all numbers are considered unmarked. Begin with the 
rst prime, 2, and mark its multiples as non-prime. Move to the next number, 3 
(the next unmarked number), and repeat the process. Continue this until the 
square of the current prime exceeds \( n \). Numbers remaining unmarked after 
this process are primes. This method reduces time complexity by eliminating 
non-prime numbers early. The result is a list of prime numbers up to \( n \)#


#Parallel approach (data distribution) 
## Block data decomposition 
## If n is the number of elements and p be the number of processing elements,
           #Divide data(range) into n/p contiguous blocks of equal size.
           # Let i denote the rank of the process
                              # Range start = i * (n/p) 
                              # Range end = (i + 1) * (n/p) -


