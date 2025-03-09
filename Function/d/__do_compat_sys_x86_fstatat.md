# Function: <code>__do_compat_sys_x86_fstatat</code>

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
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char * filename, struct stat64 * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_x86_fstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579390304,
      "name": "__do_compat_sys_x86_fstatat",
      "external": false,
      "loc": "arch/x86/ia32/sys_ia32.c:131",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstatat",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390304,
      "name": "__do_compat_sys_x86_fstatat",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char * filename, struct stat64 * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_x86_fstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579418320,
      "name": "__do_compat_sys_x86_fstatat",
      "external": false,
      "loc": "arch/x86/ia32/sys_ia32.c:131",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstatat",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418320,
      "name": "__do_compat_sys_x86_fstatat",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char * filename, struct stat64 * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_x86_fstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579434192,
      "name": "__do_compat_sys_x86_fstatat",
      "external": false,
      "loc": "arch/x86/ia32/sys_ia32.c:131",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstatat",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579434192,
      "name": "__do_compat_sys_x86_fstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char * filename, struct stat64 * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_x86_fstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579437104,
      "name": "__do_compat_sys_x86_fstatat",
      "external": false,
      "loc": "arch/x86/ia32/sys_ia32.c:131",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstatat",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579437104,
      "name": "__do_compat_sys_x86_fstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char * filename, struct stat64 * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_x86_fstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579432944,
      "name": "__do_compat_sys_x86_fstatat",
      "external": false,
      "loc": "arch/x86/ia32/sys_ia32.c:131",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstatat",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432944,
      "name": "__do_compat_sys_x86_fstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char * filename, struct stat64 * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_x86_fstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579362048,
      "name": "__do_compat_sys_x86_fstatat",
      "external": false,
      "loc": "arch/x86/ia32/sys_ia32.c:131",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstatat",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362048,
      "name": "__do_compat_sys_x86_fstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char * filename, struct stat64 * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_x86_fstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579432864,
      "name": "__do_compat_sys_x86_fstatat",
      "external": false,
      "loc": "arch/x86/ia32/sys_ia32.c:131",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstatat",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432864,
      "name": "__do_compat_sys_x86_fstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char * filename, struct stat64 * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_x86_fstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579442048,
      "name": "__do_compat_sys_x86_fstatat",
      "external": false,
      "loc": "arch/x86/ia32/sys_ia32.c:131",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fstatat",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579442048,
      "name": "__do_compat_sys_x86_fstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char * filename, struct stat64 * statbuf, int flag)
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
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char * filename, struct stat64 * statbuf, int flag)
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
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char * filename, struct stat64 * statbuf, int flag)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char * filename, struct stat64 * statbuf, int flag)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char * filename, struct stat64 * statbuf, int flag)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int __do_compat_sys_x86_fstatat(unsigned int dfd, const char * filename, struct stat64 * statbuf, int flag)
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
