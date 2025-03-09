# Function: <code>__do_compat_sys_x86_fstat64</code>

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
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 * statbuf)
```

```json
{
  "name": "__do_compat_sys_x86_fstat64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579390480,
      "name": "__do_compat_sys_x86_fstat64",
      "external": false,
      "loc": "arch/x86/ia32/sys_ia32.c:121",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstat64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstat64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390480,
      "name": "__do_compat_sys_x86_fstat64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 * statbuf)
```

```json
{
  "name": "__do_compat_sys_x86_fstat64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579418496,
      "name": "__do_compat_sys_x86_fstat64",
      "external": false,
      "loc": "arch/x86/ia32/sys_ia32.c:121",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstat64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstat64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418496,
      "name": "__do_compat_sys_x86_fstat64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 * statbuf)
```

```json
{
  "name": "__do_compat_sys_x86_fstat64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579434368,
      "name": "__do_compat_sys_x86_fstat64",
      "external": false,
      "loc": "arch/x86/ia32/sys_ia32.c:121",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstat64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstat64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579434368,
      "name": "__do_compat_sys_x86_fstat64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 * statbuf)
```

```json
{
  "name": "__do_compat_sys_x86_fstat64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579437280,
      "name": "__do_compat_sys_x86_fstat64",
      "external": false,
      "loc": "arch/x86/ia32/sys_ia32.c:121",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstat64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstat64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579437280,
      "name": "__do_compat_sys_x86_fstat64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 * statbuf)
```

```json
{
  "name": "__do_compat_sys_x86_fstat64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579433120,
      "name": "__do_compat_sys_x86_fstat64",
      "external": false,
      "loc": "arch/x86/ia32/sys_ia32.c:121",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstat64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstat64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433120,
      "name": "__do_compat_sys_x86_fstat64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 * statbuf)
```

```json
{
  "name": "__do_compat_sys_x86_fstat64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579362224,
      "name": "__do_compat_sys_x86_fstat64",
      "external": false,
      "loc": "arch/x86/ia32/sys_ia32.c:121",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstat64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstat64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362224,
      "name": "__do_compat_sys_x86_fstat64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 * statbuf)
```

```json
{
  "name": "__do_compat_sys_x86_fstat64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579433040,
      "name": "__do_compat_sys_x86_fstat64",
      "external": false,
      "loc": "arch/x86/ia32/sys_ia32.c:121",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstat64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstat64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433040,
      "name": "__do_compat_sys_x86_fstat64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 * statbuf)
```

```json
{
  "name": "__do_compat_sys_x86_fstat64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579442224,
      "name": "__do_compat_sys_x86_fstat64",
      "external": false,
      "loc": "arch/x86/ia32/sys_ia32.c:121",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstat64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstat64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579442224,
      "name": "__do_compat_sys_x86_fstat64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 * statbuf)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 * statbuf)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 * statbuf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 * statbuf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 * statbuf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int __do_compat_sys_x86_fstat64(unsigned int fd, struct stat64 * statbuf)
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
