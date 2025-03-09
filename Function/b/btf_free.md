# Function: <code>btf_free</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void btf_free(struct btf * btf)
```

```json
{
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580707216,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:668",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707216,
      "name": "btf_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void btf_free(struct btf * btf)
```

```json
{
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580783792,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:796",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580783792,
      "name": "btf_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void btf_free(struct btf * btf)
```

```json
{
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580868752,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:897",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868752,
      "name": "btf_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void btf_free(struct btf * btf)
```

```json
{
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919712,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:897",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919712,
      "name": "btf_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581097575,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:925",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_parse",
        "kernel/bpf/btf.c:btf_free_rcu"
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
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581124809,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:1511",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_parse",
        "kernel/bpf/btf.c:btf_free_rcu"
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
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581144713,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:1512",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_parse",
        "kernel/bpf/btf.c:btf_free_rcu"
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
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581378090,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:1512",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_parse",
        "kernel/bpf/btf.c:btf_free_rcu"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void btf_free(struct btf * btf)
```

```json
{
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581646320,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:1638",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_module_notify",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_parse",
        "kernel/bpf/btf.c:btf_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581646320,
      "name": "btf_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void btf_free(struct btf * btf)
```

```json
{
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582038384,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:1660",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_module_notify",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_parse",
        "kernel/bpf/btf.c:btf_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582038384,
      "name": "btf_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void btf_free(struct btf * btf)
```

```json
{
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582230992,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:1690",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_module_notify",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_parse",
        "kernel/bpf/btf.c:btf_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582230992,
      "name": "btf_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void btf_free(struct btf * btf)
```

```json
{
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582386944,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:1691",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_module_notify",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_parse",
        "kernel/bpf/btf.c:btf_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582386944,
      "name": "btf_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void btf_free(struct btf * btf)
```

```json
{
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492254872,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:897",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492254872,
      "name": "btf_free",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void btf_free(struct btf * btf)
```

```json
{
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226146348,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:897",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226146348,
      "name": "btf_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void btf_free(struct btf * btf)
```

```json
{
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285484048,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:897",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285484048,
      "name": "btf_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void btf_free(struct btf * btf)
```

```json
{
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272395800,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:897",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272395800,
      "name": "btf_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void btf_free(struct btf * btf)
```

```json
{
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580888512,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:897",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888512,
      "name": "btf_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void btf_free(struct btf * btf)
```

```json
{
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580834576,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:897",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580834576,
      "name": "btf_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void btf_free(struct btf * btf)
```

```json
{
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580879760,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:897",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580879760,
      "name": "btf_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void btf_free(struct btf * btf)
```

```json
{
  "name": "btf_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580938400,
      "name": "btf_free",
      "external": false,
      "loc": "kernel/bpf/btf.c:897",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580938400,
      "name": "btf_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void btf_free(struct btf * btf)
```
</details>
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
void btf_free(struct btf * btf)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void btf_free(struct btf * btf)
```
</details>
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
