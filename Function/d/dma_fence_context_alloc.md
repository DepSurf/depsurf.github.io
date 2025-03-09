# Function: <code>dma_fence_context_alloc</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585305792,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:47",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585305792,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585394832,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:49",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585394832,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585822688,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:48",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585822688,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586068448,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:48",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068448,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586212736,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:113",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586212736,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:106",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586459501,
      "name": "dma_fence_context_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071586455120,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586602656,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:106",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586602656,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587391472,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:106",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sync_timeline_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587391472,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587459856,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:152",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sync_timeline_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587459856,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587341504,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:177",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587341504,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587907952,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:177",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587907952,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589257520,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:178",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_singleton",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589257520,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590819120,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:186",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_singleton",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590819120,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591160208,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:187",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_singleton",
        "drivers/dma-buf/sw_sync.c:sync_timeline_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591160208,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591506144,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:187",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_singleton",
        "drivers/dma-buf/sw_sync.c:sync_timeline_create",
        "drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes",
        "drivers/gpu/drm/drm_writeback.c:drm_writeback_connector_init_with_encoder"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591506144,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499488568,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:106",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499488568,
      "name": "dma_fence_context_alloc",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231960664,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:106",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231960664,
      "name": "dma_fence_context_alloc",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292770528,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:106",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292770528,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276704720,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:106",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276704720,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586293136,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:106",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586293136,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586134512,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:106",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586134512,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586550624,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:106",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586550624,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
u64 dma_fence_context_alloc(unsigned int num)
```

```json
{
  "name": "dma_fence_context_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586662464,
      "name": "dma_fence_context_alloc",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:106",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586662464,
      "name": "dma_fence_context_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
u64 dma_fence_context_alloc(unsigned int num)
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
