# Function: <code>dma_fence_release</code>

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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585305824,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:171",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/sync_file.c:sync_file_free",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585305824,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585394864,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:168",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585394864,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585822992,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:167",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_copy_fences",
        "drivers/dma-buf/reservation.c:reservation_object_copy_fences",
        "drivers/dma-buf/reservation.c:reservation_object_copy_fences",
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585822992,
      "name": "dma_fence_release",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586068976,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:167",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_copy_fences",
        "drivers/dma-buf/reservation.c:reservation_object_copy_fences",
        "drivers/dma-buf/reservation.c:reservation_object_copy_fences",
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_shared_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_shared_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_shared_fence",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068976,
      "name": "dma_fence_release",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586213024,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:251",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_copy_fences",
        "drivers/dma-buf/reservation.c:reservation_object_copy_fences",
        "drivers/dma-buf/reservation.c:reservation_object_copy_fences",
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_shared_fence",
        "drivers/dma-buf/reservation.c:reservation_object_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586213024,
      "name": "dma_fence_release",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586456304,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:244",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_copy_fences",
        "drivers/dma-buf/reservation.c:reservation_object_copy_fences",
        "drivers/dma-buf/reservation.c:reservation_object_copy_fences",
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_shared_fence",
        "drivers/dma-buf/reservation.c:reservation_object_reserve_shared",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586456304,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586603168,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:228",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586603168,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587392944,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:228",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587392944,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587461536,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:438",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587461536,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587342672,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:519",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587342672,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587909104,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:519",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_excl",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587909104,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589259488,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:520",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_singleton",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_replace_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589259488,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590821856,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:530",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file",
        "drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_singleton",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_replace_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590821856,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591163392,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:531",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file",
        "drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled",
        "drivers/dma-buf/dma-resv.c:dma_resv_set_deadline",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_singleton",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_replace_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591163392,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591509376,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:531",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_import_sync_file",
        "drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled",
        "drivers/dma-buf/dma-resv.c:dma_resv_set_deadline",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_singleton",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_replace_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/dma-buf/sw_sync.c:sync_timeline_signal",
        "drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling",
        "drivers/gpu/drm/drm_file.c:drm_send_event_helper",
        "drivers/gpu/drm/drm_file.c:drm_event_cancel_free",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_timeline_signal_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_signal_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:syncobj_eventfd_entry_fence_func",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_handle_to_fd_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_create",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_free",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_replace_fence",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fence_add_wait",
        "drivers/gpu/drm/drm_writeback.c:drm_writeback_signal_completion",
        "drivers/gpu/drm/drm_writeback.c:drm_writeback_cleanup_job",
        "drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_wait_for_fences",
        "drivers/gpu/drm/drm_atomic_state_helper.c:__drm_atomic_helper_plane_destroy_state",
        "drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb",
        "drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591509376,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499489280,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:228",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499489280,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231961400,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:228",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231961400,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292771744,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:228",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292771744,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276705252,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:228",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276705252,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586293648,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:228",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586293648,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586135024,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:228",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586135024,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586551136,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:228",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586551136,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void dma_fence_release(struct kref * kref)
```

```json
{
  "name": "dma_fence_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586663008,
      "name": "dma_fence_release",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:228",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_release",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_copy_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence",
        "drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared",
        "drivers/dma-buf/dma-resv.c:dma_resv_fini",
        "drivers/dma-buf/sync_file.c:sync_file_release",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586663008,
      "name": "dma_fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void dma_fence_release(struct kref * kref)
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
