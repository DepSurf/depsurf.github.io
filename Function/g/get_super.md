# Function: <code>get_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581004560,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:625",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:get_super_thawed"
      ],
      "caller_func": [
        "fs/super.c:get_super_thawed",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:__invalidate_device",
        "fs/quota/quota.c:SyS_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581004560,
      "name": "get_super.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071581004768,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581163107,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:639",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:get_super_thawed"
      ],
      "caller_func": [
        "fs/super.c:get_super_thawed",
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:SyS_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162816,
      "name": "get_super.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446744071581163024,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581239888,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:687",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:SyS_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581239888,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581287264,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:690",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:SyS_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287264,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581426800,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:690",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:SyS_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581426800,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581584672,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:722",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581584672,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581671136,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:726",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581671136,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581789328,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:780",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581789328,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581861568,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:786",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581861568,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582086336,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:786",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:check_disk_change",
        "fs/block_dev.c:check_disk_size_change",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582086336,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582137248,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:750",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582137248,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582162016,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:751",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582162016,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582478992,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:751",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:__invalidate_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582478992,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582999824,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:750",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:__invalidate_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582999824,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583561216,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:793",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:__invalidate_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583561216,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583777360,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:800",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:fs_mark_dead",
        "block/bdev.c:__invalidate_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583777360,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493333424,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:786",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493333424,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226925892,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:786",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226925892,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286872064,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:786",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286872064,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273063584,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:786",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273063584,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581830304,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:786",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830304,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581767968,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:786",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581767968,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581821616,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:786",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581821616,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct super_block * get_super(struct block_device * bdev)
```

```json
{
  "name": "get_super",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581889664,
      "name": "get_super",
      "external": true,
      "loc": "fs/super.c:786",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__invalidate_device",
        "fs/block_dev.c:freeze_bdev",
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581889664,
      "name": "get_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct super_block * get_super(struct block_device * bdev)
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
