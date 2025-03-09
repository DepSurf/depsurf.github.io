# Function: <code>ratelimit_state_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595188603,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:34",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581978012,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:34",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
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
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579753711,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:39",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581914110,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:39",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582190166,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:39",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
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
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579779839,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:39",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582005247,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:39",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582279590,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:39",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579772287,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:39",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582224455,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:39",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071582364072,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:39",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584913399,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:39",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224455,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579804511,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582371175,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071582514856,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585332991,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582371175,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579484023,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579838731,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582505056,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071582705447,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585573878,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582505056,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579517303,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579885387,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582605328,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071582808353,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585698560,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582605328,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579536983,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579919995,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582777280,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071582983400,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585924574,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582777280,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579563047,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579970059,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582880400,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071583089643,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586068011,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880400,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579595063,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580017357,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583194320,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071583409307,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586797538,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:alloc_dev_data"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194320,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579575031,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579995483,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583290704,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071583524843,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586856290,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:alloc_dev_data"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583290704,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579580727,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579996939,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583314832,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071583547995,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586742173,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583314832,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615205003,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:sld_state_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579654915,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580128971,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583657984,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071583906139,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587294061,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583657984,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616977986,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:sld_state_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579750651,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580271003,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584228304,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071584484254,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588613014,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228304,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627598905,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:sld_state_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579882523,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580478507,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627921173,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_init_fs"
      ],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071585148510,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590073414,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584870864,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619352985,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:sld_state_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579931723,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580550075,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619684277,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_init_fs"
      ],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071585377662,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590385046,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585095888,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621647001,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:sld_state_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579971043,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580611547,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621990741,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_init_fs"
      ],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071585612509,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590725203,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:9",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585327600,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490722680,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491152048,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494532936,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446603336494797492,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494532936,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224778080,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 3225179792,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3227996004,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 3228216872,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227996004,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283545452,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284054976,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288342720,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 13835058055288634928,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288342720,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271437736,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271708470,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270737940,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274126560,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579539351,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579938795,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582849136,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071583058379,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585828987,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582849136,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579468113,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579876987,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582786288,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071582995531,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585688171,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582786288,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579536631,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579930331,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582838016,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071583046987,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586018027,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582838016,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```

```json
{
  "name": "ratelimit_state_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579569639,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579975947,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:devkmsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582924624,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    },
    {
      "addr": 18446744071583137051,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586125979,
      "name": "ratelimit_state_init",
      "external": false,
      "loc": "include/linux/ratelimit.h:40",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582924624,
      "name": "ratelimit_state_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void ratelimit_state_init(struct ratelimit_state * rs, int interval, int burst)
```
</details>
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
