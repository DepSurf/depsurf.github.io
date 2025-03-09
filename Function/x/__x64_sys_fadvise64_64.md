# Function: <code>__x64_sys_fadvise64_64</code>

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
long int __x64_sys_fadvise64_64(const struct pt_regs * regs)
```

```json
{
  "name": "__x64_sys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581223312,
      "name": "__x64_sys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:193",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581223312,
      "name": "__x64_sys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
long int __x64_sys_fadvise64_64(const struct pt_regs * regs)
```

```json
{
  "name": "__x64_sys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580967664,
      "name": "__x64_sys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:207",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580967664,
      "name": "__x64_sys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
long int __x64_sys_fadvise64_64(const struct pt_regs * regs)
```

```json
{
  "name": "__x64_sys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581062768,
      "name": "__x64_sys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:207",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581062768,
      "name": "__x64_sys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579676320,
      "name": "__x64_sys_fadvise64_64",
      "external": true,
      "loc": "kernel/sys_ni.c:270",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118544,
      "name": "__x64_sys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581302304,
      "name": "__x64_sys_fadvise64_64",
      "external": true,
      "loc": "kernel/sys_ni.c:270",
      "file": "kernel/sys_ni.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302304,
      "name": "__x64_sys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581345520,
      "name": "__x64_sys_fadvise64_64",
      "external": true,
      "loc": "kernel/sys_ni.c:272",
      "file": "kernel/sys_ni.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345520,
      "name": "__x64_sys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581364608,
      "name": "__x64_sys_fadvise64_64",
      "external": true,
      "loc": "kernel/sys_ni.c:278",
      "file": "kernel/sys_ni.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581364608,
      "name": "__x64_sys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581612992,
      "name": "__x64_sys_fadvise64_64",
      "external": true,
      "loc": "kernel/sys_ni.c:278",
      "file": "kernel/sys_ni.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612992,
      "name": "__x64_sys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581973248,
      "name": "__x64_sys_fadvise64_64",
      "external": true,
      "loc": "kernel/sys_ni.c:279",
      "file": "kernel/sys_ni.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581973248,
      "name": "__x64_sys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582407824,
      "name": "__x64_sys_fadvise64_64",
      "external": true,
      "loc": "kernel/sys_ni.c:279",
      "file": "kernel/sys_ni.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582407824,
      "name": "__x64_sys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582613872,
      "name": "__x64_sys_fadvise64_64",
      "external": true,
      "loc": "kernel/sys_ni.c:171",
      "file": "kernel/sys_ni.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582613872,
      "name": "__x64_sys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582785440,
      "name": "__x64_sys_fadvise64_64",
      "external": true,
      "loc": "kernel/sys_ni.c:172",
      "file": "kernel/sys_ni.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582785440,
      "name": "__x64_sys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579652640,
      "name": "__x64_sys_fadvise64_64",
      "external": true,
      "loc": "kernel/sys_ni.c:270",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087392,
      "name": "__x64_sys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579580992,
      "name": "__x64_sys_fadvise64_64",
      "external": true,
      "loc": "kernel/sys_ni.c:270",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034576,
      "name": "__x64_sys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579649904,
      "name": "__x64_sys_fadvise64_64",
      "external": true,
      "loc": "kernel/sys_ni.c:270",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078592,
      "name": "__x64_sys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
```

```json
{
  "name": "__x64_sys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683760,
      "name": "__x64_sys_fadvise64_64",
      "external": true,
      "loc": "kernel/sys_ni.c:270",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140480,
      "name": "__x64_sys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
long int __x64_sys_fadvise64_64(const struct pt_regs * regs)
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
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int __x64_sys_fadvise64_64(const struct pt_regs * __unused)
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
