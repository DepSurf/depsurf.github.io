# Function: <code>__sys_setuid</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528368,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:569",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setuid",
        "kernel/sys.c:__x64_sys_setuid",
        "kernel/uid16.c:__ia32_sys_setuid16",
        "kernel/uid16.c:__x64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528368,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564480,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:569",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setuid",
        "kernel/sys.c:__x64_sys_setuid",
        "kernel/uid16.c:__ia32_sys_setuid16",
        "kernel/uid16.c:__x64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564480,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587440,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:569",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setuid",
        "kernel/sys.c:__x64_sys_setuid",
        "kernel/uid16.c:__ia32_sys_setuid16",
        "kernel/uid16.c:__x64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587440,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579613536,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:569",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setuid",
        "kernel/sys.c:__x64_sys_setuid",
        "kernel/uid16.c:__ia32_sys_setuid16",
        "kernel/uid16.c:__x64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613536,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644624,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:578",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setuid",
        "kernel/sys.c:__x64_sys_setuid",
        "kernel/uid16.c:__ia32_sys_setuid16",
        "kernel/uid16.c:__x64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644624,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579625184,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:579",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setuid",
        "kernel/sys.c:__x64_sys_setuid",
        "kernel/uid16.c:__ia32_sys_setuid16",
        "kernel/uid16.c:__x64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625184,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579631664,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:588",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setuid",
        "kernel/sys.c:__x64_sys_setuid",
        "kernel/uid16.c:__ia32_sys_setuid16",
        "kernel/uid16.c:__x64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631664,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579708080,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:595",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setuid",
        "kernel/sys.c:__x64_sys_setuid",
        "kernel/uid16.c:__ia32_sys_setuid16",
        "kernel/uid16.c:__x64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579708080,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579811056,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:602",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setuid",
        "kernel/sys.c:__x64_sys_setuid",
        "kernel/uid16.c:__ia32_sys_setuid16",
        "kernel/uid16.c:__x64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811056,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579946880,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:603",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setuid",
        "kernel/sys.c:__x64_sys_setuid",
        "kernel/uid16.c:__ia32_sys_setuid16",
        "kernel/uid16.c:__x64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946880,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579996432,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:610",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setuid",
        "kernel/sys.c:__x64_sys_setuid",
        "kernel/uid16.c:__ia32_sys_setuid16",
        "kernel/uid16.c:__x64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579996432,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580035840,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:610",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setuid",
        "kernel/sys.c:__x64_sys_setuid",
        "kernel/uid16.c:__ia32_sys_setuid16",
        "kernel/uid16.c:__x64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035840,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490779520,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:569",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__arm64_sys_setuid",
        "kernel/uid16.c:__arm64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490779520,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224814440,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:569",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setuid",
        "kernel/uid16.c:__se_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224814440,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283604528,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:569",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283604528,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271463138,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:569",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271463138,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579589840,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:569",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setuid",
        "kernel/sys.c:__x64_sys_setuid",
        "kernel/uid16.c:__ia32_sys_setuid16",
        "kernel/uid16.c:__x64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589840,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579518480,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:569",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setuid",
        "kernel/sys.c:__x64_sys_setuid",
        "kernel/uid16.c:__ia32_sys_setuid16",
        "kernel/uid16.c:__x64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579518480,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587120,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:569",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setuid",
        "kernel/sys.c:__x64_sys_setuid",
        "kernel/uid16.c:__ia32_sys_setuid16",
        "kernel/uid16.c:__x64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587120,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
long int __sys_setuid(uid_t uid)
```

```json
{
  "name": "__sys_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579620768,
      "name": "__sys_setuid",
      "external": true,
      "loc": "kernel/sys.c:569",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setuid",
        "kernel/sys.c:__x64_sys_setuid",
        "kernel/uid16.c:__ia32_sys_setuid16",
        "kernel/uid16.c:__x64_sys_setuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579620768,
      "name": "__sys_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
long int __sys_setuid(uid_t uid)
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
