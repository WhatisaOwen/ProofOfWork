# Argon2 Based Proof-of-Work Solver
Batsh compiled into Bash

# What is a Proof of Work?

A Proof of Work (PoW) is a challenge that requires a computer to perform a certain amount of computation before it is allowed to continue.
This helps prevent abuse mainly bots because every request requires the client to spend CPU time.
Instead of asking a user to solve a annoying CAPTCHA that doesnt really work a server can require the client to solve a small mathematical puzzle.


# What does this solver do?


Its given a challenge string containing the required Argon2 parameters (memory cost, time cost, salt, and difficulty), the solver repeatedly generates candidate unblock codes and hashes them using Argon2.

A solution is found when the resulting hash satisfies the difficulty requirement defined by the challenge.

The generated unblock code can then be submitted back to the website, where the server can verify it instantly.

 PwnF @Insane
