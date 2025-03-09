# Struct: <code>prm_ll_data</code>

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
struct prm_ll_data {
    u32 (*)() read_reset_sources;
    bool (*)(u8, s16, u16) was_any_context_lost_old;
    void (*)(u8, s16, u16) clear_context_loss_flags_old;
    int (*)() late_init;
    int (*)(u8, u8, s16, u16) assert_hardreset;
    int (*)(u8, u8, u8, s16, u16, u16) deassert_hardreset;
    int (*)(u8, u8, s16, u16) is_hardreset_asserted;
    void (*)() reset_system;
    int (*)(s16, u8, u32) clear_mod_irqs;
    u32 (*)(u8) vp_check_txdone;
    void (*)(u8) vp_clear_txdone;
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
struct prm_ll_data {
    u32 (*)() read_reset_sources;
    bool (*)(u8, s16, u16) was_any_context_lost_old;
    void (*)(u8, s16, u16) clear_context_loss_flags_old;
    int (*)() late_init;
    int (*)(u8, u8, s16, u16) assert_hardreset;
    int (*)(u8, u8, u8, s16, u16, u16) deassert_hardreset;
    int (*)(u8, u8, s16, u16) is_hardreset_asserted;
    void (*)() reset_system;
    int (*)(s16, u8, u32) clear_mod_irqs;
    u32 (*)(u8) vp_check_txdone;
    void (*)(u8) vp_clear_txdone;
}
```
</details>
</li>
</ul>
