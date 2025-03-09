# Function: <code>do_sys_ftruncate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580984272,
      "name": "do_sys_ftruncate",
      "external": false,
      "loc": "fs/open.c:158",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_ftruncate",
        "fs/open.c:compat_SyS_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984272,
      "name": "do_sys_ftruncate.constprop.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581139088,
      "name": "do_sys_ftruncate",
      "external": false,
      "loc": "fs/open.c:158",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:compat_SyS_ftruncate",
        "fs/open.c:SyS_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139088,
      "name": "do_sys_ftruncate.constprop.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581214272,
      "name": "do_sys_ftruncate",
      "external": false,
      "loc": "fs/open.c:169",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:compat_SyS_ftruncate",
        "fs/open.c:SyS_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581214272,
      "name": "do_sys_ftruncate.constprop.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581261104,
      "name": "do_sys_ftruncate",
      "external": false,
      "loc": "fs/open.c:169",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:compat_SyS_ftruncate",
        "fs/open.c:SyS_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581261104,
      "name": "do_sys_ftruncate.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581399584,
      "name": "do_sys_ftruncate",
      "external": false,
      "loc": "fs/open.c:169",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:compat_SyS_ftruncate",
        "fs/open.c:SyS_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399584,
      "name": "do_sys_ftruncate.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581555904,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:169",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64",
        "fs/open.c:__x32_compat_sys_ftruncate",
        "fs/open.c:__ia32_sys_ftruncate",
        "fs/open.c:__x64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581555904,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581641392,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:158",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64",
        "fs/open.c:__x32_compat_sys_ftruncate",
        "fs/open.c:__ia32_sys_ftruncate",
        "fs/open.c:__x64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581641392,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758096,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:159",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64",
        "fs/open.c:__x32_compat_sys_ftruncate",
        "fs/open.c:__ia32_compat_sys_ftruncate",
        "fs/open.c:__ia32_sys_ftruncate",
        "fs/open.c:__x64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758096,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581830304,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:159",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64",
        "fs/open.c:__x32_compat_sys_ftruncate",
        "fs/open.c:__ia32_compat_sys_ftruncate",
        "fs/open.c:__ia32_sys_ftruncate",
        "fs/open.c:__x64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830304,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582051040,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:156",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64",
        "fs/open.c:__x32_compat_sys_ftruncate",
        "fs/open.c:__x64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582051040,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582100912,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:156",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64",
        "fs/open.c:__x32_compat_sys_ftruncate",
        "fs/open.c:__x64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582100912,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582125904,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:157",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64",
        "fs/open.c:__x32_compat_sys_ftruncate",
        "fs/open.c:__x64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125904,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582442544,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:156",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64",
        "fs/open.c:__x64_compat_sys_ftruncate",
        "fs/open.c:__x64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442544,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582960448,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:156",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64",
        "fs/open.c:__x64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582960448,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583518928,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:156",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64",
        "fs/open.c:__x64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583518928,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583734368,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:157",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64",
        "fs/open.c:__x64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583734368,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583935392,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:157",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64",
        "fs/open.c:__x64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583935392,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493293616,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:159",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_ftruncate64",
        "fs/open.c:__arm64_compat_sys_ftruncate",
        "fs/open.c:__arm64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493293616,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226896768,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:159",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/open.c:__se_sys_ftruncate64",
        "fs/open.c:__se_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226896768,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286831632,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:159",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "arch/powerpc/kernel/sys_ppc32.c:compat_sys_ftruncate64",
        "fs/open.c:__se_compat_sys_ftruncate",
        "fs/open.c:__se_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286831632,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273038782,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:159",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/open.c:__se_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273038782,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581799040,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:159",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64",
        "fs/open.c:__x32_compat_sys_ftruncate",
        "fs/open.c:__ia32_compat_sys_ftruncate",
        "fs/open.c:__ia32_sys_ftruncate",
        "fs/open.c:__x64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799040,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581736704,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:159",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64",
        "fs/open.c:__x32_compat_sys_ftruncate",
        "fs/open.c:__ia32_compat_sys_ftruncate",
        "fs/open.c:__ia32_sys_ftruncate",
        "fs/open.c:__x64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581736704,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790352,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:159",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64",
        "fs/open.c:__x32_compat_sys_ftruncate",
        "fs/open.c:__ia32_compat_sys_ftruncate",
        "fs/open.c:__ia32_sys_ftruncate",
        "fs/open.c:__x64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790352,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```

```json
{
  "name": "do_sys_ftruncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581859488,
      "name": "do_sys_ftruncate",
      "external": true,
      "loc": "fs/open.c:159",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64",
        "fs/open.c:__x32_compat_sys_ftruncate",
        "fs/open.c:__ia32_compat_sys_ftruncate",
        "fs/open.c:__ia32_sys_ftruncate",
        "fs/open.c:__x64_sys_ftruncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581859488,
      "name": "do_sys_ftruncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long int do_sys_ftruncate(unsigned int fd, loff_t length, int small)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
