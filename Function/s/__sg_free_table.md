# Function: <code>__sg_free_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sg_free_table(struct sg_table * table, unsigned int max_ents, bool skip_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583014400,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:205",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_free_table"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables",
        "drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables",
        "drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables",
        "drivers/scsi/scsi_lib.c:scsi_release_buffers",
        "drivers/scsi/scsi_lib.c:scsi_release_buffers",
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014400,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sg_free_table(struct sg_table * table, unsigned int max_ents, bool skip_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583305994,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:205",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_free_table"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583305296,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sg_free_table(struct sg_table * table, unsigned int max_ents, bool skip_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583425194,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:205",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_free_table"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583424624,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sg_free_table(struct sg_table * table, unsigned int max_ents, bool skip_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583446298,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:205",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_free_table"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583445872,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sg_free_table(struct sg_table * table, unsigned int max_ents, bool skip_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583626282,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:205",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_free_table"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583625856,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, bool skip_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583841872,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:193",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583841872,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, bool skip_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583925568,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:193",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583925568,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584105296,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:192",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105296,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584228192,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:192",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228192,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584638108,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:192",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:__sg_alloc_table_from_pages",
        "lib/scatterlist.c:sg_free_table"
      ],
      "caller_func": [
        "lib/sg_pool.c:sg_alloc_table_chained"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584634560,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584755408,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:192",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_free_table"
      ],
      "caller_func": [
        "lib/sg_pool.c:sg_alloc_table_chained"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584753600,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584783872,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:192",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_free_table"
      ],
      "caller_func": [
        "lib/sg_pool.c:sg_alloc_table_chained"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584782064,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn, unsigned int num_ents)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585216393,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:193",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_alloc_table_from_pages_segment",
        "lib/scatterlist.c:sg_alloc_table"
      ],
      "caller_func": [
        "lib/sg_pool.c:sg_alloc_table_chained"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212528,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn, unsigned int num_ents)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586054157,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:193",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_alloc_table_from_pages_segment",
        "lib/scatterlist.c:sg_alloc_table"
      ],
      "caller_func": [
        "lib/sg_pool.c:sg_alloc_table_chained"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586049776,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn, unsigned int num_ents)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587038426,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:193",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_alloc_table",
        "lib/scatterlist.c:sg_free_append_table"
      ],
      "caller_func": [
        "lib/sg_pool.c:sg_alloc_table_chained"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033280,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn, unsigned int num_ents)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587295530,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:195",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_alloc_table",
        "lib/scatterlist.c:sg_free_append_table"
      ],
      "caller_func": [
        "lib/sg_pool.c:sg_alloc_table_chained"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587288432,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn, unsigned int num_ents)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587581354,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:195",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_alloc_table",
        "lib/scatterlist.c:sg_free_append_table"
      ],
      "caller_func": [
        "lib/sg_pool.c:sg_alloc_table_chained"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587574304,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496103240,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:192",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496103240,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229428140,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:192",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229428140,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290349296,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:192",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_free_table",
        "lib/sg_pool.c:sg_alloc_table_chained"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290349296,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275169632,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:192",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275169632,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584196928,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:192",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584196928,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584132144,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:192",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132144,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584180688,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:192",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584180688,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void __sg_free_table(struct sg_table * table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn * free_fn)
```

```json
{
  "name": "__sg_free_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584285024,
      "name": "__sg_free_table",
      "external": true,
      "loc": "lib/scatterlist.c:192",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/scatterlist.c:sg_free_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584285024,
      "name": "__sg_free_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int nents_first_chunk</code>
</li>
<li>
<b>Param removed. </b>
<code>bool skip_first_chunk</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int num_ents</code>
</li>
</ul>
</details>
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
