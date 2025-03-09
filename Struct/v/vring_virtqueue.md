# Struct: <code>vring_virtqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    struct vring vring;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    u16 avail_flags_shadow;
    u16 avail_idx_shadow;
    bool (*)(struct virtqueue *) notify;
    void *[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    struct vring vring;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    u16 avail_flags_shadow;
    u16 avail_idx_shadow;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
    size_t queue_size_in_bytes;
    dma_addr_t queue_dma_addr;
    struct vring_desc_state[0] desc_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    struct vring vring;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    u16 avail_flags_shadow;
    u16 avail_idx_shadow;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
    size_t queue_size_in_bytes;
    dma_addr_t queue_dma_addr;
    struct vring_desc_state[0] desc_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    struct vring vring;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    u16 avail_flags_shadow;
    u16 avail_idx_shadow;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
    size_t queue_size_in_bytes;
    dma_addr_t queue_dma_addr;
    struct vring_desc_state[0] desc_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    struct vring vring;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    u16 avail_flags_shadow;
    u16 avail_idx_shadow;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
    size_t queue_size_in_bytes;
    dma_addr_t queue_dma_addr;
    struct vring_desc_state[0] desc_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    struct vring vring;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    u16 avail_flags_shadow;
    u16 avail_idx_shadow;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
    size_t queue_size_in_bytes;
    dma_addr_t queue_dma_addr;
    struct vring_desc_state[0] desc_state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    struct (anon) split;
    struct (anon) packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    struct (anon) split;
    struct (anon) packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    struct (anon) split;
    struct (anon) packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    struct (anon) split;
    struct (anon) packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    struct (anon) split;
    struct (anon) packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    struct (anon) split;
    struct (anon) packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    bool event_triggered;
    struct (anon) split;
    struct (anon) packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    bool event_triggered;
    struct (anon) split;
    struct (anon) packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    bool event_triggered;
    struct vring_virtqueue_split split;
    struct vring_virtqueue_packed packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    bool event_triggered;
    struct vring_virtqueue_split split;
    struct vring_virtqueue_packed packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
    struct device * dma_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    bool premapped;
    bool do_unmap;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    bool event_triggered;
    struct vring_virtqueue_split split;
    struct vring_virtqueue_packed packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
    struct device * dma_dev;
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
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    struct (anon) split;
    struct (anon) packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    struct (anon) split;
    struct (anon) packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    struct (anon) split;
    struct (anon) packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    struct (anon) split;
    struct (anon) packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
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
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    struct (anon) split;
    struct (anon) packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    struct (anon) split;
    struct (anon) packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    struct (anon) split;
    struct (anon) packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct vring_virtqueue {
    struct virtqueue vq;
    bool packed_ring;
    bool use_dma_api;
    bool weak_barriers;
    bool broken;
    bool indirect;
    bool event;
    unsigned int free_head;
    unsigned int num_added;
    u16 last_used_idx;
    struct (anon) split;
    struct (anon) packed;
    bool (*)(struct virtqueue *) notify;
    bool we_own_ring;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool we_own_ring</code>
</li>
<li>
<b>Field added. </b>
<code>size_t queue_size_in_bytes</code>
</li>
<li>
<b>Field added. </b>
<code>dma_addr_t queue_dma_addr</code>
</li>
<li>
<b>Field added. </b>
<code>struct vring_desc_state[0] desc_state</code>
</li>
<li>
<b>Field removed. </b>
<code>void *[0] data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool packed_ring</code>
</li>
<li>
<b>Field added. </b>
<code>bool use_dma_api</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) split</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) packed</code>
</li>
<li>
<b>Field removed. </b>
<code>struct vring vring</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 avail_flags_shadow</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 avail_idx_shadow</code>
</li>
<li>
<b>Field removed. </b>
<code>size_t queue_size_in_bytes</code>
</li>
<li>
<b>Field removed. </b>
<code>dma_addr_t queue_dma_addr</code>
</li>
<li>
<b>Field removed. </b>
<code>struct vring_desc_state[0] desc_state</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool event_triggered</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct (anon) split</code> ➡️ <code>struct vring_virtqueue_split split</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct (anon) packed</code> ➡️ <code>struct vring_virtqueue_packed packed</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct device * dma_dev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool premapped</code>
</li>
<li>
<b>Field added. </b>
<code>bool do_unmap</code>
</li>
</ul>
</details>
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
