# Function: <code>__ext4_journalled_writepage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581576221,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:1727",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepage"
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
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581764193,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:1884",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepage"
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
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581853247,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:1913",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepage"
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
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582001011,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:1967",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepage"
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
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582150915,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:1975",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepage"
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
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582345678,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:1978",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepage"
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
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582444644,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:2008",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepage"
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
int __ext4_journalled_writepage(struct page * page, unsigned int len)
```

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582613584,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:2024",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582613584,
      "name": "__ext4_journalled_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1126
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
int __ext4_journalled_writepage(struct page * page, unsigned int len)
```

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582714512,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:2000",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582714512,
      "name": "__ext4_journalled_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1126
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
int __ext4_journalled_writepage(struct page * page, unsigned int len)
```

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583024816,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:1850",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583024816,
      "name": "__ext4_journalled_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1244
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
int __ext4_journalled_writepage(struct page * page, unsigned int len)
```

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583100336,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:1867",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583100336,
      "name": "__ext4_journalled_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1369
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
int __ext4_journalled_writepage(struct page * page, unsigned int len)
```

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583125808,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:1866",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583125808,
      "name": "__ext4_journalled_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1369
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
int __ext4_journalled_writepage(struct page * page, unsigned int len)
```

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583467248,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:1848",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583467248,
      "name": "__ext4_journalled_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1235
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
int __ext4_journalled_writepage(struct page * page, unsigned int len)
```

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583990416,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:1870",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583990416,
      "name": "__ext4_journalled_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1498
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
int __ext4_journalled_writepage(struct page * page, unsigned int len)
```

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584616464,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:1890",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584616464,
      "name": "__ext4_journalled_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1504
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __ext4_journalled_writepage(struct page * page, unsigned int len)
```

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494371728,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:2000",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494371728,
      "name": "__ext4_journalled_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1204
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
int __ext4_journalled_writepage(struct page * page, unsigned int len)
```

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227807376,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:2000",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227807376,
      "name": "__ext4_journalled_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1372
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
int __ext4_journalled_writepage(struct page * page, unsigned int len)
```

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288105568,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:2000",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288105568,
      "name": "__ext4_journalled_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1772
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
int __ext4_journalled_writepage(struct page * page, unsigned int len)
```

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273798864,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:2000",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273798864,
      "name": "__ext4_journalled_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
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
int __ext4_journalled_writepage(struct page * page, unsigned int len)
```

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582683248,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:2000",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582683248,
      "name": "__ext4_journalled_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1126
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
int __ext4_journalled_writepage(struct page * page, unsigned int len)
```

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582620416,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:2000",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582620416,
      "name": "__ext4_journalled_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1126
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
int __ext4_journalled_writepage(struct page * page, unsigned int len)
```

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582673104,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:2000",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582673104,
      "name": "__ext4_journalled_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1126
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
int __ext4_journalled_writepage(struct page * page, unsigned int len)
```

```json
{
  "name": "__ext4_journalled_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582757056,
      "name": "__ext4_journalled_writepage",
      "external": false,
      "loc": "fs/ext4/inode.c:2000",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582757056,
      "name": "__ext4_journalled_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1127
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
int __ext4_journalled_writepage(struct page * page, unsigned int len)
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
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int __ext4_journalled_writepage(struct page * page, unsigned int len)
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
