# Struct: <code>vring_virtqueue_packed</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue_packed {
    struct (anon) vring;
    bool avail_wrap_counter;
    u16 avail_used_flags;
    u16 next_avail_idx;
    u16 event_flags_shadow;
    struct vring_desc_state_packed * desc_state;
    struct vring_desc_extra * desc_extra;
    dma_addr_t ring_dma_addr;
    dma_addr_t driver_event_dma_addr;
    dma_addr_t device_event_dma_addr;
    size_t ring_size_in_bytes;
    size_t event_size_in_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue_packed {
    struct (anon) vring;
    bool avail_wrap_counter;
    u16 avail_used_flags;
    u16 next_avail_idx;
    u16 event_flags_shadow;
    struct vring_desc_state_packed * desc_state;
    struct vring_desc_extra * desc_extra;
    dma_addr_t ring_dma_addr;
    dma_addr_t driver_event_dma_addr;
    dma_addr_t device_event_dma_addr;
    size_t ring_size_in_bytes;
    size_t event_size_in_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue_packed {
    struct (anon) vring;
    bool avail_wrap_counter;
    u16 avail_used_flags;
    u16 next_avail_idx;
    u16 event_flags_shadow;
    struct vring_desc_state_packed * desc_state;
    struct vring_desc_extra * desc_extra;
    dma_addr_t ring_dma_addr;
    dma_addr_t driver_event_dma_addr;
    dma_addr_t device_event_dma_addr;
    size_t ring_size_in_bytes;
    size_t event_size_in_bytes;
}
```
</details>
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
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct vring_virtqueue_packed {
    struct (anon) vring;
    bool avail_wrap_counter;
    u16 avail_used_flags;
    u16 next_avail_idx;
    u16 event_flags_shadow;
    struct vring_desc_state_packed * desc_state;
    struct vring_desc_extra * desc_extra;
    dma_addr_t ring_dma_addr;
    dma_addr_t driver_event_dma_addr;
    dma_addr_t device_event_dma_addr;
    size_t ring_size_in_bytes;
    size_t event_size_in_bytes;
}
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
