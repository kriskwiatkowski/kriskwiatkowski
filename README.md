I've been writing cryptographic code for about twenty years. Mostly C, Go,
some Rust, assembly when the compiler won't cooperate. Primitives,
protocols, and the unglamorous stretch in between where a specification
meets a device with a few kilobytes of RAM and no entropy source anyone
should trust.

--------------------------------------------------------------------
 
What I'm working on

Efficient Post-quantum Cryptographic Components - PQC primitives in
C and Rust for constrained targets. no_std, arm-m, riscv64, tight memory
budgets. Reference implementations are written for papers, not for
devices.

Side channels. Constant time, DPA, faults, leakage assessment,
countermeasures. Most of my time goes here. It is the part that decides
whether something sound on paper is still sound after it meets silicon.
 
Lattice signatures, multivariate schemes, code-based KEMs. The tradeoffs
between them only get honest once you try to fit one into a real
product.

--------------------------------------------------------------------
 
Elsewhere
 
Profile: [https://amongbytes.com/about.html#sec-profile](https://amongbytes.com/about.html#sec-profile)
 
