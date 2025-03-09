# Struct: <code>clkdm_ops</code>

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
struct clkdm_ops {
    int (*)(struct clockdomain *, struct clockdomain *) clkdm_add_wkdep;
    int (*)(struct clockdomain *, struct clockdomain *) clkdm_del_wkdep;
    int (*)(struct clockdomain *, struct clockdomain *) clkdm_read_wkdep;
    int (*)(struct clockdomain *) clkdm_clear_all_wkdeps;
    int (*)(struct clockdomain *, struct clockdomain *) clkdm_add_sleepdep;
    int (*)(struct clockdomain *, struct clockdomain *) clkdm_del_sleepdep;
    int (*)(struct clockdomain *, struct clockdomain *) clkdm_read_sleepdep;
    int (*)(struct clockdomain *) clkdm_clear_all_sleepdeps;
    int (*)(struct clockdomain *) clkdm_sleep;
    int (*)(struct clockdomain *) clkdm_wakeup;
    void (*)(struct clockdomain *) clkdm_allow_idle;
    void (*)(struct clockdomain *) clkdm_deny_idle;
    int (*)(struct clockdomain *) clkdm_clk_enable;
    int (*)(struct clockdomain *) clkdm_clk_disable;
    int (*)(struct clockdomain *) clkdm_save_context;
    int (*)(struct clockdomain *) clkdm_restore_context;
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
struct clkdm_ops {
    int (*)(struct clockdomain *, struct clockdomain *) clkdm_add_wkdep;
    int (*)(struct clockdomain *, struct clockdomain *) clkdm_del_wkdep;
    int (*)(struct clockdomain *, struct clockdomain *) clkdm_read_wkdep;
    int (*)(struct clockdomain *) clkdm_clear_all_wkdeps;
    int (*)(struct clockdomain *, struct clockdomain *) clkdm_add_sleepdep;
    int (*)(struct clockdomain *, struct clockdomain *) clkdm_del_sleepdep;
    int (*)(struct clockdomain *, struct clockdomain *) clkdm_read_sleepdep;
    int (*)(struct clockdomain *) clkdm_clear_all_sleepdeps;
    int (*)(struct clockdomain *) clkdm_sleep;
    int (*)(struct clockdomain *) clkdm_wakeup;
    void (*)(struct clockdomain *) clkdm_allow_idle;
    void (*)(struct clockdomain *) clkdm_deny_idle;
    int (*)(struct clockdomain *) clkdm_clk_enable;
    int (*)(struct clockdomain *) clkdm_clk_disable;
    int (*)(struct clockdomain *) clkdm_save_context;
    int (*)(struct clockdomain *) clkdm_restore_context;
}
```
</details>
</li>
</ul>
