# Struct: <code>si_sm_io</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct si_sm_io {
    unsigned char (*)(const struct si_sm_io *, unsigned int) inputb;
    void (*)(const struct si_sm_io *, unsigned int, unsigned char) outputb;
    void * addr;
    int regspacing;
    int regsize;
    int regshift;
    int addr_type;
    long int addr_data;
    enum ipmi_addr_src addr_source;
    void (*)(struct si_sm_io *) addr_source_cleanup;
    void * addr_source_data;
    union ipmi_smi_info_union addr_info;
    int (*)(struct si_sm_io *) io_setup;
    void (*)(struct si_sm_io *) io_cleanup;
    unsigned int io_size;
    int irq;
    int (*)(struct si_sm_io *) irq_setup;
    void * irq_handler_data;
    void (*)(struct si_sm_io *) irq_cleanup;
    u8 slave_addr;
    enum si_type si_type;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct si_sm_io {
    unsigned char (*)(const struct si_sm_io *, unsigned int) inputb;
    void (*)(const struct si_sm_io *, unsigned int, unsigned char) outputb;
    void * addr;
    int regspacing;
    int regsize;
    int regshift;
    int addr_type;
    long int addr_data;
    enum ipmi_addr_src addr_source;
    void (*)(struct si_sm_io *) addr_source_cleanup;
    void * addr_source_data;
    union ipmi_smi_info_union addr_info;
    int (*)(struct si_sm_io *) io_setup;
    void (*)(struct si_sm_io *) io_cleanup;
    unsigned int io_size;
    int irq;
    int (*)(struct si_sm_io *) irq_setup;
    void * irq_handler_data;
    void (*)(struct si_sm_io *) irq_cleanup;
    u8 slave_addr;
    enum si_type si_type;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct si_sm_io {
    unsigned char (*)(const struct si_sm_io *, unsigned int) inputb;
    void (*)(const struct si_sm_io *, unsigned int, unsigned char) outputb;
    void * addr;
    int regspacing;
    int regsize;
    int regshift;
    int addr_type;
    long int addr_data;
    enum ipmi_addr_src addr_source;
    void (*)(struct si_sm_io *) addr_source_cleanup;
    void * addr_source_data;
    union ipmi_smi_info_union addr_info;
    int (*)(struct si_sm_io *) io_setup;
    void (*)(struct si_sm_io *) io_cleanup;
    unsigned int io_size;
    int irq;
    int (*)(struct si_sm_io *) irq_setup;
    void * irq_handler_data;
    void (*)(struct si_sm_io *) irq_cleanup;
    u8 slave_addr;
    enum si_type si_type;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct si_sm_io {
    unsigned char (*)(const struct si_sm_io *, unsigned int) inputb;
    void (*)(const struct si_sm_io *, unsigned int, unsigned char) outputb;
    void * addr;
    unsigned int regspacing;
    unsigned int regsize;
    unsigned int regshift;
    enum ipmi_addr_space addr_space;
    long unsigned int addr_data;
    enum ipmi_addr_src addr_source;
    void (*)(struct si_sm_io *) addr_source_cleanup;
    void * addr_source_data;
    union ipmi_smi_info_union addr_info;
    int (*)(struct si_sm_io *) io_setup;
    void (*)(struct si_sm_io *) io_cleanup;
    unsigned int io_size;
    int irq;
    int (*)(struct si_sm_io *) irq_setup;
    void * irq_handler_data;
    void (*)(struct si_sm_io *) irq_cleanup;
    u8 slave_addr;
    enum si_type si_type;
    struct device * dev;
}
```
</details>
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct si_sm_io {
    unsigned char (*)(const struct si_sm_io *, unsigned int) inputb;
    void (*)(const struct si_sm_io *, unsigned int, unsigned char) outputb;
    void * addr;
    int regspacing;
    int regsize;
    int regshift;
    int addr_type;
    long int addr_data;
    enum ipmi_addr_src addr_source;
    void (*)(struct si_sm_io *) addr_source_cleanup;
    void * addr_source_data;
    union ipmi_smi_info_union addr_info;
    int (*)(struct si_sm_io *) io_setup;
    void (*)(struct si_sm_io *) io_cleanup;
    unsigned int io_size;
    int irq;
    int (*)(struct si_sm_io *) irq_setup;
    void * irq_handler_data;
    void (*)(struct si_sm_io *) irq_cleanup;
    u8 slave_addr;
    enum si_type si_type;
    struct device * dev;
}
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum ipmi_addr_space addr_space</code>
</li>
<li>
<b>Field removed. </b>
<code>int addr_type</code>
</li>
<li>
<b>Field type changed. </b>
<code>int regspacing</code> ➡️ <code>unsigned int regspacing</code>
</li>
<li>
<b>Field type changed. </b>
<code>int regsize</code> ➡️ <code>unsigned int regsize</code>
</li>
<li>
<b>Field type changed. </b>
<code>int regshift</code> ➡️ <code>unsigned int regshift</code>
</li>
<li>
<b>Field type changed. </b>
<code>long int addr_data</code> ➡️ <code>long unsigned int addr_data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
struct si_sm_io {
    unsigned char (*)(const struct si_sm_io *, unsigned int) inputb;
    void (*)(const struct si_sm_io *, unsigned int, unsigned char) outputb;
    void * addr;
    unsigned int regspacing;
    unsigned int regsize;
    unsigned int regshift;
    enum ipmi_addr_space addr_space;
    long unsigned int addr_data;
    enum ipmi_addr_src addr_source;
    void (*)(struct si_sm_io *) addr_source_cleanup;
    void * addr_source_data;
    union ipmi_smi_info_union addr_info;
    int (*)(struct si_sm_io *) io_setup;
    void (*)(struct si_sm_io *) io_cleanup;
    unsigned int io_size;
    int irq;
    int (*)(struct si_sm_io *) irq_setup;
    void * irq_handler_data;
    void (*)(struct si_sm_io *) irq_cleanup;
    u8 slave_addr;
    enum si_type si_type;
    struct device * dev;
}
```
</details>
</li>
</ul>
