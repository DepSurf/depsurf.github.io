# Struct: <code>cpg_mssr_info</code>

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
struct cpg_mssr_info {
    const struct cpg_core_clk * early_core_clks;
    unsigned int num_early_core_clks;
    const struct mssr_mod_clk * early_mod_clks;
    unsigned int num_early_mod_clks;
    const struct cpg_core_clk * core_clks;
    unsigned int num_core_clks;
    unsigned int last_dt_core_clk;
    unsigned int num_total_core_clks;
    bool stbyctrl;
    const struct mssr_mod_clk * mod_clks;
    unsigned int num_mod_clks;
    unsigned int num_hw_mod_clks;
    const unsigned int * crit_mod_clks;
    unsigned int num_crit_mod_clks;
    const unsigned int * core_pm_clks;
    unsigned int num_core_pm_clks;
    int (*)(struct device *) init;
    struct clk * (*)(struct device *, const struct cpg_core_clk *, const struct cpg_mssr_info *, struct clk * *, void *, struct raw_notifier_head *) cpg_clk_register;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cpg_mssr_info {
    const struct cpg_core_clk * early_core_clks;
    unsigned int num_early_core_clks;
    const struct mssr_mod_clk * early_mod_clks;
    unsigned int num_early_mod_clks;
    const struct cpg_core_clk * core_clks;
    unsigned int num_core_clks;
    unsigned int last_dt_core_clk;
    unsigned int num_total_core_clks;
    bool stbyctrl;
    const struct mssr_mod_clk * mod_clks;
    unsigned int num_mod_clks;
    unsigned int num_hw_mod_clks;
    const unsigned int * crit_mod_clks;
    unsigned int num_crit_mod_clks;
    const unsigned int * core_pm_clks;
    unsigned int num_core_pm_clks;
    int (*)(struct device *) init;
    struct clk * (*)(struct device *, const struct cpg_core_clk *, const struct cpg_mssr_info *, struct clk * *, void *, struct raw_notifier_head *) cpg_clk_register;
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
struct cpg_mssr_info {
    const struct cpg_core_clk * early_core_clks;
    unsigned int num_early_core_clks;
    const struct mssr_mod_clk * early_mod_clks;
    unsigned int num_early_mod_clks;
    const struct cpg_core_clk * core_clks;
    unsigned int num_core_clks;
    unsigned int last_dt_core_clk;
    unsigned int num_total_core_clks;
    bool stbyctrl;
    const struct mssr_mod_clk * mod_clks;
    unsigned int num_mod_clks;
    unsigned int num_hw_mod_clks;
    const unsigned int * crit_mod_clks;
    unsigned int num_crit_mod_clks;
    const unsigned int * core_pm_clks;
    unsigned int num_core_pm_clks;
    int (*)(struct device *) init;
    struct clk * (*)(struct device *, const struct cpg_core_clk *, const struct cpg_mssr_info *, struct clk * *, void *, struct raw_notifier_head *) cpg_clk_register;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct cpg_mssr_info {
    const struct cpg_core_clk * early_core_clks;
    unsigned int num_early_core_clks;
    const struct mssr_mod_clk * early_mod_clks;
    unsigned int num_early_mod_clks;
    const struct cpg_core_clk * core_clks;
    unsigned int num_core_clks;
    unsigned int last_dt_core_clk;
    unsigned int num_total_core_clks;
    bool stbyctrl;
    const struct mssr_mod_clk * mod_clks;
    unsigned int num_mod_clks;
    unsigned int num_hw_mod_clks;
    const unsigned int * crit_mod_clks;
    unsigned int num_crit_mod_clks;
    const unsigned int * core_pm_clks;
    unsigned int num_core_pm_clks;
    int (*)(struct device *) init;
    struct clk * (*)(struct device *, const struct cpg_core_clk *, const struct cpg_mssr_info *, struct clk * *, void *, struct raw_notifier_head *) cpg_clk_register;
}
```
</details>
</li>
</ul>
