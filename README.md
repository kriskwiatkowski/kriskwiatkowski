```
 _  __     _
| |/ /_ __(_)___
| ' /| '__| / __|
| . \| |  | \__ \
|_|\_\_|  |_|___/
 
cryptography engineering / standards / deployment
```
 
I work on post-quantum cryptography: the algorithms themselves, the
implementations, and the long road from a draft spec to something
actually running in production.

--------------------------------------------------------------------
 
What I'm working on

Efficient Post-quantum Cryptographic Components. Implementations
of PQC primitives in C and Rust, built for constrained targets rather
than servers: no_std, embedded and riscv64, tight memory budgets, the
places where a reference implementation is not an option.
 
Side-channel resistance. Constant-time construction, DPA and fault
considerations, leakage assessment, countermeasure design. This is the
part that decides whether a scheme that is sound on paper is still sound
once it is running on real hardware, and it is where most of my time
goes.
 
Lattice-based signatures, multivariate schemes and code-based KEMs, with
attention to the tradeoffs that only become visible when you try to fit
one of them into an actual device.

 
--------------------------------------------------------------------
 
Advisory
 
I take on advisory board roles in security and cryptography. If you
are planning a migration to post-quantum, arguing about hybrid modes,
or trying to work out what your standards exposure actually is, that
is the kind of thing I'm useful for.
 
--------------------------------------------------------------------
 
Elsewhere
 
Contact: contact@amongbytes.com
 
