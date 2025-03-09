# Function: <code>fence_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fence_release(struct kref * kref)
```

```json
{
  "name": "fence_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584759568,
      "name": "fence_release",
      "external": true,
      "loc": "drivers/dma-buf/fence.c:172",
      "file": "drivers/dma-buf/fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584759568,
      "name": "fence_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fence_release(struct kref * kref)
```

```json
{
  "name": "fence_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585116176,
      "name": "fence_release",
      "external": true,
      "loc": "drivers/dma-buf/fence.c:172",
      "file": "drivers/dma-buf/fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_poll",
        "drivers/dma-buf/dma-buf.c:dma_buf_release",
        "drivers/dma-buf/dma-buf.c:dma_buf_release",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/reservation.c:reservation_object_add_excl_fence",
        "drivers/dma-buf/fence-array.c:fence_array_release",
        "drivers/dma-buf/fence-array.c:fence_array_enable_signaling",
        "drivers/dma-buf/fence-array.c:fence_array_cb_func",
        "drivers/dma-buf/sync_file.c:sync_file_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585116176,
      "name": "fence_release",
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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void fence_release(struct kref * kref)
```
</details>
</li>
</ul>
