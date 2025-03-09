# Function: <code>__sys_setregid</code>

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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527120,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:350",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setregid",
        "kernel/sys.c:__x64_sys_setregid",
        "kernel/uid16.c:__ia32_sys_setregid16",
        "kernel/uid16.c:__x64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527120,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579563232,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:350",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setregid",
        "kernel/sys.c:__x64_sys_setregid",
        "kernel/uid16.c:__ia32_sys_setregid16",
        "kernel/uid16.c:__x64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563232,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579586128,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:350",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setregid",
        "kernel/sys.c:__x64_sys_setregid",
        "kernel/uid16.c:__ia32_sys_setregid16",
        "kernel/uid16.c:__x64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579586128,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579612224,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:350",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setregid",
        "kernel/sys.c:__x64_sys_setregid",
        "kernel/uid16.c:__ia32_sys_setregid16",
        "kernel/uid16.c:__x64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612224,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643280,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:351",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setregid",
        "kernel/sys.c:__x64_sys_setregid",
        "kernel/uid16.c:__ia32_sys_setregid16",
        "kernel/uid16.c:__x64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643280,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579623840,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:352",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setregid",
        "kernel/sys.c:__x64_sys_setregid",
        "kernel/uid16.c:__ia32_sys_setregid16",
        "kernel/uid16.c:__x64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579623840,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579630304,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:357",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setregid",
        "kernel/sys.c:__x64_sys_setregid",
        "kernel/uid16.c:__ia32_sys_setregid16",
        "kernel/uid16.c:__x64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630304,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706704,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:357",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setregid",
        "kernel/sys.c:__x64_sys_setregid",
        "kernel/uid16.c:__ia32_sys_setregid16",
        "kernel/uid16.c:__x64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706704,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579809328,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:364",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setregid",
        "kernel/sys.c:__x64_sys_setregid",
        "kernel/uid16.c:__ia32_sys_setregid16",
        "kernel/uid16.c:__x64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809328,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579945008,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:365",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setregid",
        "kernel/sys.c:__x64_sys_setregid",
        "kernel/uid16.c:__ia32_sys_setregid16",
        "kernel/uid16.c:__x64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945008,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579994608,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:372",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setregid",
        "kernel/sys.c:__x64_sys_setregid",
        "kernel/uid16.c:__ia32_sys_setregid16",
        "kernel/uid16.c:__x64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994608,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034016,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:372",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setregid",
        "kernel/sys.c:__x64_sys_setregid",
        "kernel/uid16.c:__ia32_sys_setregid16",
        "kernel/uid16.c:__x64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034016,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490778264,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:350",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__arm64_sys_setregid",
        "kernel/uid16.c:__arm64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490778264,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224813268,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:350",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setregid",
        "kernel/uid16.c:__se_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224813268,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283603040,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:350",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setregid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283603040,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271462102,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:350",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setregid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271462102,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588528,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:350",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setregid",
        "kernel/sys.c:__x64_sys_setregid",
        "kernel/uid16.c:__ia32_sys_setregid16",
        "kernel/uid16.c:__x64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588528,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579517168,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:350",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setregid",
        "kernel/sys.c:__x64_sys_setregid",
        "kernel/uid16.c:__ia32_sys_setregid16",
        "kernel/uid16.c:__x64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517168,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579585808,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:350",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setregid",
        "kernel/sys.c:__x64_sys_setregid",
        "kernel/uid16.c:__ia32_sys_setregid16",
        "kernel/uid16.c:__x64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585808,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
long int __sys_setregid(gid_t rgid, gid_t egid)
```

```json
{
  "name": "__sys_setregid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579619456,
      "name": "__sys_setregid",
      "external": true,
      "loc": "kernel/sys.c:350",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setregid",
        "kernel/sys.c:__x64_sys_setregid",
        "kernel/uid16.c:__ia32_sys_setregid16",
        "kernel/uid16.c:__x64_sys_setregid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619456,
      "name": "__sys_setregid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
long int __sys_setregid(gid_t rgid, gid_t egid)
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
