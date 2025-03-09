# Function: <code>map_lookup_and_delete_elem</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580697312,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1013",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580770111,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1090",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580821404,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1103",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int map_lookup_and_delete_elem(union bpf_attr * attr)
```

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580930784,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1460",
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
      "addr": 18446744071580930784,
      "name": "map_lookup_and_delete_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
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
int map_lookup_and_delete_elem(union bpf_attr * attr)
```

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580927408,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1473",
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
      "addr": 18446744071580927408,
      "name": "map_lookup_and_delete_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
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
int map_lookup_and_delete_elem(union bpf_attr * attr)
```

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580929712,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1474",
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
      "addr": 18446744071580929712,
      "name": "map_lookup_and_delete_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int map_lookup_and_delete_elem(union bpf_attr * attr)
```

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1514",
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
      "addr": 18446744071581133952,
      "name": "map_lookup_and_delete_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
    },
    {
      "addr": 18446744071592180385,
      "name": "map_lookup_and_delete_elem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int map_lookup_and_delete_elem(union bpf_attr * attr)
```

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1758",
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
      "addr": 18446744071581406528,
      "name": "map_lookup_and_delete_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 885
    },
    {
      "addr": 18446744071593954339,
      "name": "map_lookup_and_delete_elem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
int map_lookup_and_delete_elem(union bpf_attr * attr)
```

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1792",
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
      "addr": 18446744071581759312,
      "name": "map_lookup_and_delete_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 908
    },
    {
      "addr": 18446744071596013811,
      "name": "map_lookup_and_delete_elem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int map_lookup_and_delete_elem(union bpf_attr * attr)
```

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1869",
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
      "addr": 18446744071581920288,
      "name": "map_lookup_and_delete_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 886
    },
    {
      "addr": 18446744071596533832,
      "name": "map_lookup_and_delete_elem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int map_lookup_and_delete_elem(union bpf_attr * attr)
```

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1909",
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
      "addr": 18446744071582046688,
      "name": "map_lookup_and_delete_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 886
    },
    {
      "addr": 18446744071597434684,
      "name": "map_lookup_and_delete_elem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492144716,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1103",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226039980,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1103",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285351344,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1103",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272306454,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1103",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580790204,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1103",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580736380,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1103",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580781452,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1103",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_lookup_and_delete_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580839702,
      "name": "map_lookup_and_delete_elem",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1103",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int map_lookup_and_delete_elem(union bpf_attr * attr)
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
