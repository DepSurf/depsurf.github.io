# Struct: <code>uart_8250_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    short unsigned int capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    short unsigned int capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    void (*)(struct uart_8250_port *) rs485_start_tx;
    void (*)(struct uart_8250_port *) rs485_stop_tx;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    void (*)(struct uart_8250_port *) rs485_start_tx;
    void (*)(struct uart_8250_port *) rs485_stop_tx;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    void (*)(struct uart_8250_port *) rs485_start_tx;
    void (*)(struct uart_8250_port *) rs485_stop_tx;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    void (*)(struct uart_8250_port *) rs485_start_tx;
    void (*)(struct uart_8250_port *) rs485_stop_tx;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    void (*)(struct uart_8250_port *) rs485_start_tx;
    void (*)(struct uart_8250_port *) rs485_stop_tx;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    u16 lsr_saved_flags;
    u16 lsr_save_mask;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    void (*)(struct uart_8250_port *) rs485_start_tx;
    void (*)(struct uart_8250_port *) rs485_stop_tx;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    u16 bugs;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    u16 lsr_saved_flags;
    u16 lsr_save_mask;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    u32 (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, u32) dl_write;
    struct uart_8250_em485 * em485;
    void (*)(struct uart_8250_port *) rs485_start_tx;
    void (*)(struct uart_8250_port *) rs485_stop_tx;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    u16 bugs;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    u16 lsr_saved_flags;
    u16 lsr_save_mask;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    u32 (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, u32) dl_write;
    struct uart_8250_em485 * em485;
    void (*)(struct uart_8250_port *) rs485_start_tx;
    void (*)(struct uart_8250_port *) rs485_stop_tx;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct uart_8250_port {
    struct uart_port port;
    struct timer_list timer;
    struct list_head list;
    u32 capabilities;
    short unsigned int bugs;
    bool fifo_bug;
    unsigned int tx_loadsz;
    unsigned char acr;
    unsigned char fcr;
    unsigned char ier;
    unsigned char lcr;
    unsigned char mcr;
    unsigned char mcr_mask;
    unsigned char mcr_force;
    unsigned char cur_iotype;
    unsigned int rpm_tx_active;
    unsigned char canary;
    unsigned char probe;
    struct mctrl_gpios * gpios;
    unsigned char lsr_saved_flags;
    unsigned char msr_saved_flags;
    struct uart_8250_dma * dma;
    const struct uart_8250_ops * ops;
    int (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, int) dl_write;
    struct uart_8250_em485 * em485;
    struct delayed_work overrun_backoff;
    u32 overrun_backoff_time_ms;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct uart_8250_em485 * em485</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>short unsigned int capabilities</code> ➡️ <code>u32 capabilities</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct delayed_work overrun_backoff</code>
</li>
<li>
<b>Field added. </b>
<code>u32 overrun_backoff_time_ms</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mctrl_gpios * gpios</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct uart_8250_port *) rs485_start_tx</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct uart_8250_port *) rs485_stop_tx</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned char mcr_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char mcr_force</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 lsr_save_mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned char lsr_saved_flags</code> ➡️ <code>u16 lsr_saved_flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool fifo_bug</code>
</li>
<li>
<b>Field type changed. </b>
<code>short unsigned int bugs</code> ➡️ <code>u16 bugs</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct uart_8250_port *) dl_read</code> ➡️ <code>u32 (*)(struct uart_8250_port *) dl_read</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct uart_8250_port *, int) dl_write</code> ➡️ <code>void (*)(struct uart_8250_port *, u32) dl_write</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
