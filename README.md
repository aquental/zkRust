# zkRust
Zero Knowledge in Rust

### April 2024

> [Chaun-Pedersen Protocol](https://crypto.stackexchange.com/questions/99262/chaum-pedersen-protocol)
> 
> The Chaum-Pedersen Protocol allows one to prove the equality of a secret value **x** given a set of two equations that hide the value **x** but can be publicly shared. It's an interactive Zero-Knowledge Proof protocol where a _prover_ wants to convince a _verifier_ that the aforementioned condition of equality holds true. [_here_](https://muens.io/chaum-pedersen-protocol)

> Intro to Cryptography
> 
> [Cryptography: an intrduction](https://www.cs.umd.edu/~waa/414-F11/IntroToCrypto.pdf)
---
> [Bitcoin Rust](https://github.com/gagiuntoli/bitcoin_rust)
> 
> Based on [Programming Bitcoin](https://www.oreilly.com/library/view/programming-bitcoin/9781492031482/) by Jimmy Song.

> Additional Diffie-Hellman Groups for Use with IETF Standards
> 
> [reference](https://www.rfc-editor.org/rfc/rfc5114#page-15)

> Moon math
>
> [Study Group](https://zkhack.dev/zk-study-group-moonmath-manual/)
>
> [The RareSkills Book of Zero Knowledge](https://www.rareskills.io/zk-book)
>
> [CryptoHack](https://cryptohack.org/)
>
> [MIT 6.875 (Cryptography), Spring 2018](https://www.youtube.com/playlist?list=PL6ogFv-ieghe8MOIcpD6UDtdK-UMHG8oH)
>
> <details>
> <summary>Abstract Algebra - Socratica</summary>
>
> list [Abstract Algebra - Socratica](https://www.youtube.com/playlist?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 1 - [What is Abstract Algebra? (Modern Algebra)](https://youtu.be/IP7nW_hKB7I?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 2 - [Group Definition (expanded) - Abstract Algebra](https://youtu.be/g7L_r6zw4-c?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 3 - [Abstract Algebra: The definition of a Group](https://youtu.be/QudbrUcVPxk?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 4 - [Abstract Algebra: Motivation for the definition of a group](https://youtu.be/yHq_yzYZV6U?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 5 - [Abstract Algebra: The definition of a Subgroup](https://youtu.be/TJAQNlGvfjE?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 6 - [Group Multiplication Tables | Cayley Tables (Abstract Algebra)](https://youtu.be/BwHspSCXFNM?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 7 - [Cosets and Lagrange’s Theorem - The Size of Subgroups (Abstract Algebra)](https://youtu.be/TCcSZEL_3CQ?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 8 - [Normal Subgroups and Quotient Groups (aka Factor Groups) - Abstract Algebra](https://youtu.be/vYKdh5oQ4Zw?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 9 - [Cyclic Groups (Abstract Algebra)](https://youtu.be/8A84sA1YuPw?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 10 - [Abstract Algebra: Group or Not Group? (Integer edition)](https://youtu.be/qvx9TnK85bw?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
> 
> 11 - [Group Homomorphisms - Abstract Algebra](https://youtu.be/XPF5fe1WdKY?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 12 - [Homomorphisms (Abstract Algebra)](https://youtu.be/cYzp5IWqCsg?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 13 - [Isomorphisms (Abstract Algebra)](https://youtu.be/BAmWgVjSosY?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>  
> 14 - [The Kernel of a Group Homomorphism – Abstract Algebra](https://youtu.be/TngePpJ_x-I?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 15 - [The Order of an Element (Abstract Algebra)](https://youtu.be/OWTKYLAEYvY?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 16 - [Symmetric Groups (Abstract Algebra)](https://youtu.be/3aNeCWRjh8I?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 17 - [Cycle Notation of Permutations - Abstract Algebra](https://youtu.be/MpKG6FmcIHk?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 18 - [Dihedral Group (Abstract Algebra)](https://youtu.be/rPh7EQPSaO4?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 19 - [Symmetry Groups of Triangles (Abstract Algebra)](https://youtu.be/DeCcqioogLY?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 20 - [Matrix Groups (Abstract Algebra)](https://youtu.be/AJTRwhSZJWw?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 21 - [Direct Products of Groups (Abstract Algebra)](https://youtu.be/rXLz8TdckWo?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 22 - [Simple Groups - Abstract Algebra](https://youtu.be/jhVMBXl5jTA?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 23 - [Abstract Algebra: The definition of a Ring](https://youtu.be/6RC70C9FNXI?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 24 - [Ring Definition (expanded) - Abstract Algebra](https://youtu.be/j_f7O-4Rb9U?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 25 - [Ring Examples (Abstract Algebra)](https://youtu.be/_RTHvweHlhE?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
>
> 26 - []
>
> 27 - []
>
> 28 - []
>
> 29 - []
>
> 30 - []
>
> 31 - []
>
> 32 - []
>
> 33 - []
> </details>
>
> [Modern Zero Knowledge Cryptography - MIT IAP 2023](https://zkiap.com/)
>
> > [Foundations of Cryptography - MIT 6.875](https://mit6875.github.io/HANDOUTS/numbertheory.pdf)
> >
> > [Zero Knowledge Proofs - MOOC](https://zk-learning.org)
