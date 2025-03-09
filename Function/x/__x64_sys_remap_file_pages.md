# Function: <code>__x64_sys_remap_file_pages</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs * regs)
```

```json
{
  "name": "__x64_sys_remap_file_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__x64_sys_remap_file_pages",
      "external": true,
      "loc": "mm/mmap.c:2817",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581175764,
      "name": "__x64_sys_remap_file_pages.cold.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071581173888,
      "name": "__x64_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs * regs)
```

```json
{
  "name": "__x64_sys_remap_file_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__x64_sys_remap_file_pages",
      "external": true,
      "loc": "mm/mmap.c:2879",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581256084,
      "name": "__x64_sys_remap_file_pages.cold.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071581254208,
      "name": "__x64_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs * regs)
```

```json
{
  "name": "__x64_sys_remap_file_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__x64_sys_remap_file_pages",
      "external": true,
      "loc": "mm/mmap.c:2885",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330908,
      "name": "__x64_sys_remap_file_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071581329040,
      "name": "__x64_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_remap_file_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579677024,
      "name": "__x64_sys_remap_file_pages",
      "external": true,
      "loc": "kernel/sys_ni.c:283",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390316,
      "name": "__x64_sys_remap_file_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071581388448,
      "name": "__x64_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
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
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_remap_file_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581584448,
      "name": "__x64_sys_remap_file_pages",
      "external": true,
      "loc": "kernel/sys_ni.c:283",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581584448,
      "name": "__x64_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_remap_file_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581630448,
      "name": "__x64_sys_remap_file_pages",
      "external": true,
      "loc": "kernel/sys_ni.c:286",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581630448,
      "name": "__x64_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_remap_file_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581653968,
      "name": "__x64_sys_remap_file_pages",
      "external": true,
      "loc": "kernel/sys_ni.c:292",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653968,
      "name": "__x64_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_remap_file_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581922112,
      "name": "__x64_sys_remap_file_pages",
      "external": true,
      "loc": "kernel/sys_ni.c:293",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581922112,
      "name": "__x64_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_remap_file_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582328720,
      "name": "__x64_sys_remap_file_pages",
      "external": true,
      "loc": "kernel/sys_ni.c:295",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582328720,
      "name": "__x64_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_remap_file_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582828480,
      "name": "__x64_sys_remap_file_pages",
      "external": true,
      "loc": "kernel/sys_ni.c:295",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582828480,
      "name": "__x64_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_remap_file_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583043728,
      "name": "__x64_sys_remap_file_pages",
      "external": true,
      "loc": "kernel/sys_ni.c:187",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583043728,
      "name": "__x64_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_remap_file_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583225552,
      "name": "__x64_sys_remap_file_pages",
      "external": true,
      "loc": "kernel/sys_ni.c:191",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/syscall_64.c:x64_sys_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583225552,
      "name": "__x64_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_remap_file_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653344,
      "name": "__x64_sys_remap_file_pages",
      "external": true,
      "loc": "kernel/sys_ni.c:283",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581359164,
      "name": "__x64_sys_remap_file_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071581357296,
      "name": "__x64_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_remap_file_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579581696,
      "name": "__x64_sys_remap_file_pages",
      "external": true,
      "loc": "kernel/sys_ni.c:283",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302876,
      "name": "__x64_sys_remap_file_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071581301008,
      "name": "__x64_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_remap_file_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579650608,
      "name": "__x64_sys_remap_file_pages",
      "external": true,
      "loc": "kernel/sys_ni.c:283",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581350364,
      "name": "__x64_sys_remap_file_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071581348496,
      "name": "__x64_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_remap_file_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684464,
      "name": "__x64_sys_remap_file_pages",
      "external": true,
      "loc": "kernel/sys_ni.c:283",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414300,
      "name": "__x64_sys_remap_file_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071581412432,
      "name": "__x64_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
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
long int __x64_sys_remap_file_pages(const struct pt_regs * regs)
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct pt_regs * __unused</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct pt_regs * regs</code>
</li>
</ul>
</details>
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
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int __x64_sys_remap_file_pages(const struct pt_regs * __unused)
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
