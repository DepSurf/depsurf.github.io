# Function: <code>do_mprotect_pkey</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580897824,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:373",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:SyS_pkey_mprotect",
        "mm/mprotect.c:SyS_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580897824,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 828
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580942416,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:376",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:SyS_pkey_mprotect",
        "mm/mprotect.c:SyS_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580942416,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581042672,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:393",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:SyS_pkey_mprotect",
        "mm/mprotect.c:SyS_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042672,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581180528,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:456",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_mprotect",
        "mm/mprotect.c:__x64_sys_pkey_mprotect",
        "mm/mprotect.c:__ia32_sys_mprotect",
        "mm/mprotect.c:__x64_sys_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581180528,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 745
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581262816,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:457",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_mprotect",
        "mm/mprotect.c:__x64_sys_pkey_mprotect",
        "mm/mprotect.c:__ia32_sys_mprotect",
        "mm/mprotect.c:__x64_sys_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581262816,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 745
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581337376,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:458",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_mprotect",
        "mm/mprotect.c:__x64_sys_pkey_mprotect",
        "mm/mprotect.c:__ia32_sys_mprotect",
        "mm/mprotect.c:__x64_sys_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581337376,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581396656,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:486",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_mprotect",
        "mm/mprotect.c:__x64_sys_pkey_mprotect",
        "mm/mprotect.c:__ia32_sys_mprotect",
        "mm/mprotect.c:__x64_sys_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581396656,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581594784,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:512",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_mprotect",
        "mm/mprotect.c:__x64_sys_pkey_mprotect",
        "mm/mprotect.c:__ia32_sys_mprotect",
        "mm/mprotect.c:__x64_sys_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581594784,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581640800,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:512",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_mprotect",
        "mm/mprotect.c:__x64_sys_pkey_mprotect",
        "mm/mprotect.c:__ia32_sys_mprotect",
        "mm/mprotect.c:__x64_sys_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581640800,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 919
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581662368,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:512",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_mprotect",
        "mm/mprotect.c:__x64_sys_pkey_mprotect",
        "mm/mprotect.c:__ia32_sys_mprotect",
        "mm/mprotect.c:__x64_sys_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581662368,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 899
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581930736,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:522",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_mprotect",
        "mm/mprotect.c:__x64_sys_pkey_mprotect",
        "mm/mprotect.c:__ia32_sys_mprotect",
        "mm/mprotect.c:__x64_sys_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930736,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 925
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582339456,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:615",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_mprotect",
        "mm/mprotect.c:__x64_sys_pkey_mprotect",
        "mm/mprotect.c:__ia32_sys_mprotect",
        "mm/mprotect.c:__x64_sys_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582339456,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1147
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582840512,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:671",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_mprotect",
        "mm/mprotect.c:__x64_sys_pkey_mprotect",
        "mm/mprotect.c:__ia32_sys_mprotect",
        "mm/mprotect.c:__x64_sys_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582840512,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1201
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583055968,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:689",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_mprotect",
        "mm/mprotect.c:__x64_sys_pkey_mprotect",
        "mm/mprotect.c:__ia32_sys_mprotect",
        "mm/mprotect.c:__x64_sys_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583055968,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1489
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583237680,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:680",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_mprotect",
        "mm/mprotect.c:__x64_sys_pkey_mprotect",
        "mm/mprotect.c:__ia32_sys_mprotect",
        "mm/mprotect.c:__x64_sys_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583237680,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1499
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492800548,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:486",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:__arm64_sys_mprotect"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226614132,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:486",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:__se_sys_mprotect"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286173664,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:486",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:__se_sys_mprotect"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272766832,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:486",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:__se_sys_mprotect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581365504,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:486",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_mprotect",
        "mm/mprotect.c:__x64_sys_pkey_mprotect",
        "mm/mprotect.c:__ia32_sys_mprotect",
        "mm/mprotect.c:__x64_sys_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581365504,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581309008,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:486",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_mprotect",
        "mm/mprotect.c:__x64_sys_pkey_mprotect",
        "mm/mprotect.c:__ia32_sys_mprotect",
        "mm/mprotect.c:__x64_sys_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581309008,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581356704,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:486",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_mprotect",
        "mm/mprotect.c:__x64_sys_pkey_mprotect",
        "mm/mprotect.c:__ia32_sys_mprotect",
        "mm/mprotect.c:__x64_sys_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356704,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```

```json
{
  "name": "do_mprotect_pkey",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581420624,
      "name": "do_mprotect_pkey",
      "external": false,
      "loc": "mm/mprotect.c:486",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_mprotect",
        "mm/mprotect.c:__x64_sys_pkey_mprotect",
        "mm/mprotect.c:__ia32_sys_mprotect",
        "mm/mprotect.c:__x64_sys_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581420624,
      "name": "do_mprotect_pkey",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int do_mprotect_pkey(long unsigned int start, size_t len, long unsigned int prot, int pkey)
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
