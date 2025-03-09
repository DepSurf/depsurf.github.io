# Struct: <code>omap_dm_timer_ops</code>

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
struct omap_dm_timer_ops {
    struct omap_dm_timer * (*)(struct device_node *) request_by_node;
    struct omap_dm_timer * (*)(int) request_specific;
    struct omap_dm_timer * (*)() request;
    int (*)(struct omap_dm_timer *) free;
    void (*)(struct omap_dm_timer *) enable;
    void (*)(struct omap_dm_timer *) disable;
    int (*)(struct omap_dm_timer *) get_irq;
    int (*)(struct omap_dm_timer *, unsigned int) set_int_enable;
    int (*)(struct omap_dm_timer *, u32) set_int_disable;
    struct clk * (*)(struct omap_dm_timer *) get_fclk;
    int (*)(struct omap_dm_timer *) start;
    int (*)(struct omap_dm_timer *) stop;
    int (*)(struct omap_dm_timer *, int) set_source;
    int (*)(struct omap_dm_timer *, int, unsigned int) set_load;
    int (*)(struct omap_dm_timer *, int, unsigned int) set_match;
    int (*)(struct omap_dm_timer *, int, int, int) set_pwm;
    int (*)(struct omap_dm_timer *, int) set_prescaler;
    unsigned int (*)(struct omap_dm_timer *) read_counter;
    int (*)(struct omap_dm_timer *, unsigned int) write_counter;
    unsigned int (*)(struct omap_dm_timer *) read_status;
    int (*)(struct omap_dm_timer *, unsigned int) write_status;
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
struct omap_dm_timer_ops {
    struct omap_dm_timer * (*)(struct device_node *) request_by_node;
    struct omap_dm_timer * (*)(int) request_specific;
    struct omap_dm_timer * (*)() request;
    int (*)(struct omap_dm_timer *) free;
    void (*)(struct omap_dm_timer *) enable;
    void (*)(struct omap_dm_timer *) disable;
    int (*)(struct omap_dm_timer *) get_irq;
    int (*)(struct omap_dm_timer *, unsigned int) set_int_enable;
    int (*)(struct omap_dm_timer *, u32) set_int_disable;
    struct clk * (*)(struct omap_dm_timer *) get_fclk;
    int (*)(struct omap_dm_timer *) start;
    int (*)(struct omap_dm_timer *) stop;
    int (*)(struct omap_dm_timer *, int) set_source;
    int (*)(struct omap_dm_timer *, int, unsigned int) set_load;
    int (*)(struct omap_dm_timer *, int, unsigned int) set_match;
    int (*)(struct omap_dm_timer *, int, int, int) set_pwm;
    int (*)(struct omap_dm_timer *, int) set_prescaler;
    unsigned int (*)(struct omap_dm_timer *) read_counter;
    int (*)(struct omap_dm_timer *, unsigned int) write_counter;
    unsigned int (*)(struct omap_dm_timer *) read_status;
    int (*)(struct omap_dm_timer *, unsigned int) write_status;
}
```
</details>
</li>
</ul>
