# Struct: <code>dw_pcie</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    u32 num_viewport;
    u8 iatu_unroll_enabled;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    u32 num_viewport;
    u8 iatu_unroll_enabled;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    u32 num_viewport;
    u8 iatu_unroll_enabled;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    u32 num_viewport;
    u8 iatu_unroll_enabled;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    u32 num_viewport;
    u8 iatu_unroll_enabled;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    unsigned int version;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    u32 num_viewport;
    u8 iatu_unroll_enabled;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    unsigned int version;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    u32 num_viewport;
    u8 iatu_unroll_enabled;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    unsigned int version;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    size_t atu_size;
    u32 num_ib_windows;
    u32 num_ob_windows;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    unsigned int version;
    int num_lanes;
    int link_gen;
    u8[2] n_fts;
    bool iatu_unroll_enabled;
    bool io_cfg_atu_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    size_t atu_size;
    u32 num_ib_windows;
    u32 num_ob_windows;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    unsigned int version;
    int num_lanes;
    int link_gen;
    u8[2] n_fts;
    bool iatu_unroll_enabled;
    bool io_cfg_atu_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    size_t atu_size;
    u32 num_ib_windows;
    u32 num_ob_windows;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    unsigned int version;
    int num_lanes;
    int link_gen;
    u8[2] n_fts;
    bool iatu_unroll_enabled;
    bool io_cfg_atu_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    size_t atu_size;
    u32 num_ib_windows;
    u32 num_ob_windows;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    unsigned int version;
    int num_lanes;
    int link_gen;
    u8[2] n_fts;
    bool iatu_unroll_enabled;
    bool io_cfg_atu_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    size_t atu_size;
    u32 num_ib_windows;
    u32 num_ob_windows;
    u32 region_align;
    u64 region_limit;
    struct dw_pcie_rp pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    u32 version;
    u32 type;
    long unsigned int caps;
    int num_lanes;
    int link_gen;
    u8[2] n_fts;
    struct clk_bulk_data[3] app_clks;
    struct clk_bulk_data[4] core_clks;
    struct reset_control_bulk_data[3] app_rsts;
    struct reset_control_bulk_data[7] core_rsts;
    struct gpio_desc * pe_rst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    size_t atu_size;
    u32 num_ib_windows;
    u32 num_ob_windows;
    u32 region_align;
    u64 region_limit;
    struct dw_pcie_rp pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    u32 version;
    u32 type;
    long unsigned int caps;
    int num_lanes;
    int link_gen;
    u8[2] n_fts;
    struct dw_edma_chip edma;
    struct clk_bulk_data[3] app_clks;
    struct clk_bulk_data[4] core_clks;
    struct reset_control_bulk_data[3] app_rsts;
    struct reset_control_bulk_data[7] core_rsts;
    struct gpio_desc * pe_rst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    size_t atu_size;
    u32 num_ib_windows;
    u32 num_ob_windows;
    u32 region_align;
    u64 region_limit;
    struct dw_pcie_rp pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    u32 version;
    u32 type;
    long unsigned int caps;
    int num_lanes;
    int link_gen;
    u8[2] n_fts;
    struct dw_edma_chip edma;
    struct clk_bulk_data[3] app_clks;
    struct clk_bulk_data[4] core_clks;
    struct reset_control_bulk_data[3] app_rsts;
    struct reset_control_bulk_data[7] core_rsts;
    struct gpio_desc * pe_rst;
    bool suspended;
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
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    u32 num_viewport;
    u8 iatu_unroll_enabled;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    unsigned int version;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    u32 num_viewport;
    u8 iatu_unroll_enabled;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    unsigned int version;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    u32 num_viewport;
    u8 iatu_unroll_enabled;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    unsigned int version;
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
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    u32 num_viewport;
    u8 iatu_unroll_enabled;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    unsigned int version;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    u32 num_viewport;
    u8 iatu_unroll_enabled;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    unsigned int version;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    u32 num_viewport;
    u8 iatu_unroll_enabled;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    unsigned int version;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    u32 num_viewport;
    u8 iatu_unroll_enabled;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    unsigned int version;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    u32 num_viewport;
    u8 iatu_unroll_enabled;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
}
```
</details>
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
<code>void * atu_base</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int version</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>size_t atu_size</code>
</li>
<li>
<b>Field added. </b>
<code>u32 num_ib_windows</code>
</li>
<li>
<b>Field added. </b>
<code>u32 num_ob_windows</code>
</li>
<li>
<b>Field added. </b>
<code>int num_lanes</code>
</li>
<li>
<b>Field added. </b>
<code>int link_gen</code>
</li>
<li>
<b>Field added. </b>
<code>u8[2] n_fts</code>
</li>
<li>
<b>Field added. </b>
<code>bool io_cfg_atu_shared</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 num_viewport</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8 iatu_unroll_enabled</code> ➡️ <code>bool iatu_unroll_enabled</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 region_align</code>
</li>
<li>
<b>Field added. </b>
<code>u64 region_limit</code>
</li>
<li>
<b>Field added. </b>
<code>u32 type</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int caps</code>
</li>
<li>
<b>Field added. </b>
<code>struct clk_bulk_data[3] app_clks</code>
</li>
<li>
<b>Field added. </b>
<code>struct clk_bulk_data[4] core_clks</code>
</li>
<li>
<b>Field added. </b>
<code>struct reset_control_bulk_data[3] app_rsts</code>
</li>
<li>
<b>Field added. </b>
<code>struct reset_control_bulk_data[7] core_rsts</code>
</li>
<li>
<b>Field added. </b>
<code>struct gpio_desc * pe_rst</code>
</li>
<li>
<b>Field removed. </b>
<code>bool iatu_unroll_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>bool io_cfg_atu_shared</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct pcie_port pp</code> ➡️ <code>struct dw_pcie_rp pp</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int version</code> ➡️ <code>u32 version</code>
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
<code>struct dw_edma_chip edma</code>
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
<code>bool suspended</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct dw_pcie {
    struct device * dev;
    void * dbi_base;
    void * dbi_base2;
    void * atu_base;
    u32 num_viewport;
    u8 iatu_unroll_enabled;
    struct pcie_port pp;
    struct dw_pcie_ep ep;
    const struct dw_pcie_ops * ops;
    unsigned int version;
}
```
</details>
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
