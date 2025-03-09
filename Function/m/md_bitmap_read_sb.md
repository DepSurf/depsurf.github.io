# Function: <code>md_bitmap_read_sb</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587435685,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:580",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:581",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587705888,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1114
    },
    {
      "addr": 18446744071587711589,
      "name": "md_bitmap_read_sb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:581",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587910176,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1114
    },
    {
      "addr": 18446744071587915893,
      "name": "md_bitmap_read_sb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:577",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588761920,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1119
    },
    {
      "addr": 18446744071588767435,
      "name": "md_bitmap_read_sb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:578",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588782144,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1347
    },
    {
      "addr": 18446744071591591360,
      "name": "md_bitmap_read_sb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:578",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588668048,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1306
    },
    {
      "addr": 18446744071591534472,
      "name": "md_bitmap_read_sb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:578",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589346208,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1306
    },
    {
      "addr": 18446744071592647216,
      "name": "md_bitmap_read_sb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:578",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590819952,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1180
    },
    {
      "addr": 18446744071594532110,
      "name": "md_bitmap_read_sb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592507216,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:578",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592507216,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1488
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
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592937696,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:594",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592937696,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1488
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
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593687408,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:613",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593687408,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1510
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
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501141120,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:581",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501141120,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1400
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
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233655080,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:581",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233655080,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1616
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
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294647184,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:581",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294647184,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1728
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
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277854694,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:581",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277854694,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1150
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:581",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587541152,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1114
    },
    {
      "addr": 18446744071587546869,
      "name": "md_bitmap_read_sb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:581",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587309264,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1114
    },
    {
      "addr": 18446744071587314965,
      "name": "md_bitmap_read_sb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:581",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587866320,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1114
    },
    {
      "addr": 18446744071587872037,
      "name": "md_bitmap_read_sb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int md_bitmap_read_sb(struct bitmap * bitmap)
```

```json
{
  "name": "md_bitmap_read_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_read_sb",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:581",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587981376,
      "name": "md_bitmap_read_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
    },
    {
      "addr": 18446744071587987149,
      "name": "md_bitmap_read_sb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
int md_bitmap_read_sb(struct bitmap * bitmap)
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
