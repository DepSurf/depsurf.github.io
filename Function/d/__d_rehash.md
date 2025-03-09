# Function: <code>__d_rehash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __d_rehash(struct dentry * entry, struct hlist_bl_head * b)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581086832,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2410",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_rehash",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581086832,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581252240,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2343",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581252240,
      "name": "__d_rehash",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581330032,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2352",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330032,
      "name": "__d_rehash",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581385424,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2382",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581385424,
      "name": "__d_rehash",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581525472,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2394",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581525472,
      "name": "__d_rehash",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581681648,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2408",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581681648,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581768304,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2389",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581768304,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581885568,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2459",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885568,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958112,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2459",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958112,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582190944,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2480",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582190944,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582238448,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2487",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582238448,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582264176,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2514",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264176,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2515",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582128,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071592229681,
      "name": "__d_rehash.cold",
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2540",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583116080,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071594009445,
      "name": "__d_rehash.cold",
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2574",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583686160,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071596050743,
      "name": "__d_rehash.cold",
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2574",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583904048,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071596573301,
      "name": "__d_rehash.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2398",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:__d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110784,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071597477810,
      "name": "__d_rehash.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493454392,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2459",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_rehash",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493454392,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227027248,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2459",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227027248,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287014720,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2459",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287014720,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273136520,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2459",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273136520,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581926848,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2459",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926848,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581864432,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2459",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864432,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581918160,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2459",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918160,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __d_rehash(struct dentry * entry)
```

```json
{
  "name": "__d_rehash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581990752,
      "name": "__d_rehash",
      "external": false,
      "loc": "fs/dcache.c:2459",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_exact_alias",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_add",
        "fs/dcache.c:d_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581990752,
      "name": "__d_rehash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct hlist_bl_head * b</code>
</li>
</ul>
</details>
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
