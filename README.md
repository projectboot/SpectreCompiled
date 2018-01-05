# SpectreCompiled
Meltdown and Spectre Vuln PoC Compiled

$ gcc -march=pentium4 -std=c99 -O0 spectre.c -o spectre

$ ./spectre

![Screenshot](spectre.png)

CVE-2017-5754, CVE-2017-5753, CVE-2017-5715, spectre exploit

Patched;

"#define CACHE_HIT_THRESHOLD(80) -> #define CACHE_HIT_THRESHOLD (80)"

"?" -> '?'
