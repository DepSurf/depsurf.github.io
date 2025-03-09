# Function: <code>prealloc_init</code>

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
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580504689,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:123",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580533744,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:133",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580597488,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:138",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580692845,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:138",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580765156,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:142",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580842406,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:134",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580893446,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:134",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int prealloc_init(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581037728,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:249",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037728,
      "name": "prealloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
int prealloc_init(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046176,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:276",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046176,
      "name": "prealloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
int prealloc_init(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581061024,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:276",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581061024,
      "name": "prealloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int prealloc_init(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581286176,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:306",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581286176,
      "name": "prealloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
int prealloc_init(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581582528,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:322",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582528,
      "name": "prealloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
int prealloc_init(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581960624,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:302",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960624,
      "name": "prealloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
int prealloc_init(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582149440,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:313",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582149440,
      "name": "prealloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
int prealloc_init(struct bpf_htab * htab)
```

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582298512,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:318",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582298512,
      "name": "prealloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492218952,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:134",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226118472,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:134",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285443616,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:134",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272368934,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:134",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580862246,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:134",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580808374,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:134",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580853494,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:134",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prealloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580911830,
      "name": "prealloc_init",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:134",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int prealloc_init(struct bpf_htab * htab)
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
