1. ```values added: 20```
2. ```final result: 20```
3. ```values added: 20```
4. Line 13 returns an error because the let declaration of the variable result
   limits the variable's scope to the if statement's block. Thus, javascript
   can't log the value of `result` to the console because it doesn't have
   access to it outside of the if block.
5. The code results in an error because we try to reassign the value of the
   const-declared variable result. We do not get to the print statement.
6. The program throws an error at line 9, but line 13 would error as well.
   Since `result` is declared with `const`, this limits the scope to the if
   block it was declared in, so when line 13 tries to access `result`, an error
   will occur since it is not in the if block.

