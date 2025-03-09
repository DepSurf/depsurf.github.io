# Function: <code>set_fd_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int set_fd_set(long unsigned int nr, void * ufdset, long unsigned int * fdset)
```

```json
{
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581076608,
      "name": "set_fd_set",
      "external": false,
      "loc": "include/linux/poll.h:141",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581076608,
      "name": "set_fd_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long unsigned int set_fd_set(long unsigned int nr, void * ufdset, long unsigned int * fdset)
```

```json
{
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581239520,
      "name": "set_fd_set",
      "external": false,
      "loc": "include/linux/poll.h:141",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581239520,
      "name": "set_fd_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int set_fd_set(long unsigned int nr, void * ufdset, long unsigned int * fdset)
```

```json
{
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581317392,
      "name": "set_fd_set",
      "external": false,
      "loc": "include/linux/poll.h:141",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317392,
      "name": "set_fd_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long unsigned int set_fd_set(long unsigned int nr, void * ufdset, long unsigned int * fdset)
```

```json
{
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581370208,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:375",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581370208,
      "name": "set_fd_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long unsigned int set_fd_set(long unsigned int nr, void * ufdset, long unsigned int * fdset)
```

```json
{
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581511696,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:374",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581511696,
      "name": "set_fd_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581678962,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:373",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
      ],
      "caller_func": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581669952,
      "name": "set_fd_set.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581765552,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:398",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581882890,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:400",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
      ],
      "caller_func": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581873888,
      "name": "set_fd_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581954984,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:400",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582187128,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:400",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582234573,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:400",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582260409,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:400",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582578297,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:400",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583107047,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:401",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583675575,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:401",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583893355,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:401",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584100519,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:401",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493450964,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:400",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
      ],
      "caller_func": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493440840,
      "name": "set_fd_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227017916,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:400",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287006048,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:400",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273135276,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:400",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581923720,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:400",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581861304,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:400",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581915032,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:400",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
  "name": "set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581984674,
      "name": "set_fd_set",
      "external": false,
      "loc": "fs/select.c:400",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:core_sys_select"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
long unsigned int set_fd_set(long unsigned int nr, void * ufdset, long unsigned int * fdset)
```
</details>
</li>
</ul>
