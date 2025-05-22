<a href="https://andrew-johnson-4.github.io/lsts-tutorial/"><img src="https://repository-images.githubusercontent.com/404928261/4b75e965-a631-4489-a00a-d84b19a09eb9" alt="logo image" width=40%></a>

LSTS is a programming language and proof assistant.
The goal for this project is to integrate formal methods with natural programming habits.
By moving proof-theoretical concepts entirely to libraries,
programmers can hopefully benefit from improved sanity without too much additional stress.

Proofs in LSTS are built by connecting terms, type definitions, and quantified statements.
Terms can be evaluated to obtain Values.
Types describe properties of Terms.
Statements describe relations between Terms and Types.

### [Tutorial](https://github.com/andrew-johnson-4/LSTS/wiki)
### [Documentation](https://lambda-mountain-compiler-backend.github.io/lsts-language-reference/)
### [Discord](https://discord.gg/sW2ksPY9jj)

### Performance

The default LSTS backend compiles to C with little or no overhead or runtime dependencies.
Previously, the compiler generated x86-Linux objects directly, however this was approximately 3x slower than the C backend.
We will revisit the direct targets to generate fully certified builds.
Until then, C is the default backend.
