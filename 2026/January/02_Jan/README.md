# LeetCode 961 – N-Repeated Element in Size 2N Array

**Date:** Jan 2, 2026  
**Approach:**  
The repeated element must appear adjacent or within distance 2.  
We check `A[i] == A[i+1]` or `A[i] == A[i+2]`.
