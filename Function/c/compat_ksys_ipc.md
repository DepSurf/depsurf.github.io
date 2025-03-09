# Function: <code>compat_ksys_ipc</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```

```json
{
  "name": "compat_ksys_ipc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583197232,
      "name": "compat_ksys_ipc",
      "external": true,
      "loc": "ipc/syscall.c:130",
      "file": "ipc/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197232,
      "name": "compat_ksys_ipc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```

```json
{
  "name": "compat_ksys_ipc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583303024,
      "name": "compat_ksys_ipc",
      "external": true,
      "loc": "ipc/syscall.c:130",
      "file": "ipc/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583303024,
      "name": "compat_ksys_ipc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```

```json
{
  "name": "compat_ksys_ipc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583634224,
      "name": "compat_ksys_ipc",
      "external": true,
      "loc": "ipc/syscall.c:130",
      "file": "ipc/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583634224,
      "name": "compat_ksys_ipc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```

```json
{
  "name": "compat_ksys_ipc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583755120,
      "name": "compat_ksys_ipc",
      "external": true,
      "loc": "ipc/syscall.c:130",
      "file": "ipc/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583755120,
      "name": "compat_ksys_ipc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```

```json
{
  "name": "compat_ksys_ipc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583779216,
      "name": "compat_ksys_ipc",
      "external": true,
      "loc": "ipc/syscall.c:130",
      "file": "ipc/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583779216,
      "name": "compat_ksys_ipc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
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
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```

```json
{
  "name": "compat_ksys_ipc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584141376,
      "name": "compat_ksys_ipc",
      "external": true,
      "loc": "ipc/syscall.c:130",
      "file": "ipc/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/syscall.c:__x64_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584141376,
      "name": "compat_ksys_ipc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
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
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```

```json
{
  "name": "compat_ksys_ipc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584739184,
      "name": "compat_ksys_ipc",
      "external": true,
      "loc": "ipc/syscall.c:130",
      "file": "ipc/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584739184,
      "name": "compat_ksys_ipc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 645
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
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```

```json
{
  "name": "compat_ksys_ipc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585433312,
      "name": "compat_ksys_ipc",
      "external": true,
      "loc": "ipc/syscall.c:130",
      "file": "ipc/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585433312,
      "name": "compat_ksys_ipc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 645
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
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```

```json
{
  "name": "compat_ksys_ipc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585664080,
      "name": "compat_ksys_ipc",
      "external": true,
      "loc": "ipc/syscall.c:130",
      "file": "ipc/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585664080,
      "name": "compat_ksys_ipc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```

```json
{
  "name": "compat_ksys_ipc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585910896,
      "name": "compat_ksys_ipc",
      "external": true,
      "loc": "ipc/syscall.c:130",
      "file": "ipc/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585910896,
      "name": "compat_ksys_ipc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```

```json
{
  "name": "compat_ksys_ipc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288929744,
      "name": "compat_ksys_ipc",
      "external": true,
      "loc": "ipc/syscall.c:130",
      "file": "ipc/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/syscall.c:__se_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288929744,
      "name": "compat_ksys_ipc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1136
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```

```json
{
  "name": "compat_ksys_ipc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583271760,
      "name": "compat_ksys_ipc",
      "external": true,
      "loc": "ipc/syscall.c:130",
      "file": "ipc/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271760,
      "name": "compat_ksys_ipc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```

```json
{
  "name": "compat_ksys_ipc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583208896,
      "name": "compat_ksys_ipc",
      "external": true,
      "loc": "ipc/syscall.c:130",
      "file": "ipc/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583208896,
      "name": "compat_ksys_ipc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```

```json
{
  "name": "compat_ksys_ipc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583255792,
      "name": "compat_ksys_ipc",
      "external": true,
      "loc": "ipc/syscall.c:130",
      "file": "ipc/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583255792,
      "name": "compat_ksys_ipc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```

```json
{
  "name": "compat_ksys_ipc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583350320,
      "name": "compat_ksys_ipc",
      "external": true,
      "loc": "ipc/syscall.c:130",
      "file": "ipc/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583350320,
      "name": "compat_ksys_ipc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```
</details>
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
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
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
int compat_ksys_ipc(u32 call, int first, int second, u32 third, compat_uptr_t ptr, u32 fifth)
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
