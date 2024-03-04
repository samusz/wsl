# my notes on WSL config

I had to create a file .wslgconfig with
```config
[system-distro-env]
;disable GPU in system-distro
LIBGL_ALWAYS_SOFTWARE=1
```
in `C:\ProgramData\Microsoft\WSL`.
The WSL folder didn't exist so I had to create it manually.

Restarted wsl. Worked.
Restarted laptop, the fix still works.
ref: https://github.com/microsoft/wslg/issues/1148 

