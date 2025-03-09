# Struct: <code>qcom_pcie_resources_2_4_0</code>

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
struct qcom_pcie_resources_2_4_0 {
    struct clk_bulk_data[4] clks;
    int num_clks;
    struct reset_control * axi_m_reset;
    struct reset_control * axi_s_reset;
    struct reset_control * pipe_reset;
    struct reset_control * axi_m_vmid_reset;
    struct reset_control * axi_s_xpu_reset;
    struct reset_control * parf_reset;
    struct reset_control * phy_reset;
    struct reset_control * axi_m_sticky_reset;
    struct reset_control * pipe_sticky_reset;
    struct reset_control * pwr_reset;
    struct reset_control * ahb_reset;
    struct reset_control * phy_ahb_reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct qcom_pcie_resources_2_4_0 {
    struct clk_bulk_data[4] clks;
    int num_clks;
    struct reset_control * axi_m_reset;
    struct reset_control * axi_s_reset;
    struct reset_control * pipe_reset;
    struct reset_control * axi_m_vmid_reset;
    struct reset_control * axi_s_xpu_reset;
    struct reset_control * parf_reset;
    struct reset_control * phy_reset;
    struct reset_control * axi_m_sticky_reset;
    struct reset_control * pipe_sticky_reset;
    struct reset_control * pwr_reset;
    struct reset_control * ahb_reset;
    struct reset_control * phy_ahb_reset;
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
struct qcom_pcie_resources_2_4_0 {
    struct clk_bulk_data[4] clks;
    int num_clks;
    struct reset_control * axi_m_reset;
    struct reset_control * axi_s_reset;
    struct reset_control * pipe_reset;
    struct reset_control * axi_m_vmid_reset;
    struct reset_control * axi_s_xpu_reset;
    struct reset_control * parf_reset;
    struct reset_control * phy_reset;
    struct reset_control * axi_m_sticky_reset;
    struct reset_control * pipe_sticky_reset;
    struct reset_control * pwr_reset;
    struct reset_control * ahb_reset;
    struct reset_control * phy_ahb_reset;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct qcom_pcie_resources_2_4_0 {
    struct clk_bulk_data[4] clks;
    int num_clks;
    struct reset_control * axi_m_reset;
    struct reset_control * axi_s_reset;
    struct reset_control * pipe_reset;
    struct reset_control * axi_m_vmid_reset;
    struct reset_control * axi_s_xpu_reset;
    struct reset_control * parf_reset;
    struct reset_control * phy_reset;
    struct reset_control * axi_m_sticky_reset;
    struct reset_control * pipe_sticky_reset;
    struct reset_control * pwr_reset;
    struct reset_control * ahb_reset;
    struct reset_control * phy_ahb_reset;
}
```
</details>
</li>
</ul>
