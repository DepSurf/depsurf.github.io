# Struct: <code>machine_desc</code>

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
struct machine_desc {
    unsigned int nr;
    const char * name;
    long unsigned int atag_offset;
    const const char * * dt_compat;
    unsigned int nr_irqs;
    unsigned int video_start;
    unsigned int video_end;
    unsigned char reserve_lp0;
    unsigned char reserve_lp1;
    unsigned char reserve_lp2;
    enum reboot_mode reboot_mode;
    unsigned int l2c_aux_val;
    unsigned int l2c_aux_mask;
    void (*)(long unsigned int, unsigned int) l2c_write_sec;
    const struct smp_operations * smp;
    bool (*)() smp_init;
    void (*)(struct tag *, char * *) fixup;
    void (*)() dt_fixup;
    long long int (*)() pv_fixup;
    void (*)() reserve;
    void (*)() map_io;
    void (*)() init_early;
    void (*)() init_irq;
    void (*)() init_time;
    void (*)() init_machine;
    void (*)() init_late;
    void (*)(struct pt_regs *) handle_irq;
    void (*)(enum reboot_mode, const char *) restart;
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
struct machine_desc {
    unsigned int nr;
    const char * name;
    long unsigned int atag_offset;
    const const char * * dt_compat;
    unsigned int nr_irqs;
    unsigned int video_start;
    unsigned int video_end;
    unsigned char reserve_lp0;
    unsigned char reserve_lp1;
    unsigned char reserve_lp2;
    enum reboot_mode reboot_mode;
    unsigned int l2c_aux_val;
    unsigned int l2c_aux_mask;
    void (*)(long unsigned int, unsigned int) l2c_write_sec;
    const struct smp_operations * smp;
    bool (*)() smp_init;
    void (*)(struct tag *, char * *) fixup;
    void (*)() dt_fixup;
    long long int (*)() pv_fixup;
    void (*)() reserve;
    void (*)() map_io;
    void (*)() init_early;
    void (*)() init_irq;
    void (*)() init_time;
    void (*)() init_machine;
    void (*)() init_late;
    void (*)(struct pt_regs *) handle_irq;
    void (*)(enum reboot_mode, const char *) restart;
}
```
</details>
</li>
</ul>
