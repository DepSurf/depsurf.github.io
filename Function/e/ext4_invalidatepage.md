# Function: <code>ext4_invalidatepage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581558624,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3020",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558624,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581744560,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3209",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581744560,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581832288,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3236",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832288,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581979536,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3352",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581979536,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582127424,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3345",
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
      "addr": 18446744071582127424,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582315856,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3346",
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
      "addr": 18446744071582315856,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582414640,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3378",
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
      "addr": 18446744071582414640,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3391",
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
      "addr": 18446744071582583584,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071582631638,
      "name": "ext4_invalidatepage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582686176,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3354",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582686176,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583000720,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3244",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583000720,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583076688,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3264",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583076688,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583101216,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3263",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583101216,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583440992,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3186",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583440992,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494344240,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3354",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494344240,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227776004,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3354",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227776004,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288065392,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3354",
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
      "addr": 13835058055288065392,
      "name": "ext4_invalidatepage",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273773824,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3354",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273773824,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582654912,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3354",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582654912,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582592080,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3354",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582592080,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582644768,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3354",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582644768,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
```

```json
{
  "name": "ext4_invalidatepage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582729728,
      "name": "ext4_invalidatepage",
      "external": false,
      "loc": "fs/ext4/inode.c:3354",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582729728,
      "name": "ext4_invalidatepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void ext4_invalidatepage(struct page * page, unsigned int offset, unsigned int length)
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
