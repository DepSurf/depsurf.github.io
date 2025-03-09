# Function: <code>fuse_perm_getattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582073975,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1059",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
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
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582288599,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1064",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int fuse_perm_getattr(struct inode * inode, int mask)
```

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582372560,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1078",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582372560,
      "name": "fuse_perm_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int fuse_perm_getattr(struct inode * inode, int mask)
```

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582457008,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1078",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582457008,
      "name": "fuse_perm_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int fuse_perm_getattr(struct inode * inode, int mask)
```

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582607792,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1074",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582607792,
      "name": "fuse_perm_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int fuse_perm_getattr(struct inode * inode, int mask)
```

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582799232,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1083",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582799232,
      "name": "fuse_perm_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int fuse_perm_getattr(struct inode * inode, int mask)
```

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582902048,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1085",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582902048,
      "name": "fuse_perm_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int fuse_perm_getattr(struct inode * inode, int mask)
```

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583079488,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1072",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583079488,
      "name": "fuse_perm_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int fuse_perm_getattr(struct inode * inode, int mask)
```

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583187792,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1130",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583187792,
      "name": "fuse_perm_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583518075,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1130",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583627319,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1230",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583650470,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1247",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584009526,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1195",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584594579,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1275",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585272936,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1308",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585503416,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1374",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585740072,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1475",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int fuse_perm_getattr(struct inode * inode, int mask)
```

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494906008,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1130",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494906008,
      "name": "fuse_perm_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int fuse_perm_getattr(struct inode * inode, int mask)
```

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228318324,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1130",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228318324,
      "name": "fuse_perm_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int fuse_perm_getattr(struct inode * inode, int mask)
```

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288770928,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1130",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288770928,
      "name": "fuse_perm_getattr",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int fuse_perm_getattr(struct inode * inode, int mask)
```

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274217266,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1130",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274217266,
      "name": "fuse_perm_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int fuse_perm_getattr(struct inode * inode, int mask)
```

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583156528,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1130",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583156528,
      "name": "fuse_perm_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int fuse_perm_getattr(struct inode * inode, int mask)
```

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583093680,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1130",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583093680,
      "name": "fuse_perm_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int fuse_perm_getattr(struct inode * inode, int mask)
```

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583140560,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1130",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583140560,
      "name": "fuse_perm_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int fuse_perm_getattr(struct inode * inode, int mask)
```

```json
{
  "name": "fuse_perm_getattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583234112,
      "name": "fuse_perm_getattr",
      "external": false,
      "loc": "fs/fuse/dir.c:1130",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234112,
      "name": "fuse_perm_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int fuse_perm_getattr(struct inode * inode, int mask)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int fuse_perm_getattr(struct inode * inode, int mask)
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
