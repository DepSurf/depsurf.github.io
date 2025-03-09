# Function: <code>read_ldt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579054184,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:153",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:sys_modify_ldt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579050510,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:153",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:sys_modify_ldt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579049614,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:153",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:sys_modify_ldt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579041950,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:154",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:sys_modify_ldt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579051185,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:303",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:SyS_modify_ldt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int read_ldt(void * ptr, long unsigned int bytecount)
```

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579053728,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:307",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579053728,
      "name": "read_ldt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int read_ldt(void * ptr, long unsigned int bytecount)
```

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579058528,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:410",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579058528,
      "name": "read_ldt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int read_ldt(void * ptr, long unsigned int bytecount)
```

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579066352,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:410",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579066352,
      "name": "read_ldt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int read_ldt(void * ptr, long unsigned int bytecount)
```

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068432,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:410",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068432,
      "name": "read_ldt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int read_ldt(void * ptr, long unsigned int bytecount)
```

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579076320,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:494",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579076320,
      "name": "read_ldt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int read_ldt(void * ptr, long unsigned int bytecount)
```

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579078800,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:494",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078800,
      "name": "read_ldt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int read_ldt(void * ptr, long unsigned int bytecount)
```

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579085680,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:500",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085680,
      "name": "read_ldt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int read_ldt(void * ptr, long unsigned int bytecount)
```

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579108752,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:500",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108752,
      "name": "read_ldt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int read_ldt(void * ptr, long unsigned int bytecount)
```

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579139824,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:500",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139824,
      "name": "read_ldt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
int read_ldt(void * ptr, long unsigned int bytecount)
```

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579184096,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:500",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579184096,
      "name": "read_ldt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int read_ldt(void * ptr, long unsigned int bytecount)
```

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579188176,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:502",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188176,
      "name": "read_ldt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int read_ldt(void * ptr, long unsigned int bytecount)
```

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579217392,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:502",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217392,
      "name": "read_ldt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int read_ldt(void * ptr, long unsigned int bytecount)
```

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068784,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:410",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068784,
      "name": "read_ldt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int read_ldt(void * ptr, long unsigned int bytecount)
```

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579001520,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:410",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579001520,
      "name": "read_ldt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int read_ldt(void * ptr, long unsigned int bytecount)
```

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068368,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:410",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068368,
      "name": "read_ldt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int read_ldt(void * ptr, long unsigned int bytecount)
```

```json
{
  "name": "read_ldt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579072464,
      "name": "read_ldt",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:410",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt",
        "arch/x86/kernel/ldt.c:__x64_sys_modify_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579072464,
      "name": "read_ldt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int read_ldt(void * ptr, long unsigned int bytecount)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int read_ldt(void * ptr, long unsigned int bytecount)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int read_ldt(void * ptr, long unsigned int bytecount)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int read_ldt(void * ptr, long unsigned int bytecount)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int read_ldt(void * ptr, long unsigned int bytecount)
```
</details>
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
