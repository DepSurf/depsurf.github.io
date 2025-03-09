# Struct: <code>rockchip_pcie</code>

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
struct rockchip_pcie {
    void * reg_base;
    void * apb_base;
    bool legacy_phy;
    struct phy *[4] phys;
    struct reset_control * core_rst;
    struct reset_control * mgmt_rst;
    struct reset_control * mgmt_sticky_rst;
    struct reset_control * pipe_rst;
    struct reset_control * pm_rst;
    struct reset_control * aclk_rst;
    struct reset_control * pclk_rst;
    struct clk * aclk_pcie;
    struct clk * aclk_perf_pcie;
    struct clk * hclk_pcie;
    struct clk * clk_pcie_pm;
    struct regulator * vpcie12v;
    struct regulator * vpcie3v3;
    struct regulator * vpcie1v8;
    struct regulator * vpcie0v9;
    struct gpio_desc * ep_gpio;
    u32 lanes;
    u8 lanes_map;
    u8 root_bus_nr;
    int link_gen;
    struct device * dev;
    struct irq_domain * irq_domain;
    int offset;
    struct pci_bus * root_bus;
    struct resource * io;
    phys_addr_t io_bus_addr;
    u32 io_size;
    void * msg_region;
    u32 mem_size;
    phys_addr_t msg_bus_addr;
    phys_addr_t mem_bus_addr;
    bool is_rc;
    struct resource * mem_res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rockchip_pcie {
    void * reg_base;
    void * apb_base;
    bool legacy_phy;
    struct phy *[4] phys;
    struct reset_control * core_rst;
    struct reset_control * mgmt_rst;
    struct reset_control * mgmt_sticky_rst;
    struct reset_control * pipe_rst;
    struct reset_control * pm_rst;
    struct reset_control * aclk_rst;
    struct reset_control * pclk_rst;
    struct clk * aclk_pcie;
    struct clk * aclk_perf_pcie;
    struct clk * hclk_pcie;
    struct clk * clk_pcie_pm;
    struct regulator * vpcie12v;
    struct regulator * vpcie3v3;
    struct regulator * vpcie1v8;
    struct regulator * vpcie0v9;
    struct gpio_desc * ep_gpio;
    u32 lanes;
    u8 lanes_map;
    u8 root_bus_nr;
    int link_gen;
    struct device * dev;
    struct irq_domain * irq_domain;
    int offset;
    struct pci_bus * root_bus;
    struct resource * io;
    phys_addr_t io_bus_addr;
    u32 io_size;
    void * msg_region;
    u32 mem_size;
    phys_addr_t msg_bus_addr;
    phys_addr_t mem_bus_addr;
    bool is_rc;
    struct resource * mem_res;
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
struct rockchip_pcie {
    void * reg_base;
    void * apb_base;
    bool legacy_phy;
    struct phy *[4] phys;
    struct reset_control * core_rst;
    struct reset_control * mgmt_rst;
    struct reset_control * mgmt_sticky_rst;
    struct reset_control * pipe_rst;
    struct reset_control * pm_rst;
    struct reset_control * aclk_rst;
    struct reset_control * pclk_rst;
    struct clk * aclk_pcie;
    struct clk * aclk_perf_pcie;
    struct clk * hclk_pcie;
    struct clk * clk_pcie_pm;
    struct regulator * vpcie12v;
    struct regulator * vpcie3v3;
    struct regulator * vpcie1v8;
    struct regulator * vpcie0v9;
    struct gpio_desc * ep_gpio;
    u32 lanes;
    u8 lanes_map;
    u8 root_bus_nr;
    int link_gen;
    struct device * dev;
    struct irq_domain * irq_domain;
    int offset;
    struct pci_bus * root_bus;
    struct resource * io;
    phys_addr_t io_bus_addr;
    u32 io_size;
    void * msg_region;
    u32 mem_size;
    phys_addr_t msg_bus_addr;
    phys_addr_t mem_bus_addr;
    bool is_rc;
    struct resource * mem_res;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct rockchip_pcie {
    void * reg_base;
    void * apb_base;
    bool legacy_phy;
    struct phy *[4] phys;
    struct reset_control * core_rst;
    struct reset_control * mgmt_rst;
    struct reset_control * mgmt_sticky_rst;
    struct reset_control * pipe_rst;
    struct reset_control * pm_rst;
    struct reset_control * aclk_rst;
    struct reset_control * pclk_rst;
    struct clk * aclk_pcie;
    struct clk * aclk_perf_pcie;
    struct clk * hclk_pcie;
    struct clk * clk_pcie_pm;
    struct regulator * vpcie12v;
    struct regulator * vpcie3v3;
    struct regulator * vpcie1v8;
    struct regulator * vpcie0v9;
    struct gpio_desc * ep_gpio;
    u32 lanes;
    u8 lanes_map;
    u8 root_bus_nr;
    int link_gen;
    struct device * dev;
    struct irq_domain * irq_domain;
    int offset;
    struct pci_bus * root_bus;
    struct resource * io;
    phys_addr_t io_bus_addr;
    u32 io_size;
    void * msg_region;
    u32 mem_size;
    phys_addr_t msg_bus_addr;
    phys_addr_t mem_bus_addr;
    bool is_rc;
    struct resource * mem_res;
}
```
</details>
</li>
</ul>
