# Struct: <code>xhci_hcd_mtk</code>

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
struct xhci_hcd_mtk {
    struct device * dev;
    struct usb_hcd * hcd;
    struct mu3h_sch_bw_info * sch_array;
    struct mu3c_ippc_regs * ippc_regs;
    bool has_ippc;
    int num_u2_ports;
    int num_u3_ports;
    int u3p_dis_msk;
    struct regulator * vusb33;
    struct regulator * vbus;
    struct clk * sys_clk;
    struct clk * xhci_clk;
    struct clk * ref_clk;
    struct clk * mcu_clk;
    struct clk * dma_clk;
    struct regmap * pericfg;
    struct phy * * phys;
    int num_phys;
    bool lpm_support;
    bool uwk_en;
    struct regmap * uwk;
    u32 uwk_reg_base;
    u32 uwk_vers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xhci_hcd_mtk {
    struct device * dev;
    struct usb_hcd * hcd;
    struct mu3h_sch_bw_info * sch_array;
    struct mu3c_ippc_regs * ippc_regs;
    bool has_ippc;
    int num_u2_ports;
    int num_u3_ports;
    int u3p_dis_msk;
    struct regulator * vusb33;
    struct regulator * vbus;
    struct clk * sys_clk;
    struct clk * xhci_clk;
    struct clk * ref_clk;
    struct clk * mcu_clk;
    struct clk * dma_clk;
    struct regmap * pericfg;
    struct phy * * phys;
    int num_phys;
    bool lpm_support;
    bool uwk_en;
    struct regmap * uwk;
    u32 uwk_reg_base;
    u32 uwk_vers;
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
struct xhci_hcd_mtk {
    struct device * dev;
    struct usb_hcd * hcd;
    struct mu3h_sch_bw_info * sch_array;
    struct mu3c_ippc_regs * ippc_regs;
    bool has_ippc;
    int num_u2_ports;
    int num_u3_ports;
    int u3p_dis_msk;
    struct regulator * vusb33;
    struct regulator * vbus;
    struct clk * sys_clk;
    struct clk * xhci_clk;
    struct clk * ref_clk;
    struct clk * mcu_clk;
    struct clk * dma_clk;
    struct regmap * pericfg;
    struct phy * * phys;
    int num_phys;
    bool lpm_support;
    bool uwk_en;
    struct regmap * uwk;
    u32 uwk_reg_base;
    u32 uwk_vers;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct xhci_hcd_mtk {
    struct device * dev;
    struct usb_hcd * hcd;
    struct mu3h_sch_bw_info * sch_array;
    struct mu3c_ippc_regs * ippc_regs;
    bool has_ippc;
    int num_u2_ports;
    int num_u3_ports;
    int u3p_dis_msk;
    struct regulator * vusb33;
    struct regulator * vbus;
    struct clk * sys_clk;
    struct clk * xhci_clk;
    struct clk * ref_clk;
    struct clk * mcu_clk;
    struct clk * dma_clk;
    struct regmap * pericfg;
    struct phy * * phys;
    int num_phys;
    bool lpm_support;
    bool uwk_en;
    struct regmap * uwk;
    u32 uwk_reg_base;
    u32 uwk_vers;
}
```
</details>
</li>
</ul>
