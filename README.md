# vim-cflags
This vim plugin is for highlight C source code when #if #else ...

It use vim build-in method to show those code, like #if 0 #else

## Variables

### g:cflags variable
Fully qualified file name for defines file.
In this file, defines should like:
``` {.vim}
    FLAG1 = 0
    FLAG2 = 1
```

### g:cflags_debug variable
Set debug print level

## Key bindings

### <C-K>
Show define value under cursor

