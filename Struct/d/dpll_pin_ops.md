# Struct: <code>dpll_pin_ops</code>

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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dpll_pin_ops {
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, const u64, struct netlink_ext_ack *) frequency_set;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, u64 *, struct netlink_ext_ack *) frequency_get;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, const enum dpll_pin_direction, struct netlink_ext_ack *) direction_set;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, enum dpll_pin_direction *, struct netlink_ext_ack *) direction_get;
    int (*)(const struct dpll_pin *, void *, const struct dpll_pin *, void *, enum dpll_pin_state *, struct netlink_ext_ack *) state_on_pin_get;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, enum dpll_pin_state *, struct netlink_ext_ack *) state_on_dpll_get;
    int (*)(const struct dpll_pin *, void *, const struct dpll_pin *, void *, const enum dpll_pin_state, struct netlink_ext_ack *) state_on_pin_set;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, const enum dpll_pin_state, struct netlink_ext_ack *) state_on_dpll_set;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, u32 *, struct netlink_ext_ack *) prio_get;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, const u32, struct netlink_ext_ack *) prio_set;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, s64 *, struct netlink_ext_ack *) phase_offset_get;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, s32 *, struct netlink_ext_ack *) phase_adjust_get;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, const s32, struct netlink_ext_ack *) phase_adjust_set;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, s64 *, struct netlink_ext_ack *) ffo_get;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct dpll_pin_ops {
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, const u64, struct netlink_ext_ack *) frequency_set;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, u64 *, struct netlink_ext_ack *) frequency_get;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, const enum dpll_pin_direction, struct netlink_ext_ack *) direction_set;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, enum dpll_pin_direction *, struct netlink_ext_ack *) direction_get;
    int (*)(const struct dpll_pin *, void *, const struct dpll_pin *, void *, enum dpll_pin_state *, struct netlink_ext_ack *) state_on_pin_get;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, enum dpll_pin_state *, struct netlink_ext_ack *) state_on_dpll_get;
    int (*)(const struct dpll_pin *, void *, const struct dpll_pin *, void *, const enum dpll_pin_state, struct netlink_ext_ack *) state_on_pin_set;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, const enum dpll_pin_state, struct netlink_ext_ack *) state_on_dpll_set;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, u32 *, struct netlink_ext_ack *) prio_get;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, const u32, struct netlink_ext_ack *) prio_set;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, s64 *, struct netlink_ext_ack *) phase_offset_get;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, s32 *, struct netlink_ext_ack *) phase_adjust_get;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, const s32, struct netlink_ext_ack *) phase_adjust_set;
    int (*)(const struct dpll_pin *, void *, const struct dpll_device *, void *, s64 *, struct netlink_ext_ack *) ffo_get;
}
```
</details>
</li>
</ul>
