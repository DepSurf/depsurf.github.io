# Function: <code>pcpu_block_update</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580918375,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:619",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_free_area"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_block_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580909824,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581049840,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:616",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_free_area"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_block_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581045680,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581127426,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:624",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_free_area"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_block_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123344,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581187968,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:603",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581187968,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581246416,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:603",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246416,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581435392,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:577",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435392,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581478544,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:586",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581478544,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581499312,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:587",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581499312,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581759200,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:634",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759200,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141152,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:634",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141152,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582619120,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:630",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582619120,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582828160,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:630",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582828160,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002608,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:630",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_update_hint_free",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002608,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492647336,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:603",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492647336,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226487696,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:603",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226487696,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285963728,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:603",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285963728,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272661022,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:603",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272661022,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581215264,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:603",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581215264,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581161968,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:603",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581161968,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581206464,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:603",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206464,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
```

```json
{
  "name": "pcpu_block_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581269824,
      "name": "pcpu_block_update",
      "external": false,
      "loc": "mm/percpu.c:603",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/percpu.c:pcpu_block_refresh_hint",
        "mm/percpu.c:pcpu_chunk_refresh_hint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269824,
      "name": "pcpu_block_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void pcpu_block_update(struct pcpu_block_md * block, int start, int end)
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
