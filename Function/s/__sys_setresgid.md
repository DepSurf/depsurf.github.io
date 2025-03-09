# Function: <code>__sys_setresgid</code>

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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579529200,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:713",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setresgid",
        "kernel/sys.c:__x64_sys_setresgid",
        "kernel/uid16.c:__ia32_sys_setresgid16",
        "kernel/uid16.c:__x64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529200,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565312,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:713",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setresgid",
        "kernel/sys.c:__x64_sys_setresgid",
        "kernel/uid16.c:__ia32_sys_setresgid16",
        "kernel/uid16.c:__x64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565312,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588272,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:713",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setresgid",
        "kernel/sys.c:__x64_sys_setresgid",
        "kernel/uid16.c:__ia32_sys_setresgid16",
        "kernel/uid16.c:__x64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588272,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579614368,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:713",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setresgid",
        "kernel/sys.c:__x64_sys_setresgid",
        "kernel/uid16.c:__ia32_sys_setresgid16",
        "kernel/uid16.c:__x64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614368,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645456,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:722",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setresgid",
        "kernel/sys.c:__x64_sys_setresgid",
        "kernel/uid16.c:__ia32_sys_setresgid16",
        "kernel/uid16.c:__x64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645456,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579626016,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:723",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setresgid",
        "kernel/sys.c:__x64_sys_setresgid",
        "kernel/uid16.c:__ia32_sys_setresgid16",
        "kernel/uid16.c:__x64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626016,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579632528,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:740",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setresgid",
        "kernel/sys.c:__x64_sys_setresgid",
        "kernel/uid16.c:__ia32_sys_setresgid16",
        "kernel/uid16.c:__x64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579632528,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579709056,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:749",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setresgid",
        "kernel/sys.c:__x64_sys_setresgid",
        "kernel/uid16.c:__ia32_sys_setresgid16",
        "kernel/uid16.c:__x64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709056,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579812624,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:756",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setresgid",
        "kernel/sys.c:__x64_sys_setresgid",
        "kernel/uid16.c:__ia32_sys_setresgid16",
        "kernel/uid16.c:__x64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812624,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 828
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579948544,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:757",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setresgid",
        "kernel/sys.c:__x64_sys_setresgid",
        "kernel/uid16.c:__ia32_sys_setresgid16",
        "kernel/uid16.c:__x64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948544,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 828
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579998128,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:769",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setresgid",
        "kernel/sys.c:__x64_sys_setresgid",
        "kernel/uid16.c:__ia32_sys_setresgid16",
        "kernel/uid16.c:__x64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998128,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1051
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580037536,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:769",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setresgid",
        "kernel/sys.c:__x64_sys_setresgid",
        "kernel/uid16.c:__ia32_sys_setresgid16",
        "kernel/uid16.c:__x64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037536,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1051
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490780440,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:713",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__arm64_sys_setresgid",
        "kernel/uid16.c:__arm64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490780440,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224815564,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:713",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setresgid",
        "kernel/uid16.c:__se_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224815564,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283605632,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:713",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setresgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283605632,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271464104,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:713",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setresgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271464104,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579590672,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:713",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setresgid",
        "kernel/sys.c:__x64_sys_setresgid",
        "kernel/uid16.c:__ia32_sys_setresgid16",
        "kernel/uid16.c:__x64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590672,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579519312,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:713",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setresgid",
        "kernel/sys.c:__x64_sys_setresgid",
        "kernel/uid16.c:__ia32_sys_setresgid16",
        "kernel/uid16.c:__x64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519312,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587952,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:713",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setresgid",
        "kernel/sys.c:__x64_sys_setresgid",
        "kernel/uid16.c:__ia32_sys_setresgid16",
        "kernel/uid16.c:__x64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587952,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
```

```json
{
  "name": "__sys_setresgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579621600,
      "name": "__sys_setresgid",
      "external": true,
      "loc": "kernel/sys.c:713",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setresgid",
        "kernel/sys.c:__x64_sys_setresgid",
        "kernel/uid16.c:__ia32_sys_setresgid16",
        "kernel/uid16.c:__x64_sys_setresgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621600,
      "name": "__sys_setresgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
long int __sys_setresgid(gid_t rgid, gid_t egid, gid_t sgid)
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
