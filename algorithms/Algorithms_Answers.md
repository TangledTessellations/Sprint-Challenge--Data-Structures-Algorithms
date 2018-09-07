Add your answers to the Algorithms exercises here.

a.) The runtime complexity for this algorithm is O(n), since every time you     add a value x to n, the algorithm must run x more times. This is because     we are adding n^2 to the value, and comparing it to n^3. We're basically     finding how many n^2 does it take to reach n^3. This value can have a        coefficient (2n, 3n ,5n, etc), but these are ignored in big O notation,      so the answer is O.

b.) I would guess this runtime is closer to O(n^2) than it is to O(n). Each      nested for loop does not need to run the entirety of the length of n, as     it's incrementation starts at the index of the parent loop, however          since there are so many neted loops, this reduction is made less             important since there are so many more repititions per addition to n.
     I would say O(n^2)
c.) For each additional n added, this algorithm increases in number of           operations by 1. Thus, this algorithm is O(n). 