# Struct: <code>rockchip_clk_pll</code>

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
struct rockchip_clk_pll {
    struct clk_hw hw;
    struct clk_mux pll_mux;
    const struct clk_ops * pll_mux_ops;
    struct notifier_block clk_nb;
    void * reg_base;
    int lock_offset;
    unsigned int lock_shift;
    enum rockchip_pll_type type;
    u8 flags;
    const struct rockchip_pll_rate_table * rate_table;
    unsigned int rate_count;
    spinlock_t * lock;
    struct rockchip_clk_provider * ctx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rockchip_clk_pll {
    struct clk_hw hw;
    struct clk_mux pll_mux;
    const struct clk_ops * pll_mux_ops;
    struct notifier_block clk_nb;
    void * reg_base;
    int lock_offset;
    unsigned int lock_shift;
    enum rockchip_pll_type type;
    u8 flags;
    const struct rockchip_pll_rate_table * rate_table;
    unsigned int rate_count;
    spinlock_t * lock;
    struct rockchip_clk_provider * ctx;
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
struct rockchip_clk_pll {
    struct clk_hw hw;
    struct clk_mux pll_mux;
    const struct clk_ops * pll_mux_ops;
    struct notifier_block clk_nb;
    void * reg_base;
    int lock_offset;
    unsigned int lock_shift;
    enum rockchip_pll_type type;
    u8 flags;
    const struct rockchip_pll_rate_table * rate_table;
    unsigned int rate_count;
    spinlock_t * lock;
    struct rockchip_clk_provider * ctx;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct rockchip_clk_pll {
    struct clk_hw hw;
    struct clk_mux pll_mux;
    const struct clk_ops * pll_mux_ops;
    struct notifier_block clk_nb;
    void * reg_base;
    int lock_offset;
    unsigned int lock_shift;
    enum rockchip_pll_type type;
    u8 flags;
    const struct rockchip_pll_rate_table * rate_table;
    unsigned int rate_count;
    spinlock_t * lock;
    struct rockchip_clk_provider * ctx;
}
```
</details>
</li>
</ul>
