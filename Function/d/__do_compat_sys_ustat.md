# Function: <code>__do_compat_sys_ustat</code>

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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581814400,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:371",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_ustat",
        "fs/statfs.c:__ia32_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581814400,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581901392,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:381",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_ustat",
        "fs/statfs.c:__ia32_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901392,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582026928,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:395",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_ustat",
        "fs/statfs.c:__ia32_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026928,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582104864,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:386",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_ustat",
        "fs/statfs.c:__ia32_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582104864,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582341280,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:386",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_ustat",
        "fs/statfs.c:__ia32_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582341280,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582392768,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:388",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_ustat",
        "fs/statfs.c:__ia32_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582392768,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582420128,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:391",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_ustat",
        "fs/statfs.c:__ia32_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582420128,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582742944,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:391",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x64_compat_sys_ustat",
        "fs/statfs.c:__ia32_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582742944,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583289568,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:391",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__ia32_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583289568,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583873200,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:391",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__ia32_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583873200,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584094960,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:391",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__ia32_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584094960,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584311104,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:391",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__ia32_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584311104,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493642232,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:386",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__arm64_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493642232,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287234624,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:386",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__se_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287234624,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582073600,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:386",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_ustat",
        "fs/statfs.c:__ia32_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073600,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582011152,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:386",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_ustat",
        "fs/statfs.c:__ia32_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582011152,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064880,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:386",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_ustat",
        "fs/statfs.c:__ia32_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064880,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
```

```json
{
  "name": "__do_compat_sys_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582136624,
      "name": "__do_compat_sys_ustat",
      "external": false,
      "loc": "fs/statfs.c:386",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_ustat",
        "fs/statfs.c:__ia32_compat_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582136624,
      "name": "__do_compat_sys_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
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
long int __do_compat_sys_ustat(unsigned int dev, struct compat_ustat * u)
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
