# Struct: <code>sysc</code>

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
struct sysc {
    struct device * dev;
    u64 module_pa;
    u32 module_size;
    void * module_va;
    int[3] offsets;
    struct ti_sysc_module_data * mdata;
    struct clk * * clocks;
    const char * * clock_roles;
    int nr_clocks;
    struct reset_control * rsts;
    const char * legacy_mode;
    const struct sysc_capabilities * cap;
    struct sysc_config cfg;
    struct ti_sysc_cookie cookie;
    const char * name;
    u32 revision;
    unsigned int enabled;
    unsigned int needs_resume;
    unsigned int child_needs_resume;
    struct delayed_work idle_work;
    void (*)(struct sysc *) clk_enable_quirk;
    void (*)(struct sysc *) clk_disable_quirk;
    void (*)(struct sysc *) reset_done_quirk;
    void (*)(struct sysc *) module_enable_quirk;
    void (*)(struct sysc *) module_disable_quirk;
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
struct sysc {
    struct device * dev;
    u64 module_pa;
    u32 module_size;
    void * module_va;
    int[3] offsets;
    struct ti_sysc_module_data * mdata;
    struct clk * * clocks;
    const char * * clock_roles;
    int nr_clocks;
    struct reset_control * rsts;
    const char * legacy_mode;
    const struct sysc_capabilities * cap;
    struct sysc_config cfg;
    struct ti_sysc_cookie cookie;
    const char * name;
    u32 revision;
    unsigned int enabled;
    unsigned int needs_resume;
    unsigned int child_needs_resume;
    struct delayed_work idle_work;
    void (*)(struct sysc *) clk_enable_quirk;
    void (*)(struct sysc *) clk_disable_quirk;
    void (*)(struct sysc *) reset_done_quirk;
    void (*)(struct sysc *) module_enable_quirk;
    void (*)(struct sysc *) module_disable_quirk;
}
```
</details>
</li>
</ul>
