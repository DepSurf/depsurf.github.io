# Struct: <code>powerdomain</code>

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
struct powerdomain {
    const char * name;
    union (anon) voltdm;
    const s16 prcm_offs;
    const u8 pwrsts;
    const u8 pwrsts_logic_ret;
    const u8 flags;
    const u8 banks;
    const const u8[5] pwrsts_mem_ret;
    const const u8[5] pwrsts_mem_on;
    const u8 prcm_partition;
    struct clockdomain *[11] pwrdm_clkdms;
    struct list_head node;
    struct list_head voltdm_node;
    int state;
    unsigned int[4] state_counter;
    unsigned int ret_logic_off_counter;
    unsigned int[5] ret_mem_off_counter;
    spinlock_t _lock;
    long unsigned int _lock_flags;
    const u8 pwrstctrl_offs;
    const u8 pwrstst_offs;
    const u32 logicretstate_mask;
    const const u32[5] mem_on_mask;
    const const u32[5] mem_ret_mask;
    const const u32[5] mem_pwrst_mask;
    const const u32[5] mem_retst_mask;
    s64 timer;
    s64[4] state_timer;
    u32 context;
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
struct powerdomain {
    const char * name;
    union (anon) voltdm;
    const s16 prcm_offs;
    const u8 pwrsts;
    const u8 pwrsts_logic_ret;
    const u8 flags;
    const u8 banks;
    const const u8[5] pwrsts_mem_ret;
    const const u8[5] pwrsts_mem_on;
    const u8 prcm_partition;
    struct clockdomain *[11] pwrdm_clkdms;
    struct list_head node;
    struct list_head voltdm_node;
    int state;
    unsigned int[4] state_counter;
    unsigned int ret_logic_off_counter;
    unsigned int[5] ret_mem_off_counter;
    spinlock_t _lock;
    long unsigned int _lock_flags;
    const u8 pwrstctrl_offs;
    const u8 pwrstst_offs;
    const u32 logicretstate_mask;
    const const u32[5] mem_on_mask;
    const const u32[5] mem_ret_mask;
    const const u32[5] mem_pwrst_mask;
    const const u32[5] mem_retst_mask;
    s64 timer;
    s64[4] state_timer;
    u32 context;
}
```
</details>
</li>
</ul>
