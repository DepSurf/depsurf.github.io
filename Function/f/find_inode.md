# Function: <code>find_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
```

```json
{
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581102656,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:772",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iget5_locked",
        "fs/inode.c:iget5_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581102656,
      "name": "find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
```

```json
{
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581268336,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:781",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iget5_locked",
        "fs/inode.c:iget5_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268336,
      "name": "find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
```

```json
{
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346208,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:783",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iget5_locked",
        "fs/inode.c:iget5_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346208,
      "name": "find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
```

```json
{
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401648,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:784",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iget5_locked",
        "fs/inode.c:iget5_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401648,
      "name": "find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
```

```json
{
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581543280,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:784",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iget5_locked",
        "fs/inode.c:iget5_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543280,
      "name": "find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581702960,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:789",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702960,
      "name": "find_inode.isra.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581790208,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:789",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790208,
      "name": "find_inode.isra.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581908784,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:802",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581908784,
      "name": "find_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581981312,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:813",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581981312,
      "name": "find_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
```

```json
{
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582213216,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:814",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582213216,
      "name": "find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
```

```json
{
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582260672,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:813",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582260672,
      "name": "find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
```

```json
{
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582286256,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:820",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582286256,
      "name": "find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
```

```json
{
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582604736,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:824",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582604736,
      "name": "find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
```

```json
{
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583131168,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:905",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583131168,
      "name": "find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
```

```json
{
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583701552,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:904",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583701552,
      "name": "find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
```

```json
{
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583918976,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:906",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918976,
      "name": "find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
```

```json
{
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584124960,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:891",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584124960,
      "name": "find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493487504,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:813",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493487504,
      "name": "find_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
```

```json
{
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227045160,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:813",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227045160,
      "name": "find_inode",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287045040,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:813",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287045040,
      "name": "find_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273166240,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:813",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273166240,
      "name": "find_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581950048,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:813",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581950048,
      "name": "find_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581887616,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:813",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887616,
      "name": "find_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581941360,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:813",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581941360,
      "name": "find_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
  "name": "find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582008576,
      "name": "find_inode",
      "external": false,
      "loc": "fs/inode.c:813",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:inode_insert5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008576,
      "name": "find_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
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
struct inode * find_inode(struct super_block * sb, struct hlist_head * head, int (*)(struct inode *, void *) test, void * data)
```
</details>
</li>
</ul>
