# Function: <code>do_sigaltstack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_sigaltstack(const stack_t * uss, stack_t * uoss, long unsigned int sp)
```

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579423152,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:3091",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:SyS_sigaltstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:compat_restore_altstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579423152,
      "name": "do_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int do_sigaltstack(const stack_t * uss, stack_t * uoss, long unsigned int sp)
```

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579436624,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:3091",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:SyS_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436624,
      "name": "do_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int do_sigaltstack(const stack_t * uss, stack_t * uoss, long unsigned int sp)
```

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579456976,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:3111",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:SyS_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456976,
      "name": "do_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int do_sigaltstack(const stack_t * ss, stack_t * oss, long unsigned int sp)
```

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444000,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:3166",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:SyS_sigaltstack",
        "kernel/signal.c:SyS_sigaltstack",
        "kernel/signal.c:SyS_sigaltstack",
        "kernel/signal.c:SyS_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444000,
      "name": "do_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int do_sigaltstack(const stack_t * ss, stack_t * oss, long unsigned int sp)
```

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579472304,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:3187",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_restore_altstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:SyS_sigaltstack",
        "kernel/signal.c:SyS_sigaltstack",
        "kernel/signal.c:SyS_sigaltstack",
        "kernel/signal.c:SyS_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579472304,
      "name": "do_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int do_sigaltstack(const stack_t * ss, stack_t * oss, long unsigned int sp)
```

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579486512,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:3420",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579486512,
      "name": "do_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579520240,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:3744",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520240,
      "name": "do_sigaltstack.constprop.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579539872,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:3992",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539872,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579565968,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4000",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565968,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579628325,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4018",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:restore_altstack"
      ],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597648,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579608389,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4055",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:restore_altstack"
      ],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577856,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579614851,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4077",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:restore_altstack"
      ],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583536,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579691235,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4169",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:restore_altstack"
      ],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657728,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579754576,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4169",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579754576,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579886800,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4171",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886800,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579936064,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4195",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579936064,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579975392,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4206",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975392,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
int do_sigaltstack(const stack_t * ss, stack_t * oss, long unsigned int sp, size_t min_ss_size)
```

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490724312,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4000",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__arm64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490724312,
      "name": "do_sigaltstack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224781684,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4000",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__se_sys_sigaltstack",
        "kernel/signal.c:__se_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224781684,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283550112,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4000",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__se_sys_sigaltstack",
        "kernel/signal.c:__se_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283550112,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271440372,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4000",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__se_sys_sigaltstack",
        "kernel/signal.c:__se_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271440372,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579542272,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4000",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542272,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579471024,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4000",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471024,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579539552,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4000",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539552,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigaltstack",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579573424,
      "name": "do_sigaltstack",
      "external": false,
      "loc": "kernel/signal.c:4000",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_compat_sigaltstack",
        "kernel/signal.c:restore_altstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__ia32_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack",
        "kernel/signal.c:__x64_sys_sigaltstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579573424,
      "name": "do_sigaltstack.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const stack_t * ss</code>
</li>
<li>
<b>Param added. </b>
<code>stack_t * oss</code>
</li>
<li>
<b>Param removed. </b>
<code>const stack_t * uss</code>
</li>
<li>
<b>Param removed. </b>
<code>stack_t * uoss</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int do_sigaltstack(const stack_t * ss, stack_t * oss, long unsigned int sp)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int do_sigaltstack(const stack_t * ss, stack_t * oss, long unsigned int sp, size_t min_ss_size)
```
</details>
</li>
</ul>
