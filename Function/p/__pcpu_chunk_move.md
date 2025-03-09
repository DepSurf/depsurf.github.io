# Function: <code>__pcpu_chunk_move</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```

```json
{
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581191600,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:525",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581191600,
      "name": "__pcpu_chunk_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```

```json
{
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581250048,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:525",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581250048,
      "name": "__pcpu_chunk_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```

```json
{
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581439024,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:499",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581439024,
      "name": "__pcpu_chunk_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```

```json
{
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581478416,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:505",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581478416,
      "name": "__pcpu_chunk_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```

```json
{
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581499184,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:506",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581499184,
      "name": "__pcpu_chunk_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```

```json
{
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581762336,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:530",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581762336,
      "name": "__pcpu_chunk_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```

```json
{
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582145584,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:530",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145584,
      "name": "__pcpu_chunk_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```

```json
{
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582623536,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:526",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582623536,
      "name": "__pcpu_chunk_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```

```json
{
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582832576,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:526",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582832576,
      "name": "__pcpu_chunk_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```

```json
{
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583007024,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:526",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583007024,
      "name": "__pcpu_chunk_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492660144,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:525",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate",
        "mm/percpu.c:pcpu_chunk_relocate"
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
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226498700,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:525",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate",
        "mm/percpu.c:pcpu_chunk_relocate"
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
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285976740,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:525",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate",
        "mm/percpu.c:pcpu_chunk_relocate"
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
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272668918,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:525",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate",
        "mm/percpu.c:pcpu_chunk_relocate"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```

```json
{
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581218896,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:525",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218896,
      "name": "__pcpu_chunk_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```

```json
{
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581165600,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:525",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165600,
      "name": "__pcpu_chunk_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```

```json
{
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581210096,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:525",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210096,
      "name": "__pcpu_chunk_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```

```json
{
  "name": "__pcpu_chunk_move",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581273456,
      "name": "__pcpu_chunk_move",
      "external": false,
      "loc": "mm/percpu.c:525",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_chunk_relocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581273456,
      "name": "__pcpu_chunk_move",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk * chunk, int slot, bool move_front)
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
