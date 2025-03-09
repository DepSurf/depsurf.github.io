# Function: <code>__sys_setfsuid</code>

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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579529664,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:797",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setfsuid",
        "kernel/sys.c:__x64_sys_setfsuid",
        "kernel/uid16.c:__ia32_sys_setfsuid16",
        "kernel/uid16.c:__x64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529664,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565776,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:797",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setfsuid",
        "kernel/sys.c:__x64_sys_setfsuid",
        "kernel/uid16.c:__ia32_sys_setfsuid16",
        "kernel/uid16.c:__x64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565776,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588736,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:797",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setfsuid",
        "kernel/sys.c:__x64_sys_setfsuid",
        "kernel/uid16.c:__ia32_sys_setfsuid16",
        "kernel/uid16.c:__x64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588736,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579614832,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:797",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setfsuid",
        "kernel/sys.c:__x64_sys_setfsuid",
        "kernel/uid16.c:__ia32_sys_setfsuid16",
        "kernel/uid16.c:__x64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614832,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645952,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:810",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setfsuid",
        "kernel/sys.c:__x64_sys_setfsuid",
        "kernel/uid16.c:__ia32_sys_setfsuid16",
        "kernel/uid16.c:__x64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645952,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579626512,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:811",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setfsuid",
        "kernel/sys.c:__x64_sys_setfsuid",
        "kernel/uid16.c:__ia32_sys_setfsuid16",
        "kernel/uid16.c:__x64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626512,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579633024,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:828",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setfsuid",
        "kernel/sys.c:__x64_sys_setfsuid",
        "kernel/uid16.c:__ia32_sys_setfsuid16",
        "kernel/uid16.c:__x64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633024,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579709552,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:837",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setfsuid",
        "kernel/sys.c:__x64_sys_setfsuid",
        "kernel/uid16.c:__ia32_sys_setfsuid16",
        "kernel/uid16.c:__x64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709552,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579813552,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:844",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setfsuid",
        "kernel/sys.c:__x64_sys_setfsuid",
        "kernel/uid16.c:__ia32_sys_setfsuid16",
        "kernel/uid16.c:__x64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813552,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579949520,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:845",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setfsuid",
        "kernel/sys.c:__x64_sys_setfsuid",
        "kernel/uid16.c:__ia32_sys_setfsuid16",
        "kernel/uid16.c:__x64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949520,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579999328,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:863",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setfsuid",
        "kernel/sys.c:__x64_sys_setfsuid",
        "kernel/uid16.c:__ia32_sys_setfsuid16",
        "kernel/uid16.c:__x64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999328,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580038736,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:863",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setfsuid",
        "kernel/sys.c:__x64_sys_setfsuid",
        "kernel/uid16.c:__ia32_sys_setfsuid16",
        "kernel/uid16.c:__x64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038736,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490780936,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:797",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__arm64_sys_setfsuid",
        "kernel/uid16.c:__arm64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490780936,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224816312,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:797",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setfsuid",
        "kernel/uid16.c:__se_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224816312,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283606160,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:797",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setfsuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283606160,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271464736,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:797",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setfsuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271464736,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579591136,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:797",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setfsuid",
        "kernel/sys.c:__x64_sys_setfsuid",
        "kernel/uid16.c:__ia32_sys_setfsuid16",
        "kernel/uid16.c:__x64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591136,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579519776,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:797",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setfsuid",
        "kernel/sys.c:__x64_sys_setfsuid",
        "kernel/uid16.c:__ia32_sys_setfsuid16",
        "kernel/uid16.c:__x64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519776,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588416,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:797",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setfsuid",
        "kernel/sys.c:__x64_sys_setfsuid",
        "kernel/uid16.c:__ia32_sys_setfsuid16",
        "kernel/uid16.c:__x64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588416,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
long int __sys_setfsuid(uid_t uid)
```

```json
{
  "name": "__sys_setfsuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579622064,
      "name": "__sys_setfsuid",
      "external": true,
      "loc": "kernel/sys.c:797",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setfsuid",
        "kernel/sys.c:__x64_sys_setfsuid",
        "kernel/uid16.c:__ia32_sys_setfsuid16",
        "kernel/uid16.c:__x64_sys_setfsuid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622064,
      "name": "__sys_setfsuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
long int __sys_setfsuid(uid_t uid)
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
