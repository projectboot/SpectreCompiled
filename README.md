# SpectreCompiled
Meltdown and Spectre Vuln PoC Compiled

$ gcc -march=pentium4 -std=c99 -O0 spectre.c -o spectre

$ ./spectre

![Screenshot](spectre.png)

Patched;

"#define CACHE_HIT_THRESHOLD(80) -> #define CACHE_HIT_THRESHOLD (80)"

"?" -> '?'
