# Function: <code>__do_sys_getcwd</code>

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
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581809891,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:424",
      "file": "fs/d_path.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd"
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
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581896499,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:424",
      "file": "fs/d_path.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd"
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
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582021571,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:423",
      "file": "fs/d_path.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd"
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
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582099507,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:425",
      "file": "fs/d_path.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd"
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
long int __do_sys_getcwd(char * buf, long unsigned int size)
```

```json
{
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582336816,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:425",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582336816,
      "name": "__do_sys_getcwd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
long int __do_sys_getcwd(char * buf, long unsigned int size)
```

```json
{
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582388288,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:429",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582388288,
      "name": "__do_sys_getcwd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
long int __do_sys_getcwd(char * buf, long unsigned int size)
```

```json
{
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582415648,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:429",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582415648,
      "name": "__do_sys_getcwd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
long int __do_sys_getcwd(char * buf, long unsigned int size)
```

```json
{
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582738128,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:414",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582738128,
      "name": "__do_sys_getcwd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
long int __do_sys_getcwd(char * buf, long unsigned int size)
```

```json
{
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583284384,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:412",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583284384,
      "name": "__do_sys_getcwd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
long int __do_sys_getcwd(char * buf, long unsigned int size)
```

```json
{
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583867600,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:411",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583867600,
      "name": "__do_sys_getcwd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
long int __do_sys_getcwd(char * buf, long unsigned int size)
```

```json
{
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584089360,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:412",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584089360,
      "name": "__do_sys_getcwd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
long int __do_sys_getcwd(char * buf, long unsigned int size)
```

```json
{
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584305456,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:412",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584305456,
      "name": "__do_sys_getcwd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493637064,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:425",
      "file": "fs/d_path.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/d_path.c:__arm64_sys_getcwd"
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
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227176612,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:425",
      "file": "fs/d_path.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/d_path.c:__se_sys_getcwd"
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
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287228016,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:425",
      "file": "fs/d_path.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/d_path.c:__se_sys_getcwd"
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
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273274584,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:425",
      "file": "fs/d_path.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/d_path.c:__se_sys_getcwd"
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
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582068243,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:425",
      "file": "fs/d_path.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd"
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
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582005795,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:425",
      "file": "fs/d_path.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd"
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
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582059523,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:425",
      "file": "fs/d_path.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd"
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
  "name": "__do_sys_getcwd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582131251,
      "name": "__do_sys_getcwd",
      "external": false,
      "loc": "fs/d_path.c:425",
      "file": "fs/d_path.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/d_path.c:__ia32_sys_getcwd",
        "fs/d_path.c:__x64_sys_getcwd"
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
long int __do_sys_getcwd(char * buf, long unsigned int size)
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
