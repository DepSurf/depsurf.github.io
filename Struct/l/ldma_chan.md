# Struct: <code>ldma_chan</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ldma_chan {
    struct virt_dma_chan vchan;
    struct ldma_port * port;
    char[8] name;
    int nr;
    u32 flags;
    enum ldma_chan_on_off onoff;
    dma_addr_t desc_phys;
    void * desc_base;
    u32 desc_cnt;
    int rst;
    u32 hdrm_len;
    bool hdrm_csum;
    u32 boff_len;
    u32 data_endian;
    u32 desc_endian;
    bool pden;
    bool desc_rx_np;
    bool data_endian_en;
    bool desc_endian_en;
    bool abc_en;
    bool desc_init;
    struct dma_pool * desc_pool;
    u32 desc_num;
    struct dw2_desc_sw * ds;
    struct work_struct work;
    struct dma_slave_config config;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ldma_chan {
    struct virt_dma_chan vchan;
    struct ldma_port * port;
    char[8] name;
    int nr;
    u32 flags;
    enum ldma_chan_on_off onoff;
    dma_addr_t desc_phys;
    void * desc_base;
    u32 desc_cnt;
    int rst;
    u32 hdrm_len;
    bool hdrm_csum;
    u32 boff_len;
    u32 data_endian;
    u32 desc_endian;
    bool pden;
    bool desc_rx_np;
    bool data_endian_en;
    bool desc_endian_en;
    bool abc_en;
    bool desc_init;
    struct dma_pool * desc_pool;
    u32 desc_num;
    struct dw2_desc_sw * ds;
    struct work_struct work;
    struct dma_slave_config config;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ldma_chan {
    struct virt_dma_chan vchan;
    struct ldma_port * port;
    char[8] name;
    int nr;
    u32 flags;
    enum ldma_chan_on_off onoff;
    dma_addr_t desc_phys;
    void * desc_base;
    u32 desc_cnt;
    int rst;
    u32 hdrm_len;
    bool hdrm_csum;
    u32 boff_len;
    u32 data_endian;
    u32 desc_endian;
    bool pden;
    bool desc_rx_np;
    bool data_endian_en;
    bool desc_endian_en;
    bool abc_en;
    bool desc_init;
    struct dma_pool * desc_pool;
    u32 desc_num;
    struct dw2_desc_sw * ds;
    struct work_struct work;
    struct dma_slave_config config;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ldma_chan {
    struct virt_dma_chan vchan;
    struct ldma_port * port;
    char[8] name;
    int nr;
    u32 flags;
    enum ldma_chan_on_off onoff;
    dma_addr_t desc_phys;
    void * desc_base;
    u32 desc_cnt;
    int rst;
    u32 hdrm_len;
    bool hdrm_csum;
    u32 boff_len;
    u32 data_endian;
    u32 desc_endian;
    bool pden;
    bool desc_rx_np;
    bool data_endian_en;
    bool desc_endian_en;
    bool abc_en;
    bool desc_init;
    struct dma_pool * desc_pool;
    u32 desc_num;
    struct dw2_desc_sw * ds;
    struct work_struct work;
    struct dma_slave_config config;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ldma_chan {
    struct virt_dma_chan vchan;
    struct ldma_port * port;
    char[8] name;
    int nr;
    u32 flags;
    enum ldma_chan_on_off onoff;
    dma_addr_t desc_phys;
    void * desc_base;
    u32 desc_cnt;
    int rst;
    u32 hdrm_len;
    bool hdrm_csum;
    u32 boff_len;
    u32 data_endian;
    u32 desc_endian;
    bool pden;
    bool desc_rx_np;
    bool data_endian_en;
    bool desc_endian_en;
    bool abc_en;
    bool desc_init;
    struct dma_pool * desc_pool;
    u32 desc_num;
    struct dw2_desc_sw * ds;
    struct work_struct work;
    struct dma_slave_config config;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ldma_chan {
    struct virt_dma_chan vchan;
    struct ldma_port * port;
    char[8] name;
    int nr;
    u32 flags;
    enum ldma_chan_on_off onoff;
    dma_addr_t desc_phys;
    void * desc_base;
    u32 desc_cnt;
    int rst;
    u32 hdrm_len;
    bool hdrm_csum;
    u32 boff_len;
    u32 data_endian;
    u32 desc_endian;
    bool pden;
    bool desc_rx_np;
    bool data_endian_en;
    bool desc_endian_en;
    bool abc_en;
    bool desc_init;
    struct dma_pool * desc_pool;
    u32 desc_num;
    struct dw2_desc_sw * ds;
    struct work_struct work;
    struct dma_slave_config config;
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct ldma_chan {
    struct virt_dma_chan vchan;
    struct ldma_port * port;
    char[8] name;
    int nr;
    u32 flags;
    enum ldma_chan_on_off onoff;
    dma_addr_t desc_phys;
    void * desc_base;
    u32 desc_cnt;
    int rst;
    u32 hdrm_len;
    bool hdrm_csum;
    u32 boff_len;
    u32 data_endian;
    u32 desc_endian;
    bool pden;
    bool desc_rx_np;
    bool data_endian_en;
    bool desc_endian_en;
    bool abc_en;
    bool desc_init;
    struct dma_pool * desc_pool;
    u32 desc_num;
    struct dw2_desc_sw * ds;
    struct work_struct work;
    struct dma_slave_config config;
}
```
</details>
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
