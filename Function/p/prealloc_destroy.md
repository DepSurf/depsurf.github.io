# Function: <code>prealloc_destroy</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580497927,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:175",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_free"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void prealloc_destroy(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580525904,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:189",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525904,
      "name": "prealloc_destroy",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void prealloc_destroy(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580589408,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:196",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589408,
      "name": "prealloc_destroy",
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
void prealloc_destroy(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580684816,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:196",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684816,
      "name": "prealloc_destroy",
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
void prealloc_destroy(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756464,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:200",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756464,
      "name": "prealloc_destroy",
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
void prealloc_destroy(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580840240,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:192",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580840240,
      "name": "prealloc_destroy",
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
void prealloc_destroy(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580891280,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:192",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891280,
      "name": "prealloc_destroy",
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
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581042278,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:307",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
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
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581048416,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:335",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
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
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581063968,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:335",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
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
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581288834,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:365",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
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
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581585543,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:381",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
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
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581962072,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:361",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
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
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582153212,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:372",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
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
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582302377,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:377",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
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
void prealloc_destroy(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492218152,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:192",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492218152,
      "name": "prealloc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void prealloc_destroy(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226116164,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:192",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226116164,
      "name": "prealloc_destroy",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void prealloc_destroy(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285440320,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:192",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285440320,
      "name": "prealloc_destroy",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void prealloc_destroy(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272365522,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:192",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272365522,
      "name": "prealloc_destroy",
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
void prealloc_destroy(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580860080,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:192",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860080,
      "name": "prealloc_destroy",
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
void prealloc_destroy(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580806208,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:192",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806208,
      "name": "prealloc_destroy",
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
void prealloc_destroy(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580851328,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:192",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580851328,
      "name": "prealloc_destroy",
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
void prealloc_destroy(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580909648,
      "name": "prealloc_destroy",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:192",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580909648,
      "name": "prealloc_destroy",
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void prealloc_destroy(struct bpf_htab * htab)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
void prealloc_destroy(struct bpf_htab * htab)
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
