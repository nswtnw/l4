'''
1. Start 
2. Define function f(x)
3. Define function g(x) which is obtained 
   from f(x)=0 such that x = g(x) and |g'(x) < 1|
4. Choose intial guess x0, Tolerable Error e 
   and Maximum Iteration N
5. Initialize iteration counter: step = 1
6. Calculate x1 = g(x0)
7. Increment iteration counter: step = step + 1
8. If step > N then print "Not Convergent" 
   and goto (12) otherwise goto (10) 
9. Set x0 = x1 for next iteration
10. If |f(x1)| > e then goto step (6) otherwise goto step (11)
11. Display x1 as root.
12. Stop

''
