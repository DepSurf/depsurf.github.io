# Struct: <code>ti_sysc_platform_data</code>

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
struct ti_sysc_platform_data {
    struct of_dev_auxdata * auxdata;
    int (*)(struct device *, struct clk *, struct clk *, struct ti_sysc_cookie *) init_clockdomain;
    void (*)(struct device *, const struct ti_sysc_cookie *) clkdm_deny_idle;
    void (*)(struct device *, const struct ti_sysc_cookie *) clkdm_allow_idle;
    int (*)(struct device *, const struct ti_sysc_module_data *, struct ti_sysc_cookie *) init_module;
    int (*)(struct device *, const struct ti_sysc_cookie *) enable_module;
    int (*)(struct device *, const struct ti_sysc_cookie *) idle_module;
    int (*)(struct device *, const struct ti_sysc_cookie *) shutdown_module;
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
struct ti_sysc_platform_data {
    struct of_dev_auxdata * auxdata;
    int (*)(struct device *, struct clk *, struct clk *, struct ti_sysc_cookie *) init_clockdomain;
    void (*)(struct device *, const struct ti_sysc_cookie *) clkdm_deny_idle;
    void (*)(struct device *, const struct ti_sysc_cookie *) clkdm_allow_idle;
    int (*)(struct device *, const struct ti_sysc_module_data *, struct ti_sysc_cookie *) init_module;
    int (*)(struct device *, const struct ti_sysc_cookie *) enable_module;
    int (*)(struct device *, const struct ti_sysc_cookie *) idle_module;
    int (*)(struct device *, const struct ti_sysc_cookie *) shutdown_module;
}
```
</details>
</li>
</ul>
