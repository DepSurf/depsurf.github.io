# Function: <code>dquot_decr_inodes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581406176,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1122",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406176,
      "name": "dquot_decr_inodes.constprop.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581587664,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1131",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587664,
      "name": "dquot_decr_inodes.constprop.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581676048,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1128",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581676048,
      "name": "dquot_decr_inodes.constprop.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581726848,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1133",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581726848,
      "name": "dquot_decr_inodes",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581872816,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1110",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581872816,
      "name": "dquot_decr_inodes",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582055904,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1107",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582055904,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582150000,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1107",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582150000,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582312720,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1117",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582312720,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582411776,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1119",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582411776,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582706672,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1117",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582706672,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582777824,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1118",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582777824,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582805744,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1116",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582805744,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583134256,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1121",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583134256,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583622944,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1131",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583622944,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584227360,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1131",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584227360,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584456800,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1189",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584456800,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584679968,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1143",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584679968,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494016752,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1119",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494016752,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227483732,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1119",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227483732,
      "name": "dquot_decr_inodes",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287666928,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1119",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287666928,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273541552,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1119",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_alloc_inode"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582380512,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1119",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582380512,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582318208,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1119",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582318208,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582370992,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1119",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582370992,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
```

```json
{
  "name": "dquot_decr_inodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582450976,
      "name": "dquot_decr_inodes",
      "external": false,
      "loc": "fs/quota/dquot.c:1119",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:dquot_alloc_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582450976,
      "name": "dquot_decr_inodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void dquot_decr_inodes(struct dquot * dquot, qsize_t number)
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
