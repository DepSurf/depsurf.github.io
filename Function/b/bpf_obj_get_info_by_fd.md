# Function: <code>bpf_obj_get_info_by_fd</code>

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
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580493367,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1361",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580543904,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1658",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543904,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580633968,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2088",
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
      "addr": 18446744071580633968,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
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
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692208,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2407",
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
      "addr": 18446744071580692208,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
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
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580760864,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2633",
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
      "addr": 18446744071580760864,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580810912,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2658",
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
      "addr": 18446744071580810912,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
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
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580934080,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:3599",
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
      "addr": 18446744071580934080,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580930720,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:3770",
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
      "addr": 18446744071580930720,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933024,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:3794",
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
      "addr": 18446744071580933024,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1073
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
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581138672,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:3977",
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
      "addr": 18446744071581138672,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581429905,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:4238",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf"
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
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581782884,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:4286",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581925520,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:4423",
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
      "addr": 18446744071581925520,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582051952,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:4760",
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
      "addr": 18446744071582051952,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492130776,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2658",
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
      "addr": 18446603336492130776,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1164
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
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226029848,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2658",
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
      "addr": 3226029848,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285337872,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2658",
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
      "addr": 13835058055285337872,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 924
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
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272297540,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2658",
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
      "addr": 18446743936272297540,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580779712,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2658",
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
      "addr": 18446744071580779712,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
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
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580725888,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2658",
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
      "addr": 18446744071580725888,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
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
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580770960,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2658",
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
      "addr": 18446744071580770960,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
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
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "bpf_obj_get_info_by_fd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580829184,
      "name": "bpf_obj_get_info_by_fd",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2658",
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
      "addr": 18446744071580829184,
      "name": "bpf_obj_get_info_by_fd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int bpf_obj_get_info_by_fd(const union bpf_attr * attr, union bpf_attr * uattr)
```
</details>
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
