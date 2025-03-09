# Function: <code>sync_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581188816,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2370",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188816,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581352399,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2448",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581352336,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581431311,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2446",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431248,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581485487,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2455",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485424,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581627631,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2470",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581627568,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581786300,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2468",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786224,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581873084,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2497",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581873008,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581995420,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2512",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995344,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582070908,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2600",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070832,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582306620,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2609",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582306544,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582359612,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2602",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582359536,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582387372,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2603",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582387296,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493601680,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2600",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493601544,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227149704,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2600",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227149588,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287191492,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2600",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287191360,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273250440,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2600",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273250364,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582039644,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2600",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582039568,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581977212,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2600",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977136,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582030924,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2600",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582030848,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sync_inode(struct inode * inode, struct writeback_control * wbc)
```

```json
{
  "name": "sync_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582104684,
      "name": "sync_inode",
      "external": true,
      "loc": "fs/fs-writeback.c:2600",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:sync_inode_metadata"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582104608,
      "name": "sync_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int sync_inode(struct inode * inode, struct writeback_control * wbc)
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
