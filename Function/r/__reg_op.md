# Function: <code>__reg_op</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011216,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:946",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_allocate_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011216,
      "name": "__reg_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301744,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:948",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301744,
      "name": "__reg_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583420784,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:990",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583420784,
      "name": "__reg_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583442277,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:996",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region"
      ],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583441920,
      "name": "__reg_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583622213,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:992",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region"
      ],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621856,
      "name": "__reg_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583838415,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:989",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region"
      ],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583838192,
      "name": "__reg_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583922047,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:984",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region"
      ],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921824,
      "name": "__reg_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584101965,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1012",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region"
      ],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584101600,
      "name": "__reg_op",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584224749,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1032",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region"
      ],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584224384,
      "name": "__reg_op",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584632448,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1107",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
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
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584751491,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1107",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
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
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584779923,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1118",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1249",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585208064,
      "name": "__reg_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071592322910,
      "name": "__reg_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1266",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044048,
      "name": "__reg_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071594126755,
      "name": "__reg_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1247",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587026912,
      "name": "__reg_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071596113798,
      "name": "__reg_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1247",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587281904,
      "name": "__reg_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    },
    {
      "addr": 18446744071596638902,
      "name": "__reg_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496098584,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1032",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region"
      ],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496098168,
      "name": "__reg_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229425484,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1032",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region"
      ],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229425064,
      "name": "__reg_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290343372,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1032",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region"
      ],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290342640,
      "name": "__reg_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275166734,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1032",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region"
      ],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275166368,
      "name": "__reg_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584193485,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1032",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region"
      ],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193120,
      "name": "__reg_op",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584128701,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1032",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region"
      ],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584128336,
      "name": "__reg_op",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584177245,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1032",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region"
      ],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584176880,
      "name": "__reg_op",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```

```json
{
  "name": "__reg_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584281581,
      "name": "__reg_op",
      "external": false,
      "loc": "lib/bitmap.c:1032",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_allocate_region"
      ],
      "caller_func": [
        "lib/bitmap.c:bitmap_allocate_region",
        "lib/bitmap.c:bitmap_release_region",
        "lib/bitmap.c:bitmap_find_free_region",
        "lib/bitmap.c:bitmap_find_free_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584281216,
      "name": "__reg_op",
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
```
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int __reg_op(long unsigned int * bitmap, unsigned int pos, int order, int reg_op)
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
