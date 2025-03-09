# Function: <code>fat_cont_expand</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581969737,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:182",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_setattr"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582180080,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:187",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582180080,
      "name": "fat_cont_expand",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269488,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:187",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269488,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582354144,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:187",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582354144,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582504944,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:187",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504944,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582696032,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:187",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582696032,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582799152,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:220",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582799152,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582974048,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:227",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974048,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583080256,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:227",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583080256,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583398960,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:216",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583398960,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583514496,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:216",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583514496,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583537392,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:216",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583537392,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583895248,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:216",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583895248,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584471696,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:216",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584471696,
      "name": "fat_cont_expand",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585135360,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:217",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585135360,
      "name": "fat_cont_expand",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585364704,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:217",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585364704,
      "name": "fat_cont_expand",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585599440,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:217",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585599440,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494785320,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:227",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494785320,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228205588,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:227",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228205588,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288619680,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:227",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288619680,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274117078,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:227",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274117078,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583048992,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:227",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048992,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582986144,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:227",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582986144,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583037600,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:227",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583037600,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int fat_cont_expand(struct inode * inode, loff_t size)
```

```json
{
  "name": "fat_cont_expand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583126736,
      "name": "fat_cont_expand",
      "external": false,
      "loc": "fs/fat/file.c:227",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_setattr",
        "fs/fat/file.c:fat_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583126736,
      "name": "fat_cont_expand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int fat_cont_expand(struct inode * inode, loff_t size)
```
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
