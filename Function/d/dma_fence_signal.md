# Function: <code>dma_fence_signal</code>

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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585306432,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:109",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_poll",
        "drivers/dma-buf/sync_debug.c:sync_debugfs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585306432,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585395024,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:109",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585395024,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585824384,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:108",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_copy_fences",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585824384,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586070880,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:108",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_copy_fences",
        "drivers/dma-buf/reservation.c:reservation_object_add_shared_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_shared_fence",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586070880,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586215328,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:180",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_copy_fences",
        "drivers/dma-buf/reservation.c:reservation_object_add_shared_fence",
        "drivers/dma-buf/reservation.c:reservation_object_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586215328,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586457600,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:173",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_copy_fences",
        "drivers/dma-buf/reservation.c:reservation_object_add_shared_fence",
        "drivers/dma-buf/reservation.c:reservation_object_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586457600,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586602944,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:169",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586602944,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587394071,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:169",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587391824,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587462327,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:370",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587460192,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587344282,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:451",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587341968,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587910682,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:451",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587908560,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589262054,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:452",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_describe",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589258624,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590823974,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:460",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_describe",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590820368,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591163958,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:461",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_describe",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591161648,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591509942,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:461",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_describe",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout"
      ],
      "caller_func": [
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences",
        "drivers/dma-buf/sync_file.c:sync_fill_fence_info",
        "drivers/dma-buf/sync_file.c:sync_file_poll",
        "drivers/gpu/drm/drm_file.c:drm_send_event_helper",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl",
        "drivers/gpu/drm/drm_writeback.c:drm_writeback_signal_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591507584,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499489712,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:169",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499489712,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231961148,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:169",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231961148,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292771296,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:169",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292771296,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276705010,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:169",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276705010,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586293424,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:169",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586293424,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586134800,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:169",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586134800,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586550912,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:169",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586550912,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int dma_fence_signal(struct dma_fence * fence)
```

```json
{
  "name": "dma_fence_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586662784,
      "name": "dma_fence_signal",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:169",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586662784,
      "name": "dma_fence_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int dma_fence_signal(struct dma_fence * fence)
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
