# Function: <code>allocate_probes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580153782,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:62",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
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
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580188202,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:62",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
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
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580228810,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:62",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
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
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580238739,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:63",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
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
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580289964,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:63",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580351805,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:63",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
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
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580407245,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:69",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
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
void * allocate_probes(int count)
```

```json
{
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580459904,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:56",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580459904,
      "name": "allocate_probes",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * allocate_probes(int count)
```

```json
{
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580508816,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:56",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580508816,
      "name": "allocate_probes",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580594916,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:56",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_remove_func",
        "kernel/tracepoint.c:func_add"
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
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580586162,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:62",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:func_remove",
        "kernel/tracepoint.c:func_add"
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
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580587796,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:107",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func"
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
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580758788,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:107",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func"
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
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580974461,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:107",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func"
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
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581272045,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:107",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func"
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
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581367180,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:107",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func"
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
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581472060,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:107",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func"
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
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491787996,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:56",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
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
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225735720,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:56",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * allocate_probes(int count)
```

```json
{
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284836672,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:56",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284836672,
      "name": "allocate_probes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272102484,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:56",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * allocate_probes(int count)
```

```json
{
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580477616,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:56",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477616,
      "name": "allocate_probes",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void * allocate_probes(int count)
```

```json
{
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580424752,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:56",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424752,
      "name": "allocate_probes",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void * allocate_probes(int count)
```

```json
{
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580468864,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:56",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580468864,
      "name": "allocate_probes",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void * allocate_probes(int count)
```

```json
{
  "name": "allocate_probes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580524560,
      "name": "allocate_probes",
      "external": false,
      "loc": "kernel/tracepoint.c:56",
      "file": "kernel/tracepoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580524560,
      "name": "allocate_probes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void * allocate_probes(int count)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void * allocate_probes(int count)
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
void * allocate_probes(int count)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * allocate_probes(int count)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * allocate_probes(int count)
```
</details>
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
