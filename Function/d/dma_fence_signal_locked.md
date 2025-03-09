# Function: <code>dma_fence_signal_locked</code>

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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585304928,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:66",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585304928,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585393888,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:68",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585393888,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585823392,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:67",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585823392,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586069376,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:67",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586069376,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586213920,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:136",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586213920,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:129",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586459520,
      "name": "dma_fence_signal_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586455952,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586602688,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:129",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586602688,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587391568,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:129",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587391568,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587459952,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:330",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587459952,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587342309,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:432",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587341920,
      "name": "dma_fence_signal_locked",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587908741,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:432",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587908512,
      "name": "dma_fence_signal_locked",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589259453,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:433",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589258576,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590821805,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:441",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590820304,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591162941,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:442",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591161584,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591508925,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:442",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub"
      ],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_pt_create",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591507520,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499488680,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:129",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499488680,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231960784,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:129",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231960784,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292770848,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:129",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292770848,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276704774,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:129",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276704774,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586293168,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:129",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586293168,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586134544,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:129",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586134544,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586550656,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:129",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586550656,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int dma_fence_signal_locked(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586662496,
      "name": "dma_fence_signal_locked",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:129",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_status",
        "drivers/dma-buf/dma-fence.c:dma_fence_add_callback",
        "drivers/dma-buf/dma-fence.c:dma_fence_release",
        "drivers/dma-buf/dma-fence.c:dma_fence_signal",
        "drivers/dma-buf/dma-fence.c:dma_fence_get_stub",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/dma-buf/sync_debug.c:sync_print_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586662496,
      "name": "dma_fence_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int dma_fence_signal_locked(struct dma_fence * fence)
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
