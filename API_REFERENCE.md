# API reference

This portable core provides bounded JSON lexical validation and cursor helpers. It deliberately does not allocate an AST; a host or future standard allocator can layer token storage and serialization on these deterministic primitives.

