# Function: <code>allocate_hook_entries_size</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nf_hook_entries * allocate_hook_entries_size(u16 num)
```

```json
{
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587806512,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:72",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_register_net_hook",
        "net/netfilter/core.c:nf_register_net_hook",
        "net/netfilter/core.c:__nf_hook_entries_try_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587806512,
      "name": "allocate_hook_entries_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
struct nf_hook_entries * allocate_hook_entries_size(u16 num)
```

```json
{
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588149280,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:49",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow",
        "net/netfilter/core.c:nf_hook_entries_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588149280,
      "name": "allocate_hook_entries_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct nf_hook_entries * allocate_hook_entries_size(u16 num)
```

```json
{
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588332464,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:49",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow",
        "net/netfilter/core.c:nf_hook_entries_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588332464,
      "name": "allocate_hook_entries_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct nf_hook_entries * allocate_hook_entries_size(u16 num)
```

```json
{
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588732736,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow",
        "net/netfilter/core.c:nf_hook_entries_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588732736,
      "name": "allocate_hook_entries_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct nf_hook_entries * allocate_hook_entries_size(u16 num)
```

```json
{
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588956656,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow",
        "net/netfilter/core.c:nf_hook_entries_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588956656,
      "name": "allocate_hook_entries_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589911297,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow"
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
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589952209,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow"
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
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589867041,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow"
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
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590627954,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow"
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
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592252627,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow"
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
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594086563,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow"
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
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594471571,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow"
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
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595273891,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct nf_hook_entries * allocate_hook_entries_size(u16 num)
```

```json
{
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502558176,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow",
        "net/netfilter/core.c:nf_hook_entries_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502558176,
      "name": "allocate_hook_entries_size",
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
struct nf_hook_entries * allocate_hook_entries_size(u16 num)
```

```json
{
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235264548,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow",
        "net/netfilter/core.c:nf_hook_entries_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235264548,
      "name": "allocate_hook_entries_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
struct nf_hook_entries * allocate_hook_entries_size(u16 num)
```

```json
{
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296136944,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow",
        "net/netfilter/core.c:nf_hook_entries_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296136944,
      "name": "allocate_hook_entries_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
struct nf_hook_entries * allocate_hook_entries_size(u16 num)
```

```json
{
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278717936,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow",
        "net/netfilter/core.c:nf_hook_entries_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278717936,
      "name": "allocate_hook_entries_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
struct nf_hook_entries * allocate_hook_entries_size(u16 num)
```

```json
{
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588563040,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow",
        "net/netfilter/core.c:nf_hook_entries_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563040,
      "name": "allocate_hook_entries_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct nf_hook_entries * allocate_hook_entries_size(u16 num)
```

```json
{
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588275024,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow",
        "net/netfilter/core.c:nf_hook_entries_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588275024,
      "name": "allocate_hook_entries_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct nf_hook_entries * allocate_hook_entries_size(u16 num)
```

```json
{
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588895216,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow",
        "net/netfilter/core.c:nf_hook_entries_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588895216,
      "name": "allocate_hook_entries_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct nf_hook_entries * allocate_hook_entries_size(u16 num)
```

```json
{
  "name": "allocate_hook_entries_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589037520,
      "name": "allocate_hook_entries_size",
      "external": false,
      "loc": "net/netfilter/core.c:50",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:__nf_hook_entries_try_shrink",
        "net/netfilter/core.c:nf_hook_entries_grow",
        "net/netfilter/core.c:nf_hook_entries_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589037520,
      "name": "allocate_hook_entries_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct nf_hook_entries * allocate_hook_entries_size(u16 num)
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
struct nf_hook_entries * allocate_hook_entries_size(u16 num)
```
</details>
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
