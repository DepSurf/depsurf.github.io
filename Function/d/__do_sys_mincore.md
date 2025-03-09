# Function: <code>__do_sys_mincore</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581146948,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:224",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581226772,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:224",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581300676,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:253",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581359365,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:252",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char * vec)
```

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581557024,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:253",
      "file": "mm/mincore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581557024,
      "name": "__do_sys_mincore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char * vec)
```

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581601376,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:229",
      "file": "mm/mincore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581601376,
      "name": "__do_sys_mincore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char * vec)
```

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581623712,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:230",
      "file": "mm/mincore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581623712,
      "name": "__do_sys_mincore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
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
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char * vec)
```

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581891184,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:230",
      "file": "mm/mincore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891184,
      "name": "__do_sys_mincore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 755
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
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char * vec)
```

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582289120,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:232",
      "file": "mm/mincore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582289120,
      "name": "__do_sys_mincore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char * vec)
```

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582782336,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:232",
      "file": "mm/mincore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582782336,
      "name": "__do_sys_mincore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582998770,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:232",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
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
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583178146,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:232",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
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
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char * vec)
```

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492765448,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:252",
      "file": "mm/mincore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__arm64_sys_mincore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492765448,
      "name": "__do_sys_mincore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 984
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226584888,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:252",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__se_sys_mincore"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286128568,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:252",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__se_sys_mincore"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272743572,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:252",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__se_sys_mincore"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581328213,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:252",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581272037,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:252",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581319413,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:252",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_mincore",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581383397,
      "name": "__do_sys_mincore",
      "external": false,
      "loc": "mm/mincore.c:252",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char * vec)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char * vec)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
long int __do_sys_mincore(long unsigned int start, size_t len, unsigned char * vec)
```
</details>
</li>
</ul>
