# Struct: <code>pl011_dmarx_data</code>

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
struct pl011_dmarx_data {
    struct dma_chan * chan;
    struct completion complete;
    bool use_buf_b;
    struct pl011_sgbuf sgbuf_a;
    struct pl011_sgbuf sgbuf_b;
    dma_cookie_t cookie;
    bool running;
    struct timer_list timer;
    unsigned int last_residue;
    long unsigned int last_jiffies;
    bool auto_poll_rate;
    unsigned int poll_rate;
    unsigned int poll_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pl011_dmarx_data {
    struct dma_chan * chan;
    struct completion complete;
    bool use_buf_b;
    struct pl011_sgbuf sgbuf_a;
    struct pl011_sgbuf sgbuf_b;
    dma_cookie_t cookie;
    bool running;
    struct timer_list timer;
    unsigned int last_residue;
    long unsigned int last_jiffies;
    bool auto_poll_rate;
    unsigned int poll_rate;
    unsigned int poll_timeout;
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
struct pl011_dmarx_data {
    struct dma_chan * chan;
    struct completion complete;
    bool use_buf_b;
    struct pl011_sgbuf sgbuf_a;
    struct pl011_sgbuf sgbuf_b;
    dma_cookie_t cookie;
    bool running;
    struct timer_list timer;
    unsigned int last_residue;
    long unsigned int last_jiffies;
    bool auto_poll_rate;
    unsigned int poll_rate;
    unsigned int poll_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct pl011_dmarx_data {
    struct dma_chan * chan;
    struct completion complete;
    bool use_buf_b;
    struct pl011_sgbuf sgbuf_a;
    struct pl011_sgbuf sgbuf_b;
    dma_cookie_t cookie;
    bool running;
    struct timer_list timer;
    unsigned int last_residue;
    long unsigned int last_jiffies;
    bool auto_poll_rate;
    unsigned int poll_rate;
    unsigned int poll_timeout;
}
```
</details>
</li>
</ul>
