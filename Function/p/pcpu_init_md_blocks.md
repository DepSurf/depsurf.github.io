# Function: <code>pcpu_init_md_blocks</code>

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
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580914491,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1052",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
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
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581052683,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1049",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
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
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581130427,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1057",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
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
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581188336,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1282",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188336,
      "name": "pcpu_init_md_blocks",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581246784,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1282",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246784,
      "name": "pcpu_init_md_blocks",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581435760,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1254",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435760,
      "name": "pcpu_init_md_blocks",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581478912,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1270",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581478912,
      "name": "pcpu_init_md_blocks",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581499728,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1271",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581499728,
      "name": "pcpu_init_md_blocks",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581759616,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1315",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759616,
      "name": "pcpu_init_md_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141632,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1315",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141632,
      "name": "pcpu_init_md_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582618944,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1319",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582618944,
      "name": "pcpu_init_md_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582827984,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1319",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582827984,
      "name": "pcpu_init_md_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002432,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1319",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002432,
      "name": "pcpu_init_md_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492647024,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1282",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492647024,
      "name": "pcpu_init_md_blocks",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226487444,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1282",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226487444,
      "name": "pcpu_init_md_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285963360,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1282",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285963360,
      "name": "pcpu_init_md_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272661528,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1282",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272661528,
      "name": "pcpu_init_md_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581215632,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1282",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581215632,
      "name": "pcpu_init_md_blocks",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581162336,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1282",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162336,
      "name": "pcpu_init_md_blocks",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581206832,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1282",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206832,
      "name": "pcpu_init_md_blocks",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_init_md_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581270192,
      "name": "pcpu_init_md_blocks",
      "external": false,
      "loc": "mm/percpu.c:1282",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581270192,
      "name": "pcpu_init_md_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void pcpu_init_md_blocks(struct pcpu_chunk * chunk)
```
</details>
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
