# Function: <code>dma_fence_chain_walk</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586460848,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586460848,
      "name": "dma_fence_chain_walk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071586461440,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586608208,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586608208,
      "name": "dma_fence_chain_walk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
    },
    {
      "addr": 18446744071586608864,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587397360,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587396352,
      "name": "dma_fence_chain_walk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
    },
    {
      "addr": 18446744071587397088,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587465936,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587464576,
      "name": "dma_fence_chain_walk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
    },
    {
      "addr": 18446744071587465328,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587347852,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587346528,
      "name": "dma_fence_chain_walk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 718
    },
    {
      "addr": 18446744071587347248,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587914268,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587912944,
      "name": "dma_fence_chain_walk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 718
    },
    {
      "addr": 18446744071587913664,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589264480,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589264480,
      "name": "dma_fence_chain_walk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
    },
    {
      "addr": 18446744071589265248,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590826672,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590826672,
      "name": "dma_fence_chain_walk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
    },
    {
      "addr": 18446744071590827456,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591168480,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591168480,
      "name": "dma_fence_chain_walk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
    },
    {
      "addr": 18446744071591169248,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591514464,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591514464,
      "name": "dma_fence_chain_walk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
    },
    {
      "addr": 18446744071591515232,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499496152,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499496152,
      "name": "dma_fence_chain_walk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 18446603336499496984,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231967268,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231967268,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292780416,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292780416,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276710234,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276710234,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586298688,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586298688,
      "name": "dma_fence_chain_walk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
    },
    {
      "addr": 18446744071586299344,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586140064,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586140064,
      "name": "dma_fence_chain_walk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
    },
    {
      "addr": 18446744071586140720,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586556176,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586556176,
      "name": "dma_fence_chain_walk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
    },
    {
      "addr": 18446744071586556832,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_chain_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586668240,
      "name": "dma_fence_chain_walk",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence-chain.c:39",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586668240,
      "name": "dma_fence_chain_walk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071586668928,
      "name": "dma_fence_chain_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct dma_fence * dma_fence_chain_walk(struct dma_fence * fence)
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
