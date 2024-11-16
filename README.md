# Status bar and widgets

`tsconfig.json` contains hard-coded nix store path. To regenerate it:

```
ags types -d . --tsconfig
```

This is necessary when cloning the project or adding libs to the codebase.
