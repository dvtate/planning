# Backend
The obvious solution is to have a frontend that allows user to make their programs and help validate them. And the frontend will do codegen to a lang that's used to actually run the user's code.



## Fully Compiled Language

### Pros
- Potential for best perf
-

### Cons
- Lots of work from scratch and unlikely to be able to make abstractions up to the level required
- For example making async/await is unlikely

## VM Language

### Pros
- Kinda happy medium in terms of perf vs

### Cons
- Design closely tied to lang so some features (ie)

## Interpreted Language (WASM)

### Pros

### Cons


## Interpreted Language (JS)

### Pros
- Can focus on validation and easy interop and stuff
- Likely can later convert to it being interpreted in WASM

### Cons
- Slow