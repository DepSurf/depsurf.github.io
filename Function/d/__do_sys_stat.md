# Function: <code>__do_sys_stat</code>

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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "__do_sys_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595152,
      "name": "__do_sys_stat",
      "external": false,
      "loc": "fs/stat.c:244",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_stat",
        "fs/stat.c:__x64_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595152,
      "name": "__do_sys_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "__do_sys_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581681136,
      "name": "__do_sys_stat",
      "external": false,
      "loc": "fs/stat.c:244",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_stat",
        "fs/stat.c:__x64_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581681136,
      "name": "__do_sys_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "__do_sys_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581799264,
      "name": "__do_sys_stat",
      "external": false,
      "loc": "fs/stat.c:246",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_stat",
        "fs/stat.c:__x64_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799264,
      "name": "__do_sys_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "__do_sys_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581871856,
      "name": "__do_sys_stat",
      "external": false,
      "loc": "fs/stat.c:246",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_stat",
        "fs/stat.c:__x64_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871856,
      "name": "__do_sys_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "__do_sys_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582099616,
      "name": "__do_sys_stat",
      "external": false,
      "loc": "fs/stat.c:266",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_stat",
        "fs/stat.c:__x64_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582099616,
      "name": "__do_sys_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "__do_sys_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582146352,
      "name": "__do_sys_stat",
      "external": false,
      "loc": "fs/stat.c:254",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_stat",
        "fs/stat.c:__x64_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146352,
      "name": "__do_sys_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "__do_sys_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582171200,
      "name": "__do_sys_stat",
      "external": false,
      "loc": "fs/stat.c:272",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_stat",
        "fs/stat.c:__x64_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582171200,
      "name": "__do_sys_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "__do_sys_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582488496,
      "name": "__do_sys_stat",
      "external": false,
      "loc": "fs/stat.c:290",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_stat",
        "fs/stat.c:__x64_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582488496,
      "name": "__do_sys_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "__do_sys_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011216,
      "name": "__do_sys_stat",
      "external": false,
      "loc": "fs/stat.c:304",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_stat",
        "fs/stat.c:__x64_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011216,
      "name": "__do_sys_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "__do_sys_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583574128,
      "name": "__do_sys_stat",
      "external": false,
      "loc": "fs/stat.c:319",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_stat",
        "fs/stat.c:__x64_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583574128,
      "name": "__do_sys_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "__do_sys_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583790224,
      "name": "__do_sys_stat",
      "external": false,
      "loc": "fs/stat.c:325",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_stat",
        "fs/stat.c:__x64_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583790224,
      "name": "__do_sys_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "__do_sys_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583996608,
      "name": "__do_sys_stat",
      "external": false,
      "loc": "fs/stat.c:353",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_stat",
        "fs/stat.c:__x64_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996608,
      "name": "__do_sys_stat",
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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "__do_sys_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581840592,
      "name": "__do_sys_stat",
      "external": false,
      "loc": "fs/stat.c:246",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_stat",
        "fs/stat.c:__x64_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581840592,
      "name": "__do_sys_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "__do_sys_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581778256,
      "name": "__do_sys_stat",
      "external": false,
      "loc": "fs/stat.c:246",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_stat",
        "fs/stat.c:__x64_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581778256,
      "name": "__do_sys_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "__do_sys_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831904,
      "name": "__do_sys_stat",
      "external": false,
      "loc": "fs/stat.c:246",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_stat",
        "fs/stat.c:__x64_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831904,
      "name": "__do_sys_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "__do_sys_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581901296,
      "name": "__do_sys_stat",
      "external": false,
      "loc": "fs/stat.c:246",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_stat",
        "fs/stat.c:__x64_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901296,
      "name": "__do_sys_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int __do_sys_stat(const char * filename, struct __old_kernel_stat * statbuf)
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
