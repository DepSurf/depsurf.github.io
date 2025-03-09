# Function: <code>shmem_unuse_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580595816,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:644",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_unuse"
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
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580696353,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1061",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_unuse"
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
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580761967,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1086",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_unuse"
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
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580796716,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1111",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_unuse"
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
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580886493,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1134",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_unuse"
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
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581022899,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1154",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_unuse"
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
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581100523,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1126",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_unuse"
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
int shmem_unuse_inode(struct inode * inode, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581162880,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1193",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162880,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1275
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
int shmem_unuse_inode(struct inode * inode, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581220800,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1208",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581220800,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1275
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
int shmem_unuse_inode(struct inode * inode, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581392496,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1212",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581392496,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1382
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
int shmem_unuse_inode(struct inode * inode, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581450352,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1266",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581450352,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1394
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
int shmem_unuse_inode(struct inode * inode, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581471280,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1240",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471280,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1409
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
int shmem_unuse_inode(struct inode * inode, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581714480,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1251",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714480,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1432
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
int shmem_unuse_inode(struct inode * inode, unsigned int type)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582091648,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1234",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582091648,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 905
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
int shmem_unuse_inode(struct inode * inode, unsigned int type)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582566464,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1252",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582566464,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 905
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
int shmem_unuse_inode(struct inode * inode, unsigned int type)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582772976,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1267",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582772976,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1007
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
int shmem_unuse_inode(struct inode * inode, unsigned int type)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582949184,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1345",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582949184,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1007
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
int shmem_unuse_inode(struct inode * inode, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492606016,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1208",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492606016,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 988
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
int shmem_unuse_inode(struct inode * inode, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226461352,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1208",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226461352,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1004
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
int shmem_unuse_inode(struct inode * inode, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285924880,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1208",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285924880,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1320
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
int shmem_unuse_inode(struct inode * inode, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272636662,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1208",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272636662,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
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
int shmem_unuse_inode(struct inode * inode, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581189648,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1208",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189648,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1275
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
int shmem_unuse_inode(struct inode * inode, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136400,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1208",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136400,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1275
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
int shmem_unuse_inode(struct inode * inode, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581180848,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1208",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581180848,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1275
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
int shmem_unuse_inode(struct inode * inode, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "shmem_unuse_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581244064,
      "name": "shmem_unuse_inode",
      "external": false,
      "loc": "mm/shmem.c:1208",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581244064,
      "name": "shmem_unuse_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1285
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
int shmem_unuse_inode(struct inode * inode, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool frontswap</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * fs_pages_to_unuse</code>
</li>
</ul>
</details>
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
