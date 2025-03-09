# Struct: <code>plat_serial8250_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    unsigned char has_sysrq;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    unsigned char has_sysrq;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    unsigned char has_sysrq;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    unsigned char has_sysrq;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    unsigned char has_sysrq;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    unsigned char has_sysrq;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, const struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    resource_size_t mapsize;
    unsigned int uartclk;
    unsigned int irq;
    long unsigned int irqflags;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    unsigned char has_sysrq;
    unsigned int type;
    upf_t flags;
    u16 bugs;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    u32 (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, u32) dl_write;
    void (*)(struct uart_port *, struct ktermios *, const struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    resource_size_t mapsize;
    unsigned int uartclk;
    unsigned int irq;
    long unsigned int irqflags;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    unsigned char has_sysrq;
    unsigned int type;
    upf_t flags;
    u16 bugs;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    u32 (*)(struct uart_8250_port *) dl_read;
    void (*)(struct uart_8250_port *, u32) dl_write;
    void (*)(struct uart_port *, struct ktermios *, const struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
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
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
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
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct plat_serial8250_port {
    long unsigned int iobase;
    void * membase;
    resource_size_t mapbase;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    void * private_data;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char hub6;
    upf_t flags;
    unsigned int type;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
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
<code>unsigned int (*)(struct uart_port *) get_mctrl</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct uart_port *, struct ktermios *) set_ldisc</code>
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<code>unsigned char has_sysrq</code>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios</code> ➡️ <code>void (*)(struct uart_port *, struct ktermios *, const struct ktermios *) set_termios</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>resource_size_t mapsize</code>
</li>
<li>
<b>Field added. </b>
<code>u16 bugs</code>
</li>
<li>
<b>Field added. </b>
<code>u32 (*)(struct uart_8250_port *) dl_read</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct uart_8250_port *, u32) dl_write</code>
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
