# Function: <code>madvise_inject_error</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580986760,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:612",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:SyS_madvise"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581089994,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:622",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:SyS_madvise"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int madvise_inject_error(int behavior, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:622",
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
      "addr": 18446744071581224464,
      "name": "madvise_inject_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    },
    {
      "addr": 18446744071581231236,
      "name": "madvise_inject_error.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int madvise_inject_error(int behavior, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:623",
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
      "addr": 18446744071581308000,
      "name": "madvise_inject_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071581314219,
      "name": "madvise_inject_error.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581422518,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:624",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise"
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
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581483819,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:868",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int madvise_inject_error(int behavior, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:869",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581686896,
      "name": "madvise_inject_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    },
    {
      "addr": 18446744071581694624,
      "name": "madvise_inject_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581734703,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:877",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581763111,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:878",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582045619,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:937",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int madvise_inject_error(int behavior, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:1082",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:do_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582474080,
      "name": "madvise_inject_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071593986007,
      "name": "madvise_inject_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int madvise_inject_error(int behavior, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:1114",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:do_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582988224,
      "name": "madvise_inject_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
    },
    {
      "addr": 18446744071596038320,
      "name": "madvise_inject_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583208234,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:1116",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:do_madvise"
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
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583443802,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:1110",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:do_madvise"
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
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492902240,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:868",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286303176,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:868",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581452667,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:868",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise"
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
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581394987,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:868",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise"
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
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581443867,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:868",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise"
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
  "name": "madvise_inject_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581508347,
      "name": "madvise_inject_error",
      "external": false,
      "loc": "mm/madvise.c:868",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise"
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int madvise_inject_error(int behavior, long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int madvise_inject_error(int behavior, long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int madvise_inject_error(int behavior, long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int madvise_inject_error(int behavior, long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int madvise_inject_error(int behavior, long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int madvise_inject_error(int behavior, long unsigned int start, long unsigned int end)
```
</details>
</li>
</ul>
