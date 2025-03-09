# Function: <code>__do_sys_statx</code>

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
long int __do_sys_statx(int dfd, const char * filename, unsigned int flags, unsigned int mask, struct statx * buffer)
```

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581597216,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:566",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581597216,
      "name": "__do_sys_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
long int __do_sys_statx(int dfd, const char * filename, unsigned int flags, unsigned int mask, struct statx * buffer)
```

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581683200,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:569",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581683200,
      "name": "__do_sys_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
long int __do_sys_statx(int dfd, const char * filename, unsigned int flags, unsigned int mask, struct statx * buffer)
```

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581801376,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:571",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581801376,
      "name": "__do_sys_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
long int __do_sys_statx(int dfd, const char * filename, unsigned int flags, unsigned int mask, struct statx * buffer)
```

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581873968,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:571",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581873968,
      "name": "__do_sys_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582102261,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:610",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582148949,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:598",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582173797,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:616",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582491093,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:634",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583013052,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:647",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583576316,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:664",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583792412,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:677",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583998492,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:699",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
long int __do_sys_statx(int dfd, const char * filename, unsigned int flags, unsigned int mask, struct statx * buffer)
```

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493349400,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:571",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__arm64_sys_statx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493349400,
      "name": "__do_sys_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
long int __do_sys_statx(int dfd, const char * filename, unsigned int flags, unsigned int mask, struct statx * buffer)
```

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226940292,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:571",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__se_sys_statx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226940292,
      "name": "__do_sys_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
long int __do_sys_statx(int dfd, const char * filename, unsigned int flags, unsigned int mask, struct statx * buffer)
```

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286891984,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:571",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__se_sys_statx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286891984,
      "name": "__do_sys_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
long int __do_sys_statx(int dfd, const char * filename, unsigned int flags, unsigned int mask, struct statx * buffer)
```

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273074772,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:571",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__se_sys_statx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273074772,
      "name": "__do_sys_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
long int __do_sys_statx(int dfd, const char * filename, unsigned int flags, unsigned int mask, struct statx * buffer)
```

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581842704,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:571",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842704,
      "name": "__do_sys_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
long int __do_sys_statx(int dfd, const char * filename, unsigned int flags, unsigned int mask, struct statx * buffer)
```

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581780368,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:571",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780368,
      "name": "__do_sys_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
long int __do_sys_statx(int dfd, const char * filename, unsigned int flags, unsigned int mask, struct statx * buffer)
```

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581834016,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:571",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834016,
      "name": "__do_sys_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
long int __do_sys_statx(int dfd, const char * filename, unsigned int flags, unsigned int mask, struct statx * buffer)
```

```json
{
  "name": "__do_sys_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581903408,
      "name": "__do_sys_statx",
      "external": false,
      "loc": "fs/stat.c:571",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_statx",
        "fs/stat.c:__x64_sys_statx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581903408,
      "name": "__do_sys_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
long int __do_sys_statx(int dfd, const char * filename, unsigned int flags, unsigned int mask, struct statx * buffer)
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
long int __do_sys_statx(int dfd, const char * filename, unsigned int flags, unsigned int mask, struct statx * buffer)
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
