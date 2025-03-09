# Struct: <code>ti_sci_dev_ops</code>

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
struct ti_sci_dev_ops {
    int (*)(const struct ti_sci_handle *, u32) get_device;
    int (*)(const struct ti_sci_handle *, u32) get_device_exclusive;
    int (*)(const struct ti_sci_handle *, u32) idle_device;
    int (*)(const struct ti_sci_handle *, u32) idle_device_exclusive;
    int (*)(const struct ti_sci_handle *, u32) put_device;
    int (*)(const struct ti_sci_handle *, u32) is_valid;
    int (*)(const struct ti_sci_handle *, u32, u32 *) get_context_loss_count;
    int (*)(const struct ti_sci_handle *, u32, bool *) is_idle;
    int (*)(const struct ti_sci_handle *, u32, bool *, bool *) is_stop;
    int (*)(const struct ti_sci_handle *, u32, bool *, bool *) is_on;
    int (*)(const struct ti_sci_handle *, u32, bool *) is_transitioning;
    int (*)(const struct ti_sci_handle *, u32, u32) set_device_resets;
    int (*)(const struct ti_sci_handle *, u32, u32 *) get_device_resets;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
struct ti_sci_dev_ops {
    int (*)(const struct ti_sci_handle *, u32) get_device;
    int (*)(const struct ti_sci_handle *, u32) get_device_exclusive;
    int (*)(const struct ti_sci_handle *, u32) idle_device;
    int (*)(const struct ti_sci_handle *, u32) idle_device_exclusive;
    int (*)(const struct ti_sci_handle *, u32) put_device;
    int (*)(const struct ti_sci_handle *, u32) is_valid;
    int (*)(const struct ti_sci_handle *, u32, u32 *) get_context_loss_count;
    int (*)(const struct ti_sci_handle *, u32, bool *) is_idle;
    int (*)(const struct ti_sci_handle *, u32, bool *, bool *) is_stop;
    int (*)(const struct ti_sci_handle *, u32, bool *, bool *) is_on;
    int (*)(const struct ti_sci_handle *, u32, bool *) is_transitioning;
    int (*)(const struct ti_sci_handle *, u32, u32) set_device_resets;
    int (*)(const struct ti_sci_handle *, u32, u32 *) get_device_resets;
}
```
</details>
</li>
</ul>
