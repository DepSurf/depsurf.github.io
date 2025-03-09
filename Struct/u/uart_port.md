# Struct: <code>uart_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char unused1;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char irq_wake;
    unsigned char[2] unused;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char unused1;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char irq_wake;
    unsigned char[2] unused;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char unused1;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char irq_wake;
    unsigned char[2] unused;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char unused1;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char irq_wake;
    unsigned char[2] unused;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char[2] unused;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char[2] unused;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char[2] unused;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct serial_iso7816 iso7816;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char[2] unused;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct serial_iso7816 iso7816;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char[2] unused;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct serial_iso7816 iso7816;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    unsigned char has_sysrq;
    unsigned char sysrq_seq;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char console_reinit;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct gpio_desc * rs485_term_gpio;
    struct serial_iso7816 iso7816;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    unsigned char has_sysrq;
    unsigned char sysrq_seq;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char console_reinit;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct gpio_desc * rs485_term_gpio;
    struct serial_iso7816 iso7816;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    unsigned char has_sysrq;
    unsigned char sysrq_seq;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char console_reinit;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct gpio_desc * rs485_term_gpio;
    struct serial_iso7816 iso7816;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    unsigned char has_sysrq;
    unsigned char sysrq_seq;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char console_reinit;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct gpio_desc * rs485_term_gpio;
    struct serial_iso7816 iso7816;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int frame_time;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    unsigned char has_sysrq;
    unsigned char sysrq_seq;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char console_reinit;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct gpio_desc * rs485_term_gpio;
    struct serial_iso7816 iso7816;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, const struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct ktermios *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int frame_time;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    unsigned char has_sysrq;
    unsigned char sysrq_seq;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char console_reinit;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct serial_rs485 rs485_supported;
    struct gpio_desc * rs485_term_gpio;
    struct serial_iso7816 iso7816;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, const struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct ktermios *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int ctrl_id;
    unsigned int port_id;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    upf_t flags;
    upstat_t status;
    bool hw_stopped;
    unsigned int mctrl;
    unsigned int frame_time;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    struct serial_port_device * port_dev;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    unsigned char has_sysrq;
    unsigned char sysrq_seq;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char console_reinit;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct serial_rs485 rs485_supported;
    struct gpio_desc * rs485_term_gpio;
    struct gpio_desc * rs485_rx_during_tx_gpio;
    struct serial_iso7816 iso7816;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, const struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct ktermios *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int ctrl_id;
    unsigned int port_id;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    upf_t flags;
    upstat_t status;
    bool hw_stopped;
    unsigned int mctrl;
    unsigned int frame_time;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    struct serial_port_device * port_dev;
    long unsigned int sysrq;
    u8 sysrq_ch;
    unsigned char has_sysrq;
    unsigned char sysrq_seq;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char console_reinit;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct serial_rs485 rs485_supported;
    struct gpio_desc * rs485_term_gpio;
    struct gpio_desc * rs485_rx_during_tx_gpio;
    struct serial_iso7816 iso7816;
    void * private_data;
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
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char[2] unused;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct serial_iso7816 iso7816;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char[2] unused;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct serial_iso7816 iso7816;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char[2] unused;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct serial_iso7816 iso7816;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char[2] unused;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct serial_iso7816 iso7816;
    void * private_data;
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
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char[2] unused;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct serial_iso7816 iso7816;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char[2] unused;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct serial_iso7816 iso7816;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char[2] unused;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct serial_iso7816 iso7816;
    void * private_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct uart_port {
    spinlock_t lock;
    long unsigned int iobase;
    unsigned char * membase;
    unsigned int (*)(struct uart_port *, int) serial_in;
    void (*)(struct uart_port *, int, int) serial_out;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor;
    void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    int (*)(struct uart_port *) handle_irq;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    void (*)(struct uart_port *) handle_break;
    int (*)(struct uart_port *, struct serial_rs485 *) rs485_config;
    int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config;
    unsigned int irq;
    long unsigned int irqflags;
    unsigned int uartclk;
    unsigned int fifosize;
    unsigned char x_char;
    unsigned char regshift;
    unsigned char iotype;
    unsigned char quirks;
    unsigned int read_status_mask;
    unsigned int ignore_status_mask;
    struct uart_state * state;
    struct uart_icount icount;
    struct console * cons;
    long unsigned int sysrq;
    unsigned int sysrq_ch;
    upf_t flags;
    upstat_t status;
    int hw_stopped;
    unsigned int mctrl;
    unsigned int timeout;
    unsigned int type;
    const struct uart_ops * ops;
    unsigned int custom_divisor;
    unsigned int line;
    unsigned int minor;
    resource_size_t mapbase;
    resource_size_t mapsize;
    struct device * dev;
    unsigned char hub6;
    unsigned char suspended;
    unsigned char[2] unused;
    const char * name;
    struct attribute_group * attr_group;
    const struct attribute_group * * tty_groups;
    struct serial_rs485 rs485;
    struct serial_iso7816 iso7816;
    void * private_data;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const char * name</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned char quirks</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char unused1</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char irq_wake</code>
</li>
</ul>
</details>
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
<code>unsigned int (*)(struct uart_port *, unsigned int, unsigned int *) get_divisor</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct uart_port *, unsigned int, unsigned int, unsigned int) set_divisor</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct uart_port *, struct serial_iso7816 *) iso7816_config</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sysrq_ch</code>
</li>
<li>
<b>Field added. </b>
<code>struct serial_iso7816 iso7816</code>
</li>
</ul>
</details>
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
<li>
<b>Field added. </b>
<code>unsigned char sysrq_seq</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char console_reinit</code>
</li>
<li>
<b>Field added. </b>
<code>struct gpio_desc * rs485_term_gpio</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char[2] unused</code>
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
<b>Field added. </b>
<code>unsigned int frame_time</code>
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
<code>struct serial_rs485 rs485_supported</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int timeout</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios</code> ➡️ <code>void (*)(struct uart_port *, struct ktermios *, const struct ktermios *) set_termios</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct uart_port *, struct serial_rs485 *) rs485_config</code> ➡️ <code>int (*)(struct uart_port *, struct ktermios *, struct serial_rs485 *) rs485_config</code>
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
<code>unsigned int ctrl_id</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int port_id</code>
</li>
<li>
<b>Field added. </b>
<code>struct serial_port_device * port_dev</code>
</li>
<li>
<b>Field added. </b>
<code>struct gpio_desc * rs485_rx_during_tx_gpio</code>
</li>
<li>
<b>Field type changed. </b>
<code>int hw_stopped</code> ➡️ <code>bool hw_stopped</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned int sysrq_ch</code> ➡️ <code>u8 sysrq_ch</code>
</li>
</ul>
</details>
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
