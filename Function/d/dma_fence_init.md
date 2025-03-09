# Function: <code>dma_fence_init</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, unsigned int seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585304432,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:530",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585304432,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, unsigned int seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585393616,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:559",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585393616,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, unsigned int seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585823184,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:558",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585823184,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, unsigned int seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586069168,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:559",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586069168,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, unsigned int seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586213216,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:651",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586213216,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586455232,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:661",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586455232,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586604960,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:646",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586604960,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587393536,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:638",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sync_pt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587393536,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587461824,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:848",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sync_pt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587461824,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587342064,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:929",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sync_pt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587342064,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587908048,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:929",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sync_pt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587908048,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589258720,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:943",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sync_pt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589258720,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590820480,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:947",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sync_pt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590820480,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591162639,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:1007",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub",
        "drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sync_pt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591161760,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591508622,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:1008",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub",
        "drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/gpu/drm/drm_crtc.c:drm_crtc_create_fence",
        "drivers/gpu/drm/drm_writeback.c:drm_writeback_get_out_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591507696,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499487672,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:646",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499487672,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231961816,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:646",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231961816,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292772288,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:646",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292772288,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276706720,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:646",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276706720,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586295440,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:646",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586295440,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586136816,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:646",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586136816,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586552928,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:646",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586552928,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, u64 seqno)
```

```json
{
  "name": "dma_fence_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586664912,
      "name": "dma_fence_init",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:646",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_create",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586664912,
      "name": "dma_fence_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void dma_fence_init(struct dma_fence * fence, const struct dma_fence_ops * ops, spinlock_t * lock, u64 context, unsigned int seqno)
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int seqno</code> ➡️ <code>u64 seqno</code>
</li>
</ul>
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
