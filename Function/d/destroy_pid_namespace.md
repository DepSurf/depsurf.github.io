# Function: <code>destroy_pid_namespace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void destroy_pid_namespace(struct pid_namespace * ns)
```

```json
{
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580022096,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:142",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:put_pid_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022096,
      "name": "destroy_pid_namespace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void destroy_pid_namespace(struct pid_namespace * ns)
```

```json
{
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054672,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:142",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:put_pid_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054672,
      "name": "destroy_pid_namespace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void destroy_pid_namespace(struct pid_namespace * ns)
```

```json
{
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094496,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:162",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:put_pid_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094496,
      "name": "destroy_pid_namespace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580100316,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:165",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:put_pid_ns"
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
void destroy_pid_namespace(struct pid_namespace * ns)
```

```json
{
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580152736,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:160",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152736,
      "name": "destroy_pid_namespace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void destroy_pid_namespace(struct pid_namespace * ns)
```

```json
{
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580212448,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:141",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212448,
      "name": "destroy_pid_namespace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void destroy_pid_namespace(struct pid_namespace * ns)
```

```json
{
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580264880,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:141",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580264880,
      "name": "destroy_pid_namespace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void destroy_pid_namespace(struct pid_namespace * ns)
```

```json
{
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580315744,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:142",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315744,
      "name": "destroy_pid_namespace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void destroy_pid_namespace(struct pid_namespace * ns)
```

```json
{
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580364576,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:142",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364576,
      "name": "destroy_pid_namespace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580439008,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:133",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:put_pid_ns"
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
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580426206,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:133",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:put_pid_ns"
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
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580430638,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:133",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:put_pid_ns"
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
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580594654,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:134",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:put_pid_ns"
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
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580797208,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:134",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:put_pid_ns"
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
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581082200,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:134",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:put_pid_ns"
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
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581173896,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:137",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:put_pid_ns"
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
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581279576,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:138",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:put_pid_ns"
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
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491627128,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:142",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:put_pid_ns"
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
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225581392,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:142",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:put_pid_ns"
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
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284619808,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:142",
      "file": "kernel/pid_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:put_pid_ns"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void destroy_pid_namespace(struct pid_namespace * ns)
```

```json
{
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272025520,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:142",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272025520,
      "name": "destroy_pid_namespace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void destroy_pid_namespace(struct pid_namespace * ns)
```

```json
{
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580333376,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:142",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580333376,
      "name": "destroy_pid_namespace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void destroy_pid_namespace(struct pid_namespace * ns)
```

```json
{
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580280640,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:142",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580280640,
      "name": "destroy_pid_namespace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void destroy_pid_namespace(struct pid_namespace * ns)
```

```json
{
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580324624,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:142",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580324624,
      "name": "destroy_pid_namespace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void destroy_pid_namespace(struct pid_namespace * ns)
```

```json
{
  "name": "destroy_pid_namespace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580379648,
      "name": "destroy_pid_namespace",
      "external": false,
      "loc": "kernel/pid_namespace.c:142",
      "file": "kernel/pid_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_put",
        "kernel/pid_namespace.c:pidns_for_children_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379648,
      "name": "destroy_pid_namespace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void destroy_pid_namespace(struct pid_namespace * ns)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void destroy_pid_namespace(struct pid_namespace * ns)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void destroy_pid_namespace(struct pid_namespace * ns)
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
void destroy_pid_namespace(struct pid_namespace * ns)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void destroy_pid_namespace(struct pid_namespace * ns)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void destroy_pid_namespace(struct pid_namespace * ns)
```
</details>
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
