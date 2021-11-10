Reproduction of F# StackOverflowException when switching from VS2019 to VS2022.

MSBuild log w/ 'Diagnostic' verbosity includes:

```
> Microsoft (R) F# Compiler version 12.0.0.0 for F# 6.0
> Copyright (c) Microsoft Corporation. All Rights Reserved.
> Process is terminated due to StackOverflowException.
```

See [Library1.fs](https://github.com/patroeper/fs_fsc_soe/blob/main/Library1/Library1.fs) for reproduction steps.
