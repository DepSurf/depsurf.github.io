# Function: <code>bdi_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580610096,
      "name": "bdi_init",
      "external": true,
      "loc": "mm/backing-dev.c:772",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:default_bdi_init",
        "fs/fuse/inode.c:fuse_fill_super",
        "block/blk-core.c:blk_alloc_queue_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580610096,
      "name": "bdi_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580713600,
      "name": "bdi_init",
      "external": true,
      "loc": "mm/backing-dev.c:772",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:default_bdi_init",
        "fs/fuse/inode.c:fuse_fill_super",
        "block/blk-core.c:blk_alloc_queue_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580713600,
      "name": "bdi_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580779440,
      "name": "bdi_init",
      "external": true,
      "loc": "mm/backing-dev.c:778",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:default_bdi_init",
        "fs/fuse/inode.c:fuse_fill_super",
        "block/blk-core.c:blk_alloc_queue_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580779440,
      "name": "bdi_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580817318,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:823",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
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
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580907462,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:838",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
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
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581043654,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:836",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
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
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581120857,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:839",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581185485,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:826",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
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
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581244141,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:849",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581433163,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:848",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc"
      ],
      "caller_func": [
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435047,
      "name": "bdi_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581475679,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:715",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc"
      ],
      "caller_func": [
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591325644,
      "name": "bdi_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581496431,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:714",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc"
      ],
      "caller_func": [
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591267700,
      "name": "bdi_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581756911,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:787",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc"
      ],
      "caller_func": [
        "mm/backing-dev.c:default_bdi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592193007,
      "name": "bdi_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582138800,
      "name": "bdi_init",
      "external": true,
      "loc": "mm/backing-dev.c:777",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc",
        "drivers/base/init.c:driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138800,
      "name": "bdi_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582616240,
      "name": "bdi_init",
      "external": true,
      "loc": "mm/backing-dev.c:904",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc",
        "drivers/base/init.c:driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616240,
      "name": "bdi_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582824976,
      "name": "bdi_init",
      "external": true,
      "loc": "mm/backing-dev.c:917",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc",
        "drivers/base/init.c:driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582824976,
      "name": "bdi_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int bdi_init(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582999376,
      "name": "bdi_init",
      "external": true,
      "loc": "mm/backing-dev.c:912",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_alloc",
        "drivers/base/init.c:driver_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582999376,
      "name": "bdi_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492643064,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:849",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
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
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226485076,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:849",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
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
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285960024,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:849",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
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
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272658622,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:849",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
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
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581212989,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:849",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
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
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581159693,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:849",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
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
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581204189,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:849",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
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
  "name": "bdi_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581267517,
      "name": "bdi_init",
      "external": false,
      "loc": "mm/backing-dev.c:849",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_alloc_node",
        "mm/backing-dev.c:default_bdi_init"
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
int bdi_init(struct backing_dev_info * bdi)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bdi_init(struct backing_dev_info * bdi)
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
