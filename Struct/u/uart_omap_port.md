# Struct: <code>uart_omap_port</code>

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
struct uart_omap_port {
    struct uart_port port;
    struct uart_omap_dma uart_dma;
    struct device * dev;
    int wakeirq;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char fcr;
    unsigned char efr;
    unsigned char dll;
    unsigned char dlh;
    unsigned char mdr1;
    unsigned char scr;
    unsigned char wer;
    int use_dma;
    unsigned int lsr_break_flag;
    unsigned char msr_saved_flags;
    char[20] name;
    long unsigned int port_activity;
    int context_loss_cnt;
    u32 errata;
    u32 features;
    int rts_gpio;
    struct pm_qos_request pm_qos_request;
    u32 latency;
    u32 calc_latency;
    struct work_struct qos_work;
    bool is_suspending;
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
struct uart_omap_port {
    struct uart_port port;
    struct uart_omap_dma uart_dma;
    struct device * dev;
    int wakeirq;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char fcr;
    unsigned char efr;
    unsigned char dll;
    unsigned char dlh;
    unsigned char mdr1;
    unsigned char scr;
    unsigned char wer;
    int use_dma;
    unsigned int lsr_break_flag;
    unsigned char msr_saved_flags;
    char[20] name;
    long unsigned int port_activity;
    int context_loss_cnt;
    u32 errata;
    u32 features;
    int rts_gpio;
    struct pm_qos_request pm_qos_request;
    u32 latency;
    u32 calc_latency;
    struct work_struct qos_work;
    bool is_suspending;
}
```
</details>
</li>
</ul>
