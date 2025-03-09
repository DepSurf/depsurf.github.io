# Function: <code>compat_get_timeval</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int compat_get_timeval(struct timeval * tv, const void * utv)
```

```json
{
  "name": "compat_get_timeval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579959728,
      "name": "compat_get_timeval",
      "external": true,
      "loc": "kernel/compat.c:157",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959728,
      "name": "compat_get_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int compat_get_timeval(struct timeval * tv, const void * utv)
```

```json
{
  "name": "compat_get_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579988592,
      "name": "compat_get_timeval",
      "external": true,
      "loc": "kernel/compat.c:157",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988592,
      "name": "compat_get_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int compat_get_timeval(struct timeval * tv, const void * utv)
```

```json
{
  "name": "compat_get_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580019120,
      "name": "compat_get_timeval",
      "external": true,
      "loc": "kernel/compat.c:157",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019120,
      "name": "compat_get_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int compat_get_timeval(struct timeval * tv, const void * utv)
```

```json
{
  "name": "compat_get_timeval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580026304,
      "name": "compat_get_timeval",
      "external": true,
      "loc": "kernel/compat.c:167",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:compat_SyS_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026304,
      "name": "compat_get_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int compat_get_timeval(struct timeval * tv, const void * utv)
```

```json
{
  "name": "compat_get_timeval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580073200,
      "name": "compat_get_timeval",
      "external": true,
      "loc": "kernel/compat.c:167",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:compat_SyS_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073200,
      "name": "compat_get_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int compat_get_timeval(struct timeval * tv, const void * utv)
```

```json
{
  "name": "compat_get_timeval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580132528,
      "name": "compat_get_timeval",
      "external": true,
      "loc": "kernel/compat.c:124",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132528,
      "name": "compat_get_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int compat_get_timeval(struct timeval * tv, const void * utv)
```

```json
{
  "name": "compat_get_timeval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580179712,
      "name": "compat_get_timeval",
      "external": true,
      "loc": "kernel/compat.c:124",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580179712,
      "name": "compat_get_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int compat_get_timeval(struct timeval * tv, const void * utv)
```

```json
{
  "name": "compat_get_timeval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580225744,
      "name": "compat_get_timeval",
      "external": true,
      "loc": "kernel/compat.c:57",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580225744,
      "name": "compat_get_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int compat_get_timeval(struct timeval * tv, const void * utv)
```

```json
{
  "name": "compat_get_timeval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580273984,
      "name": "compat_get_timeval",
      "external": true,
      "loc": "kernel/compat.c:57",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580273984,
      "name": "compat_get_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int compat_get_timeval(struct timeval * tv, const void * utv)
```

```json
{
  "name": "compat_get_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491516176,
      "name": "compat_get_timeval",
      "external": true,
      "loc": "kernel/compat.c:57",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__arm64_compat_sys_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491516176,
      "name": "compat_get_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 760
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int compat_get_timeval(struct timeval * tv, const void * utv)
```

```json
{
  "name": "compat_get_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284484192,
      "name": "compat_get_timeval",
      "external": true,
      "loc": "kernel/compat.c:57",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__se_compat_sys_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284484192,
      "name": "compat_get_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int compat_get_timeval(struct timeval * tv, const void * utv)
```

```json
{
  "name": "compat_get_timeval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580242784,
      "name": "compat_get_timeval",
      "external": true,
      "loc": "kernel/compat.c:57",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580242784,
      "name": "compat_get_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int compat_get_timeval(struct timeval * tv, const void * utv)
```

```json
{
  "name": "compat_get_timeval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580190336,
      "name": "compat_get_timeval",
      "external": true,
      "loc": "kernel/compat.c:57",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190336,
      "name": "compat_get_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int compat_get_timeval(struct timeval * tv, const void * utv)
```

```json
{
  "name": "compat_get_timeval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580234032,
      "name": "compat_get_timeval",
      "external": true,
      "loc": "kernel/compat.c:57",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580234032,
      "name": "compat_get_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int compat_get_timeval(struct timeval * tv, const void * utv)
```

```json
{
  "name": "compat_get_timeval",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580287024,
      "name": "compat_get_timeval",
      "external": true,
      "loc": "kernel/compat.c:57",
      "file": "kernel/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287024,
      "name": "compat_get_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int compat_get_timeval(struct timeval * tv, const void * utv)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int compat_get_timeval(struct timeval * tv, const void * utv)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int compat_get_timeval(struct timeval * tv, const void * utv)
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
