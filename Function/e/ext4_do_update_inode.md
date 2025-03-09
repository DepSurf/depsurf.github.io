# Function: <code>ext4_do_update_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581577348,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:4458",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758384,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:4784",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758384,
      "name": "ext4_do_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1863
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581847312,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:4926",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847312,
      "name": "ext4_do_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1869
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581986016,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5034",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986016,
      "name": "ext4_do_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1901
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582135440,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5091",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582135440,
      "name": "ext4_do_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1901
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582325248,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5179",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582325248,
      "name": "ext4_do_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1934
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582422208,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5226",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582422208,
      "name": "ext4_do_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1946
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582591200,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5240",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582591200,
      "name": "ext4_do_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2010
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582691952,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5248",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582691952,
      "name": "ext4_do_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1953
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
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583004128,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:4963",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583004128,
      "name": "ext4_do_update_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1918
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583082032,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5024",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583082032,
      "name": "ext4_do_update_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2018
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583107072,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5019",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583107072,
      "name": "ext4_do_update_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2002
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:4951",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446320,
      "name": "ext4_do_update_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2222
    },
    {
      "addr": 18446744071592258146,
      "name": "ext4_do_update_inode.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583968976,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5116",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968976,
      "name": "ext4_do_update_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 999
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584596848,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5217",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584596848,
      "name": "ext4_do_update_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1011
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584823152,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5029",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584823152,
      "name": "ext4_do_update_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1014
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585056128,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5051",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585056128,
      "name": "ext4_do_update_inode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1014
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494349040,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5248",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494349040,
      "name": "ext4_do_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1928
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227782780,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5248",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227782780,
      "name": "ext4_do_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1984
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288076528,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5248",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288076528,
      "name": "ext4_do_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2400
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273779048,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5248",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273779048,
      "name": "ext4_do_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1710
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582660688,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5248",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582660688,
      "name": "ext4_do_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1953
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582597856,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5248",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582597856,
      "name": "ext4_do_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1953
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582650544,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5248",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582650544,
      "name": "ext4_do_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1953
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_do_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582735552,
      "name": "ext4_do_update_inode",
      "external": false,
      "loc": "fs/ext4/inode.c:5248",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_iloc_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582735552,
      "name": "ext4_do_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1956
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
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int ext4_do_update_inode(handle_t * handle, struct inode * inode, struct ext4_iloc * iloc)
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
