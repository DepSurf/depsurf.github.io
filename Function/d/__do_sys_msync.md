# Function: <code>__do_sys_msync</code>

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
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581187834,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync"
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
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581270810,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync"
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
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581345328,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync"
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
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581404640,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync"
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
long int __do_sys_msync(long unsigned int start, size_t len, int flags)
```

```json
{
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581602960,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581602960,
      "name": "__do_sys_msync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
long int __do_sys_msync(long unsigned int start, size_t len, int flags)
```

```json
{
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581650080,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650080,
      "name": "__do_sys_msync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
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
long int __do_sys_msync(long unsigned int start, size_t len, int flags)
```

```json
{
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581671296,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581671296,
      "name": "__do_sys_msync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
long int __do_sys_msync(long unsigned int start, size_t len, int flags)
```

```json
{
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581940592,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581940592,
      "name": "__do_sys_msync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
long int __do_sys_msync(long unsigned int start, size_t len, int flags)
```

```json
{
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582349712,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349712,
      "name": "__do_sys_msync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 742
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
long int __do_sys_msync(long unsigned int start, size_t len, int flags)
```

```json
{
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582851392,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582851392,
      "name": "__do_sys_msync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
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
long int __do_sys_msync(long unsigned int start, size_t len, int flags)
```

```json
{
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583067376,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583067376,
      "name": "__do_sys_msync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
long int __do_sys_msync(long unsigned int start, size_t len, int flags)
```

```json
{
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583249312,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583249312,
      "name": "__do_sys_msync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492805688,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__arm64_sys_msync"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226618464,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__se_sys_msync"
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
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286181584,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__se_sys_msync"
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
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272770158,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__se_sys_msync"
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
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581373488,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync"
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
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581316896,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync"
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
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581364688,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync"
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
  "name": "__do_sys_msync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581428592,
      "name": "__do_sys_msync",
      "external": false,
      "loc": "mm/msync.c:32",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync"
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
long int __do_sys_msync(long unsigned int start, size_t len, int flags)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
