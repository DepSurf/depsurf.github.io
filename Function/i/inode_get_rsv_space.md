# Function: <code>inode_get_rsv_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
qsize_t inode_get_rsv_space(struct inode * inode)
```

```json
{
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581404784,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1604",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:__dquot_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581404784,
      "name": "inode_get_rsv_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
qsize_t inode_get_rsv_space(struct inode * inode)
```

```json
{
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581586272,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1612",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586272,
      "name": "inode_get_rsv_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
qsize_t inode_get_rsv_space(struct inode * inode)
```

```json
{
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581674656,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1609",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581674656,
      "name": "inode_get_rsv_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581735353,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1635",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729824,
      "name": "inode_get_rsv_space.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581882315,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1617",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:__dquot_initialize"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581876400,
      "name": "inode_get_rsv_space.part.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582067838,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1614",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:__dquot_initialize"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057744,
      "name": "inode_get_rsv_space.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582161934,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1614",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:__dquot_initialize"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152048,
      "name": "inode_get_rsv_space.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582328533,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1624",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582427733,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1626",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582723168,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1624",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582794320,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1625",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582822185,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1623",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583153470,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1628",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583635025,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1638",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584240257,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1638",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584470785,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1696",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584693729,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1650",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494037096,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1626",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227490412,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1626",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287678344,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1626",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273543352,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1626",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582396469,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1626",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582334165,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1626",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582386949,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1626",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_get_rsv_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582457235,
      "name": "inode_get_rsv_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1626",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_initialize"
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
qsize_t inode_get_rsv_space(struct inode * inode)
```
</details>
</li>
</ul>
