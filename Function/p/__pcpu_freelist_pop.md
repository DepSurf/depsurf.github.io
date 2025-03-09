# Function: <code>__pcpu_freelist_pop</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580770944,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:87",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580770944,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580855376,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:84",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855376,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906416,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:84",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906416,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581053056,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:84",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581053056,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581065387,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:193",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065312,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581080032,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:193",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581080032,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581308032,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:193",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308032,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581606896,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:193",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581606896,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581991020,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:184",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581990912,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582182348,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:184",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582182240,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582331116,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:184",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582331008,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492237000,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:84",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492237000,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226131968,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:84",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226131968,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285463376,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:84",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285463376,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272382636,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:84",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272382636,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580875216,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:84",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875216,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580821312,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:84",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821312,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866464,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:84",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866464,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```

```json
{
  "name": "__pcpu_freelist_pop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580925040,
      "name": "__pcpu_freelist_pop",
      "external": true,
      "loc": "kernel/bpf/percpu_freelist.c:84",
      "file": "kernel/bpf/percpu_freelist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925040,
      "name": "__pcpu_freelist_pop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct pcpu_freelist_node * __pcpu_freelist_pop(struct pcpu_freelist * s)
```
</details>
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
