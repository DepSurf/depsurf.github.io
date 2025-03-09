# Function: <code>nf_hook_entries_grow</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587807390,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:101",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_register_net_hook"
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588149344,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:103",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588149344,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588332528,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:103",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588332528,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588732800,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588732800,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588956720,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588956720,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589912944,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589912944,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589953888,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589953888,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589868720,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589868720,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590629792,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/netfilter/core.c:nf_hook_entries_insert_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590629792,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592250896,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/netfilter/core.c:nf_hook_entries_insert_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592250896,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594084720,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/netfilter/core.c:nf_hook_entries_insert_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594084720,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594469632,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/netfilter/core.c:nf_hook_entries_insert_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594469632,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 474
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595271856,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/netfilter/core.c:nf_hook_entries_insert_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595271856,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 474
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502558256,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502558256,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235264620,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235264620,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296137088,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook",
        "net/netfilter/core.c:nf_hook_entries_insert_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296137088,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278718006,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278718006,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588563104,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563104,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588275088,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588275088,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588895280,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588895280,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
```

```json
{
  "name": "nf_hook_entries_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589037584,
      "name": "nf_hook_entries_grow",
      "external": false,
      "loc": "net/netfilter/core.c:104",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_register_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589037584,
      "name": "nf_hook_entries_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
struct nf_hook_entries * nf_hook_entries_grow(const struct nf_hook_entries * old, const struct nf_hook_ops * reg)
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
