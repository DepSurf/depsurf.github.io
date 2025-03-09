# Struct: <code>receive_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct receive_queue {
    struct virtqueue * vq;
    struct napi_struct napi;
    struct page * pages;
    struct ewma_pkt_len mrg_avg_pkt_len;
    struct page_frag alloc_frag;
    struct scatterlist[19] sg;
    char[40] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct receive_queue {
    struct virtqueue * vq;
    struct napi_struct napi;
    struct page * pages;
    struct ewma_pkt_len mrg_avg_pkt_len;
    struct page_frag alloc_frag;
    struct scatterlist[19] sg;
    char[40] name;
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct receive_queue {
    struct virtqueue * vq;
    struct napi_struct napi;
    struct bpf_prog * xdp_prog;
    struct virtnet_rq_stats stats;
    struct page * pages;
    struct ewma_pkt_len mrg_avg_pkt_len;
    struct page_frag alloc_frag;
    struct scatterlist[19] sg;
    unsigned int min_buf_len;
    char[16] name;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct receive_queue {
    struct virtqueue * vq;
    struct napi_struct napi;
    struct bpf_prog * xdp_prog;
    struct virtnet_rq_stats stats;
    u16 calls;
    bool dim_enabled;
    struct dim dim;
    u32 packets_in_napi;
    struct virtnet_interrupt_coalesce intr_coal;
    struct page * pages;
    struct ewma_pkt_len mrg_avg_pkt_len;
    struct page_frag alloc_frag;
    struct scatterlist[19] sg;
    unsigned int min_buf_len;
    char[16] name;
    struct xdp_rxq_info xdp_rxq;
    struct virtnet_rq_dma * last_dma;
    bool do_dma;
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
struct receive_queue {
    struct virtqueue * vq;
    struct napi_struct napi;
    struct page * pages;
    struct ewma_pkt_len mrg_avg_pkt_len;
    struct page_frag alloc_frag;
    struct scatterlist[19] sg;
    char[40] name;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct receive_queue {
    struct virtqueue * vq;
    struct napi_struct napi;
    struct bpf_prog * xdp_prog;
    struct virtnet_rq_stats stats;
    struct page * pages;
    struct ewma_pkt_len mrg_avg_pkt_len;
    struct page_frag alloc_frag;
    struct scatterlist[19] sg;
    unsigned int min_buf_len;
    char[16] name;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 calls</code>
</li>
<li>
<b>Field added. </b>
<code>bool dim_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>struct dim dim</code>
</li>
<li>
<b>Field added. </b>
<code>u32 packets_in_napi</code>
</li>
<li>
<b>Field added. </b>
<code>struct virtnet_interrupt_coalesce intr_coal</code>
</li>
<li>
<b>Field added. </b>
<code>struct virtnet_rq_dma * last_dma</code>
</li>
<li>
<b>Field added. </b>
<code>bool do_dma</code>
</li>
</ul>
</details>
</li>
</ul>
