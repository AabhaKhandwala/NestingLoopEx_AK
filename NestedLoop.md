Look at the first set of nested loops ("CN"). Which variable changes faster? Is it the variable controlled by the outer loop (c) or the variable controlled by the inner loop (n)? Answer in a comment.
Ans: inner loop changes faster than outer loop.variable controlled by the inner loop(n).

Change the order of the loops so that the "c" loop is on the inside and the "n" loop is on the outside. How does the output change?
Ans: 1 A 1 B 1 C 1 D 1 E 2 A 2 B 2 C 2 D 2 E 3 A 3 B 3 C 3 D 3 E

Look at the second set of nested loops ("AB"). Change the print() statement to println(). How does the output change? (Then change it back to print().)
Ans:print() will print output in same line.(1-1 1-2 1-3 2-1 2-2 2-3 3-1 3-2 3-3)while println will print output in newline.

Add a System.out.println() statement after the close brace of the inner loop (the "b" loop), but still inside the outer loop. How does the output change?
Ans:it will throw error("b cannot be resolved to a variable") as b is out of scope here, outside of the loop.
