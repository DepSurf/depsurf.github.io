# Struct: <code>musb_hw_ep</code>

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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct musb_hw_ep {
    struct musb * musb;
    void * fifo;
    void * regs;
    void * conf;
    u8 epnum;
    bool is_shared_fifo;
    bool tx_double_buffered;
    bool rx_double_buffered;
    u16 max_packet_sz_tx;
    u16 max_packet_sz_rx;
    struct dma_channel * tx_channel;
    struct dma_channel * rx_channel;
    dma_addr_t fifo_async;
    dma_addr_t fifo_sync;
    void * fifo_sync_va;
    struct musb_qh * in_qh;
    struct musb_qh * out_qh;
    u8 rx_reinit;
    u8 tx_reinit;
    struct musb_ep ep_in;
    struct musb_ep ep_out;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct musb_hw_ep {
    struct musb * musb;
    void * fifo;
    void * regs;
    void * conf;
    u8 epnum;
    bool is_shared_fifo;
    bool tx_double_buffered;
    bool rx_double_buffered;
    u16 max_packet_sz_tx;
    u16 max_packet_sz_rx;
    struct dma_channel * tx_channel;
    struct dma_channel * rx_channel;
    dma_addr_t fifo_async;
    dma_addr_t fifo_sync;
    void * fifo_sync_va;
    struct musb_qh * in_qh;
    struct musb_qh * out_qh;
    u8 rx_reinit;
    u8 tx_reinit;
    struct musb_ep ep_in;
    struct musb_ep ep_out;
}
```
</details>
</li>
</ul>
