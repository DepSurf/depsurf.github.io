# Struct: <code>tegra_pcie</code>

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
struct tegra_pcie {
    struct device * dev;
    void * pads;
    void * afi;
    void * cfg;
    int irq;
    struct resource cs;
    struct resource io;
    struct resource pio;
    struct resource mem;
    struct resource prefetch;
    struct resource busn;
    struct (anon) offset;
    struct clk * pex_clk;
    struct clk * afi_clk;
    struct clk * pll_e;
    struct clk * cml_clk;
    struct reset_control * pex_rst;
    struct reset_control * afi_rst;
    struct reset_control * pcie_xrst;
    bool legacy_phy;
    struct phy * phy;
    struct tegra_msi msi;
    struct list_head ports;
    u32 xbar_config;
    struct regulator_bulk_data * supplies;
    unsigned int num_supplies;
    const struct tegra_pcie_soc * soc;
    struct dentry * debugfs;
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
struct tegra_pcie {
    struct device * dev;
    void * pads;
    void * afi;
    void * cfg;
    int irq;
    struct resource cs;
    struct resource io;
    struct resource pio;
    struct resource mem;
    struct resource prefetch;
    struct resource busn;
    struct (anon) offset;
    struct clk * pex_clk;
    struct clk * afi_clk;
    struct clk * pll_e;
    struct clk * cml_clk;
    struct reset_control * pex_rst;
    struct reset_control * afi_rst;
    struct reset_control * pcie_xrst;
    bool legacy_phy;
    struct phy * phy;
    struct tegra_msi msi;
    struct list_head ports;
    u32 xbar_config;
    struct regulator_bulk_data * supplies;
    unsigned int num_supplies;
    const struct tegra_pcie_soc * soc;
    struct dentry * debugfs;
}
```
</details>
</li>
</ul>
