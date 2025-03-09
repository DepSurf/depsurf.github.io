# Struct: <code>uart_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) start_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) start_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, const struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) start_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, const struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) start_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, const struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
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
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
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
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct uart_ops {
    unsigned int (*)(struct uart_port *) tx_empty;
    void (*)(struct uart_port *, unsigned int) set_mctrl;
    unsigned int (*)(struct uart_port *) get_mctrl;
    void (*)(struct uart_port *) stop_tx;
    void (*)(struct uart_port *) start_tx;
    void (*)(struct uart_port *) throttle;
    void (*)(struct uart_port *) unthrottle;
    void (*)(struct uart_port *, char) send_xchar;
    void (*)(struct uart_port *) stop_rx;
    void (*)(struct uart_port *) enable_ms;
    void (*)(struct uart_port *, int) break_ctl;
    int (*)(struct uart_port *) startup;
    void (*)(struct uart_port *) shutdown;
    void (*)(struct uart_port *) flush_buffer;
    void (*)(struct uart_port *, struct ktermios *, struct ktermios *) set_termios;
    void (*)(struct uart_port *, struct ktermios *) set_ldisc;
    void (*)(struct uart_port *, unsigned int, unsigned int) pm;
    const char * (*)(struct uart_port *) type;
    void (*)(struct uart_port *) release_port;
    int (*)(struct uart_port *) request_port;
    void (*)(struct uart_port *, int) config_port;
    int (*)(struct uart_port *, struct serial_struct *) verify_port;
    int (*)(struct uart_port *, unsigned int, long unsigned int) ioctl;
    int (*)(struct uart_port *) poll_init;
    void (*)(struct uart_port *, unsigned char) poll_put_char;
    int (*)(struct uart_port *) poll_get_char;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<code>void (*)(struct uart_port *) start_rx</code>
</li>
</ul>
</details>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct uart_port *) poll_init</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct uart_port *, unsigned char) poll_put_char</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct uart_port *) poll_get_char</code>
</li>
</ul>
</details>
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
