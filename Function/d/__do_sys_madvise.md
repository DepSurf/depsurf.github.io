# Function: <code>__do_sys_madvise</code>

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
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581224875,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:801",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
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
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581308410,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:802",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior)
```

```json
{
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:803",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581420672,
      "name": "__do_sys_madvise",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2302
    },
    {
      "addr": 18446744071581425054,
      "name": "__do_sys_madvise.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior)
```

```json
{
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1053",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581481600,
      "name": "__do_sys_madvise",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2764
    },
    {
      "addr": 18446744071581489228,
      "name": "__do_sys_madvise.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581689577,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1169",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
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
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581735129,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1156",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
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
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581763556,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1157",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
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
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582046132,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1226",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
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
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582485589,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1421",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
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
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582999973,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1455",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
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
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583208645,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1458",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
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
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583444213,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1452",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492900312,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1053",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__arm64_sys_madvise"
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
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226696956,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1053",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__se_sys_madvise"
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
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286300736,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1053",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__se_sys_madvise"
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
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272830468,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1053",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__se_sys_madvise"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior)
```

```json
{
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1053",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581450448,
      "name": "__do_sys_madvise",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2764
    },
    {
      "addr": 18446744071581458076,
      "name": "__do_sys_madvise.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior)
```

```json
{
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1053",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581392768,
      "name": "__do_sys_madvise",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2764
    },
    {
      "addr": 18446744071581400256,
      "name": "__do_sys_madvise.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior)
```

```json
{
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1053",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581441648,
      "name": "__do_sys_madvise",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2764
    },
    {
      "addr": 18446744071581449276,
      "name": "__do_sys_madvise.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior)
```

```json
{
  "name": "__do_sys_madvise",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_madvise",
      "external": false,
      "loc": "mm/madvise.c:1053",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581506128,
      "name": "__do_sys_madvise",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2764
    },
    {
      "addr": 18446744071581513744,
      "name": "__do_sys_madvise.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior)
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
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int __do_sys_madvise(long unsigned int start, size_t len_in, int behavior)
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
