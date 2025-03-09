# Function: <code>hv_ringbuffer_get_debuginfo</code>

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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int hv_ringbuffer_get_debuginfo(struct hv_ring_buffer_info * ring_info, struct hv_ring_buffer_debug_info * debug_info)
```

```json
{
  "name": "hv_ringbuffer_get_debuginfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587575600,
      "name": "hv_ringbuffer_get_debuginfo",
      "external": true,
      "loc": "drivers/hv/ring_buffer.c:156",
      "file": "drivers/hv/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hv/vmbus_drv.c:in_write_bytes_avail_show",
        "drivers/hv/vmbus_drv.c:in_read_bytes_avail_show",
        "drivers/hv/vmbus_drv.c:in_write_index_show",
        "drivers/hv/vmbus_drv.c:in_read_index_show",
        "drivers/hv/vmbus_drv.c:in_intr_mask_show",
        "drivers/hv/vmbus_drv.c:out_write_bytes_avail_show",
        "drivers/hv/vmbus_drv.c:out_read_bytes_avail_show",
        "drivers/hv/vmbus_drv.c:out_write_index_show",
        "drivers/hv/vmbus_drv.c:out_read_index_show",
        "drivers/hv/vmbus_drv.c:out_intr_mask_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587575600,
      "name": "hv_ringbuffer_get_debuginfo",
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
int hv_ringbuffer_get_debuginfo(struct hv_ring_buffer_info * ring_info, struct hv_ring_buffer_debug_info * debug_info)
```
</details>
</li>
</ul>
