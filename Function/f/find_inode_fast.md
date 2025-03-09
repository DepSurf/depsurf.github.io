# Function: <code>find_inode_fast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581102992,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:801",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581102992,
      "name": "find_inode_fast",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581268656,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:810",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268656,
      "name": "find_inode_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346528,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:812",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346528,
      "name": "find_inode_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401968,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:813",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401968,
      "name": "find_inode_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581543600,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:813",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543600,
      "name": "find_inode_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581702400,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:818",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702400,
      "name": "find_inode_fast.isra.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581791376,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:822",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791376,
      "name": "find_inode_fast.isra.26",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581909952,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:835",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581909952,
      "name": "find_inode_fast.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581982480,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:846",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581982480,
      "name": "find_inode_fast.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582213584,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:847",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582213584,
      "name": "find_inode_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582261040,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:846",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582261040,
      "name": "find_inode_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582286624,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:853",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582286624,
      "name": "find_inode_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582605120,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:857",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582605120,
      "name": "find_inode_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583131376,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:938",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583131376,
      "name": "find_inode_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583701776,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:937",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583701776,
      "name": "find_inode_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583919200,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:939",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919200,
      "name": "find_inode_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584125184,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:924",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125184,
      "name": "find_inode_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493488752,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:846",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493488752,
      "name": "find_inode_fast.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227045576,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:846",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227045576,
      "name": "find_inode_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287045760,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:846",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287045760,
      "name": "find_inode_fast.isra.0",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273167676,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:846",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273167676,
      "name": "find_inode_fast.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581951216,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:846",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581951216,
      "name": "find_inode_fast.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581888784,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:846",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581888784,
      "name": "find_inode_fast.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581942528,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:846",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942528,
      "name": "find_inode_fast.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_inode_fast",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582008944,
      "name": "find_inode_fast",
      "external": false,
      "loc": "fs/inode.c:846",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008944,
      "name": "find_inode_fast.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct inode * find_inode_fast(struct super_block * sb, struct hlist_head * head, long unsigned int ino)
```
</details>
</li>
</ul>
