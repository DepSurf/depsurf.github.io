# Function: <code>do_prlimit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579456752,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1375",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_getrlimit",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_setrlimit",
        "kernel/compat.c:compat_SyS_setrlimit",
        "kernel/compat.c:compat_SyS_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456752,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579469968,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1375",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_setrlimit",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_getrlimit",
        "kernel/compat.c:compat_SyS_getrlimit",
        "kernel/compat.c:compat_SyS_setrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579469968,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579490368,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1375",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_setrlimit",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_getrlimit",
        "kernel/compat.c:compat_SyS_getrlimit",
        "kernel/compat.c:compat_SyS_setrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490368,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579477936,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1480",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_setrlimit",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:compat_SyS_getrlimit",
        "kernel/sys.c:compat_SyS_setrlimit",
        "kernel/sys.c:SyS_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579477936,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505808,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1487",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_setrlimit",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:SyS_prlimit64",
        "kernel/sys.c:compat_SyS_getrlimit",
        "kernel/sys.c:compat_SyS_setrlimit",
        "kernel/sys.c:SyS_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505808,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530496,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1541",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setrlimit",
        "kernel/sys.c:__x64_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x32_compat_sys_getrlimit",
        "kernel/sys.c:__ia32_compat_sys_getrlimit",
        "kernel/sys.c:__x32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_getrlimit",
        "kernel/sys.c:__x64_sys_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530496,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579566608,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1542",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setrlimit",
        "kernel/sys.c:__x64_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x32_compat_sys_getrlimit",
        "kernel/sys.c:__ia32_compat_sys_getrlimit",
        "kernel/sys.c:__x32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_getrlimit",
        "kernel/sys.c:__x64_sys_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566608,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579589600,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1542",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setrlimit",
        "kernel/sys.c:__x64_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x32_compat_sys_getrlimit",
        "kernel/sys.c:__ia32_compat_sys_getrlimit",
        "kernel/sys.c:__x32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_getrlimit",
        "kernel/sys.c:__x64_sys_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589600,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579615696,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1542",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setrlimit",
        "kernel/sys.c:__x64_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x32_compat_sys_getrlimit",
        "kernel/sys.c:__ia32_compat_sys_getrlimit",
        "kernel/sys.c:__x32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_getrlimit",
        "kernel/sys.c:__x64_sys_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615696,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579646832,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1558",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setrlimit",
        "kernel/sys.c:__x64_sys_setrlimit",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__x32_compat_sys_getrlimit",
        "kernel/sys.c:__ia32_compat_sys_getrlimit",
        "kernel/sys.c:__x32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_getrlimit",
        "kernel/sys.c:__x64_sys_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579646832,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579627360,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1559",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setrlimit",
        "kernel/sys.c:__x64_sys_setrlimit",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__x32_compat_sys_getrlimit",
        "kernel/sys.c:__ia32_compat_sys_getrlimit",
        "kernel/sys.c:__x32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_getrlimit",
        "kernel/sys.c:__x64_sys_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627360,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579633904,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1576",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setrlimit",
        "kernel/sys.c:__x64_sys_setrlimit",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__x32_compat_sys_getrlimit",
        "kernel/sys.c:__ia32_compat_sys_getrlimit",
        "kernel/sys.c:__x32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_getrlimit",
        "kernel/sys.c:__x64_sys_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633904,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579710432,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1585",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setrlimit",
        "kernel/sys.c:__x64_sys_setrlimit",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__x64_compat_sys_getrlimit",
        "kernel/sys.c:__ia32_compat_sys_getrlimit",
        "kernel/sys.c:__x64_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_getrlimit",
        "kernel/sys.c:__x64_sys_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579710432,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579809138,
      "name": "do_prlimit",
      "external": false,
      "loc": "kernel/sys.c:1449",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_compat_sys_getrlimit",
        "kernel/sys.c:__ia32_sys_getrlimit",
        "kernel/sys.c:__x64_sys_getrlimit"
      ],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setrlimit",
        "kernel/sys.c:__x64_sys_setrlimit",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__ia32_compat_sys_setrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579798992,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579944786,
      "name": "do_prlimit",
      "external": false,
      "loc": "kernel/sys.c:1452",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_compat_sys_getrlimit",
        "kernel/sys.c:__ia32_sys_getrlimit",
        "kernel/sys.c:__x64_sys_getrlimit"
      ],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setrlimit",
        "kernel/sys.c:__x64_sys_setrlimit",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__ia32_compat_sys_setrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932240,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579994386,
      "name": "do_prlimit",
      "external": false,
      "loc": "kernel/sys.c:1470",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_compat_sys_getrlimit",
        "kernel/sys.c:__ia32_sys_getrlimit",
        "kernel/sys.c:__x64_sys_getrlimit"
      ],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setrlimit",
        "kernel/sys.c:__x64_sys_setrlimit",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__ia32_compat_sys_setrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982304,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580033794,
      "name": "do_prlimit",
      "external": false,
      "loc": "kernel/sys.c:1470",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_compat_sys_getrlimit",
        "kernel/sys.c:__ia32_sys_getrlimit",
        "kernel/sys.c:__x64_sys_getrlimit"
      ],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setrlimit",
        "kernel/sys.c:__x64_sys_setrlimit",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__do_sys_prlimit64",
        "kernel/sys.c:__ia32_compat_sys_setrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021712,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490781864,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1542",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__arm64_sys_setrlimit",
        "kernel/sys.c:__arm64_sys_prlimit64",
        "kernel/sys.c:__arm64_sys_prlimit64",
        "kernel/sys.c:__arm64_compat_sys_getrlimit",
        "kernel/sys.c:__arm64_compat_sys_setrlimit",
        "kernel/sys.c:__arm64_sys_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490781864,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224819492,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1542",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setrlimit",
        "kernel/sys.c:__se_sys_prlimit64",
        "kernel/sys.c:__se_sys_prlimit64",
        "kernel/sys.c:__se_sys_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224819492,
      "name": "do_prlimit",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283607456,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1542",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setrlimit",
        "kernel/sys.c:__se_sys_prlimit64",
        "kernel/sys.c:__se_sys_prlimit64",
        "kernel/sys.c:__se_compat_sys_getrlimit",
        "kernel/sys.c:__se_compat_sys_setrlimit",
        "kernel/sys.c:__se_sys_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283607456,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271466994,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1542",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setrlimit",
        "kernel/sys.c:__se_sys_prlimit64",
        "kernel/sys.c:__se_sys_prlimit64",
        "kernel/sys.c:__se_sys_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271466994,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579592000,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1542",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setrlimit",
        "kernel/sys.c:__x64_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x32_compat_sys_getrlimit",
        "kernel/sys.c:__ia32_compat_sys_getrlimit",
        "kernel/sys.c:__x32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_getrlimit",
        "kernel/sys.c:__x64_sys_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592000,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579520640,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1542",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setrlimit",
        "kernel/sys.c:__x64_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x32_compat_sys_getrlimit",
        "kernel/sys.c:__ia32_compat_sys_getrlimit",
        "kernel/sys.c:__x32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_getrlimit",
        "kernel/sys.c:__x64_sys_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520640,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579589280,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1542",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setrlimit",
        "kernel/sys.c:__x64_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x32_compat_sys_getrlimit",
        "kernel/sys.c:__ia32_compat_sys_getrlimit",
        "kernel/sys.c:__x32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_getrlimit",
        "kernel/sys.c:__x64_sys_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589280,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
int do_prlimit(struct task_struct * tsk, unsigned int resource, struct rlimit * new_rlim, struct rlimit * old_rlim)
```

```json
{
  "name": "do_prlimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579622928,
      "name": "do_prlimit",
      "external": true,
      "loc": "kernel/sys.c:1542",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setrlimit",
        "kernel/sys.c:__x64_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__ia32_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x64_sys_prlimit64",
        "kernel/sys.c:__x32_compat_sys_getrlimit",
        "kernel/sys.c:__ia32_compat_sys_getrlimit",
        "kernel/sys.c:__x32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_compat_sys_setrlimit",
        "kernel/sys.c:__ia32_sys_getrlimit",
        "kernel/sys.c:__x64_sys_getrlimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622928,
      "name": "do_prlimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
