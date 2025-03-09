# Struct: <code>pwrdm_ops</code>

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
struct pwrdm_ops {
    int (*)(struct powerdomain *, u8) pwrdm_set_next_pwrst;
    int (*)(struct powerdomain *) pwrdm_read_next_pwrst;
    int (*)(struct powerdomain *) pwrdm_read_pwrst;
    int (*)(struct powerdomain *) pwrdm_read_prev_pwrst;
    int (*)(struct powerdomain *, u8) pwrdm_set_logic_retst;
    int (*)(struct powerdomain *, u8, u8) pwrdm_set_mem_onst;
    int (*)(struct powerdomain *, u8, u8) pwrdm_set_mem_retst;
    int (*)(struct powerdomain *) pwrdm_read_logic_pwrst;
    int (*)(struct powerdomain *) pwrdm_read_prev_logic_pwrst;
    int (*)(struct powerdomain *) pwrdm_read_logic_retst;
    int (*)(struct powerdomain *, u8) pwrdm_read_mem_pwrst;
    int (*)(struct powerdomain *, u8) pwrdm_read_prev_mem_pwrst;
    int (*)(struct powerdomain *, u8) pwrdm_read_mem_retst;
    int (*)(struct powerdomain *) pwrdm_clear_all_prev_pwrst;
    int (*)(struct powerdomain *) pwrdm_enable_hdwr_sar;
    int (*)(struct powerdomain *) pwrdm_disable_hdwr_sar;
    int (*)(struct powerdomain *) pwrdm_set_lowpwrstchange;
    int (*)(struct powerdomain *) pwrdm_wait_transition;
    int (*)() pwrdm_has_voltdm;
    void (*)(struct powerdomain *) pwrdm_save_context;
    void (*)(struct powerdomain *) pwrdm_restore_context;
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
struct pwrdm_ops {
    int (*)(struct powerdomain *, u8) pwrdm_set_next_pwrst;
    int (*)(struct powerdomain *) pwrdm_read_next_pwrst;
    int (*)(struct powerdomain *) pwrdm_read_pwrst;
    int (*)(struct powerdomain *) pwrdm_read_prev_pwrst;
    int (*)(struct powerdomain *, u8) pwrdm_set_logic_retst;
    int (*)(struct powerdomain *, u8, u8) pwrdm_set_mem_onst;
    int (*)(struct powerdomain *, u8, u8) pwrdm_set_mem_retst;
    int (*)(struct powerdomain *) pwrdm_read_logic_pwrst;
    int (*)(struct powerdomain *) pwrdm_read_prev_logic_pwrst;
    int (*)(struct powerdomain *) pwrdm_read_logic_retst;
    int (*)(struct powerdomain *, u8) pwrdm_read_mem_pwrst;
    int (*)(struct powerdomain *, u8) pwrdm_read_prev_mem_pwrst;
    int (*)(struct powerdomain *, u8) pwrdm_read_mem_retst;
    int (*)(struct powerdomain *) pwrdm_clear_all_prev_pwrst;
    int (*)(struct powerdomain *) pwrdm_enable_hdwr_sar;
    int (*)(struct powerdomain *) pwrdm_disable_hdwr_sar;
    int (*)(struct powerdomain *) pwrdm_set_lowpwrstchange;
    int (*)(struct powerdomain *) pwrdm_wait_transition;
    int (*)() pwrdm_has_voltdm;
    void (*)(struct powerdomain *) pwrdm_save_context;
    void (*)(struct powerdomain *) pwrdm_restore_context;
}
```
</details>
</li>
</ul>
