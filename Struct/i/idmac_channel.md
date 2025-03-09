# Struct: <code>idmac_channel</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct idmac_channel {
    struct dma_chan dma_chan;
    dma_cookie_t completed;
    union ipu_channel_param params;
    enum ipu_channel link;
    enum ipu_channel_status status;
    void * client;
    unsigned int n_tx_desc;
    struct idmac_tx_desc * desc;
    struct scatterlist *[2] sg;
    struct list_head free_list;
    struct list_head queue;
    spinlock_t lock;
    struct mutex chan_mutex;
    bool sec_chan_en;
    int active_buffer;
    unsigned int eof_irq;
    char[16] eof_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct idmac_channel {
    struct dma_chan dma_chan;
    dma_cookie_t completed;
    union ipu_channel_param params;
    enum ipu_channel link;
    enum ipu_channel_status status;
    void * client;
    unsigned int n_tx_desc;
    struct idmac_tx_desc * desc;
    struct scatterlist *[2] sg;
    struct list_head free_list;
    struct list_head queue;
    spinlock_t lock;
    struct mutex chan_mutex;
    bool sec_chan_en;
    int active_buffer;
    unsigned int eof_irq;
    char[16] eof_name;
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct idmac_channel {
    struct dma_chan dma_chan;
    dma_cookie_t completed;
    union ipu_channel_param params;
    enum ipu_channel link;
    enum ipu_channel_status status;
    void * client;
    unsigned int n_tx_desc;
    struct idmac_tx_desc * desc;
    struct scatterlist *[2] sg;
    struct list_head free_list;
    struct list_head queue;
    spinlock_t lock;
    struct mutex chan_mutex;
    bool sec_chan_en;
    int active_buffer;
    unsigned int eof_irq;
    char[16] eof_name;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct idmac_channel {
    struct dma_chan dma_chan;
    dma_cookie_t completed;
    union ipu_channel_param params;
    enum ipu_channel link;
    enum ipu_channel_status status;
    void * client;
    unsigned int n_tx_desc;
    struct idmac_tx_desc * desc;
    struct scatterlist *[2] sg;
    struct list_head free_list;
    struct list_head queue;
    spinlock_t lock;
    struct mutex chan_mutex;
    bool sec_chan_en;
    int active_buffer;
    unsigned int eof_irq;
    char[16] eof_name;
}
```
</details>
</li>
</ul>
