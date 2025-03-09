# Function: <code>__blk_mq_get_tag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582807574,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:321",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
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
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583086678,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:321",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
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
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583194771,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:159",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag"
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583250064,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:93",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583250064,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583429248,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:93",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583429248,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583640592,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:96",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583640592,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583746864,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:96",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583746864,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583936064,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:97",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583936064,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584039424,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:98",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584039424,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584434256,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:90",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584434256,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584550704,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:76",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584550704,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584583056,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:76",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584583056,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584997312,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:77",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584997312,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585710112,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:102",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585710112,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586490272,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:98",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586490272,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586737792,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:105",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586737792,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587009888,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:105",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009888,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495873592,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:98",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495873592,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229219468,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:98",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229219468,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290074304,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:98",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290074304,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274997264,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:98",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274997264,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008160,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:98",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008160,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583943984,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:98",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583943984,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583991920,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:98",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583991920,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
```

```json
{
  "name": "__blk_mq_get_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584094224,
      "name": "__blk_mq_get_tag",
      "external": false,
      "loc": "block/blk-mq-tag.c:98",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584094224,
      "name": "__blk_mq_get_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int __blk_mq_get_tag(struct blk_mq_alloc_data * data, struct sbitmap_queue * bt)
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
