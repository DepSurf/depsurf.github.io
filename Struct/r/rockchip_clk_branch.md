# Struct: <code>rockchip_clk_branch</code>

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
struct rockchip_clk_branch {
    unsigned int id;
    enum rockchip_clk_branch_type branch_type;
    const char * name;
    const const char * * parent_names;
    u8 num_parents;
    long unsigned int flags;
    int muxdiv_offset;
    u8 mux_shift;
    u8 mux_width;
    u8 mux_flags;
    int div_offset;
    u8 div_shift;
    u8 div_width;
    u8 div_flags;
    struct clk_div_table * div_table;
    int gate_offset;
    u8 gate_shift;
    u8 gate_flags;
    struct rockchip_clk_branch * child;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rockchip_clk_branch {
    unsigned int id;
    enum rockchip_clk_branch_type branch_type;
    const char * name;
    const const char * * parent_names;
    u8 num_parents;
    long unsigned int flags;
    int muxdiv_offset;
    u8 mux_shift;
    u8 mux_width;
    u8 mux_flags;
    int div_offset;
    u8 div_shift;
    u8 div_width;
    u8 div_flags;
    struct clk_div_table * div_table;
    int gate_offset;
    u8 gate_shift;
    u8 gate_flags;
    struct rockchip_clk_branch * child;
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
struct rockchip_clk_branch {
    unsigned int id;
    enum rockchip_clk_branch_type branch_type;
    const char * name;
    const const char * * parent_names;
    u8 num_parents;
    long unsigned int flags;
    int muxdiv_offset;
    u8 mux_shift;
    u8 mux_width;
    u8 mux_flags;
    int div_offset;
    u8 div_shift;
    u8 div_width;
    u8 div_flags;
    struct clk_div_table * div_table;
    int gate_offset;
    u8 gate_shift;
    u8 gate_flags;
    struct rockchip_clk_branch * child;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct rockchip_clk_branch {
    unsigned int id;
    enum rockchip_clk_branch_type branch_type;
    const char * name;
    const const char * * parent_names;
    u8 num_parents;
    long unsigned int flags;
    int muxdiv_offset;
    u8 mux_shift;
    u8 mux_width;
    u8 mux_flags;
    int div_offset;
    u8 div_shift;
    u8 div_width;
    u8 div_flags;
    struct clk_div_table * div_table;
    int gate_offset;
    u8 gate_shift;
    u8 gate_flags;
    struct rockchip_clk_branch * child;
}
```
</details>
</li>
</ul>
