# Function: <code>mext_page_mkuptodate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581820974,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:177",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
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
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582016716,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:177",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
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
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582106764,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:177",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
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
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582076983,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:177",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
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
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582227221,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:177",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
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
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582417122,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:169",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
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
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582516580,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:167",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582684096,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:167",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582684096,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582786272,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:167",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582786272,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583099296,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:167",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583099296,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583178480,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:167",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583178480,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583204784,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:167",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583204784,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:167",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583548144,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 854
    },
    {
      "addr": 18446744071592266179,
      "name": "mext_page_mkuptodate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:172",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584082496,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1101
    },
    {
      "addr": 18446744071594047660,
      "name": "mext_page_mkuptodate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:169",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715408,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1111
    },
    {
      "addr": 18446744071596080542,
      "name": "mext_page_mkuptodate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int mext_page_mkuptodate(struct folio * folio, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:171",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584939184,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
    },
    {
      "addr": 18446744071596603714,
      "name": "mext_page_mkuptodate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int mext_page_mkuptodate(struct folio * folio, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:171",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585170736,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
    },
    {
      "addr": 18446744071597509153,
      "name": "mext_page_mkuptodate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494456040,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:167",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494456040,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 896
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227890940,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:167",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227890940,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288209264,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:167",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288209264,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273863878,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:167",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273863878,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582755008,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:167",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582755008,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582692176,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:167",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582692176,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582744864,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:167",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582744864,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
```

```json
{
  "name": "mext_page_mkuptodate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582830112,
      "name": "mext_page_mkuptodate",
      "external": false,
      "loc": "fs/ext4/move_extent.c:167",
      "file": "fs/ext4/move_extent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830112,
      "name": "mext_page_mkuptodate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 818
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
int mext_page_mkuptodate(struct page * page, unsigned int from, unsigned int to)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
</ul>
</details>
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
