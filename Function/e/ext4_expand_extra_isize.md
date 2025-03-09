# Function: <code>ext4_expand_extra_isize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581579607,
      "name": "ext4_expand_extra_isize",
      "external": false,
      "loc": "fs/ext4/inode.c:5060",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty"
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
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581766519,
      "name": "ext4_expand_extra_isize",
      "external": false,
      "loc": "fs/ext4/inode.c:5401",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty"
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
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581855614,
      "name": "ext4_expand_extra_isize",
      "external": false,
      "loc": "fs/ext4/inode.c:5545",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582002928,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:5782",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002928,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582152928,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:5835",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152928,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582340496,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:5931",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340496,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582439616,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:5984",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439616,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582609104,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:6006",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609104,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582710016,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:6035",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582710016,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583021376,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:5755",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583021376,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583097008,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:5848",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583097008,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583122032,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:5845",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setproject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583122032,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583462880,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:5785",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setproject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583462880,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583986208,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:5863",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setproject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986208,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 469
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584615376,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:6007",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setproject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584615376,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584842112,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:5819",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setproject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584842112,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585074976,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:5839",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl_setproject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585074976,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494367632,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:6035",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494367632,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227802000,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:6035",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227802000,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288100208,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:6035",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288100208,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273795134,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:6035",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273795134,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582678752,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:6035",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582678752,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582615920,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:6035",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615920,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582668608,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:6035",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582668608,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```

```json
{
  "name": "ext4_expand_extra_isize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582752384,
      "name": "ext4_expand_extra_isize",
      "external": true,
      "loc": "fs/ext4/inode.c:6035",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582752384,
      "name": "ext4_expand_extra_isize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int ext4_expand_extra_isize(struct inode * inode, unsigned int new_extra_isize, struct ext4_iloc * iloc)
```
</details>
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
