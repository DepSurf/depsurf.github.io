# Function: <code>map_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580366796,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:136",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580424605,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:178",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580474109,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:219",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580494367,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:273",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
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
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580548623,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:383",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580635488,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:432",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__ia32_sys_bpf",
        "kernel/bpf/syscall.c:__x64_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635488,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 858
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
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580696793,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:489",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580762832,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:547",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580762832,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1194
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580813776,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:550",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580813776,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1194
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580937216,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:790",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580937216,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 841
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933920,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:799",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933920,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 866
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936624,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:800",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936624,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 866
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140464,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:826",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140464,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 895
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581414752,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1049",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414752,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1429
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581768896,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1089",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581768896,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 976
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581930688,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1097",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930688,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1116
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582057200,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1128",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057200,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1171
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492134360,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:550",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492134360,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1236
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226033096,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:550",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226033096,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1112
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285342592,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:550",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285342592,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1484
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272300382,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:550",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272300382,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580782576,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:550",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580782576,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1194
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580728752,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:550",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580728752,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1194
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580773824,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:550",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580773824,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1194
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
int map_create(union bpf_attr * attr)
```

```json
{
  "name": "map_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580832048,
      "name": "map_create",
      "external": false,
      "loc": "kernel/bpf/syscall.c:550",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580832048,
      "name": "map_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1217
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
int map_create(union bpf_attr * attr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int map_create(union bpf_attr * attr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int map_create(union bpf_attr * attr)
```
</details>
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
