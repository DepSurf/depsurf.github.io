# Function: <code>info_idq_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581406064,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1357",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_transfer"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406064,
      "name": "info_idq_free.part.9.constprop.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581600972,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1366",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode"
      ],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587552,
      "name": "info_idq_free.part.9.constprop.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581689468,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1363",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode"
      ],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581675936,
      "name": "info_idq_free.part.11.constprop.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581743550,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1369",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode"
      ],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729072,
      "name": "info_idq_free.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581890227,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1371",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode"
      ],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874912,
      "name": "info_idq_free.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582056176,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1368",
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
      "addr": 18446744071582056176,
      "name": "info_idq_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582150272,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1368",
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
      "addr": 18446744071582150272,
      "name": "info_idq_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582312992,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1378",
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
      "addr": 18446744071582312992,
      "name": "info_idq_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582412048,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1380",
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
      "addr": 18446744071582412048,
      "name": "info_idq_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582705600,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1378",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582705600,
      "name": "info_idq_free",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582776752,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1379",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582776752,
      "name": "info_idq_free",
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
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582805072,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1377",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582805072,
      "name": "info_idq_free",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583135095,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1382",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583134992,
      "name": "info_idq_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071592246347,
      "name": "info_idq_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1392",
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
      "addr": 18446744071583623344,
      "name": "info_idq_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071594027095,
      "name": "info_idq_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1392",
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
      "addr": 18446744071584228288,
      "name": "info_idq_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071596062571,
      "name": "info_idq_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1450",
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
      "addr": 18446744071584457776,
      "name": "info_idq_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071596586634,
      "name": "info_idq_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1404",
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
      "addr": 18446744071584680944,
      "name": "info_idq_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071597492404,
      "name": "info_idq_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494015512,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1380",
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
      "addr": 18446603336494015512,
      "name": "info_idq_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227482092,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1380",
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
      "addr": 3227482092,
      "name": "info_idq_free",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287667328,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1380",
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
      "addr": 13835058055287667328,
      "name": "info_idq_free",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273525890,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1380",
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
      "addr": 18446743936273525890,
      "name": "info_idq_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582380784,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1380",
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
      "addr": 18446744071582380784,
      "name": "info_idq_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582318480,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1380",
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
      "addr": 18446744071582318480,
      "name": "info_idq_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582371264,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1380",
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
      "addr": 18446744071582371264,
      "name": "info_idq_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```

```json
{
  "name": "info_idq_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582451248,
      "name": "info_idq_free",
      "external": false,
      "loc": "fs/quota/dquot.c:1380",
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
      "addr": 18446744071582451248,
      "name": "info_idq_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int info_idq_free(struct dquot * dquot, qsize_t inodes)
```
</details>
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
