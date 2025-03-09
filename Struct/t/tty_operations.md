# Struct: <code>tty_operations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct inode *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    const struct file_operations * proc_fops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    const struct file_operations * proc_fops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    const struct file_operations * proc_fops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    const struct file_operations * proc_fops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    const struct file_operations * proc_fops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    unsigned int (*)(struct tty_struct *) write_room;
    unsigned int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    unsigned int (*)(struct tty_struct *) write_room;
    unsigned int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    unsigned int (*)(struct tty_struct *) write_room;
    unsigned int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, const struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    unsigned int (*)(struct tty_struct *) write_room;
    unsigned int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, const struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    ssize_t (*)(struct tty_struct *, const u8 *, size_t) write;
    int (*)(struct tty_struct *, u8) put_char;
    void (*)(struct tty_struct *) flush_chars;
    unsigned int (*)(struct tty_struct *) write_room;
    unsigned int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, const struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, u8) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
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
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct seq_file *, void *) proc_show;
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
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tty_operations {
    struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup;
    int (*)(struct tty_driver *, struct tty_struct *) install;
    void (*)(struct tty_driver *, struct tty_struct *) remove;
    int (*)(struct tty_struct *, struct file *) open;
    void (*)(struct tty_struct *, struct file *) close;
    void (*)(struct tty_struct *) shutdown;
    void (*)(struct tty_struct *) cleanup;
    int (*)(struct tty_struct *, const unsigned char *, int) write;
    int (*)(struct tty_struct *, unsigned char) put_char;
    void (*)(struct tty_struct *) flush_chars;
    int (*)(struct tty_struct *) write_room;
    int (*)(struct tty_struct *) chars_in_buffer;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    void (*)(struct tty_struct *) throttle;
    void (*)(struct tty_struct *) unthrottle;
    void (*)(struct tty_struct *) stop;
    void (*)(struct tty_struct *) start;
    void (*)(struct tty_struct *) hangup;
    int (*)(struct tty_struct *, int) break_ctl;
    void (*)(struct tty_struct *) flush_buffer;
    void (*)(struct tty_struct *) set_ldisc;
    void (*)(struct tty_struct *, int) wait_until_sent;
    void (*)(struct tty_struct *, char) send_xchar;
    int (*)(struct tty_struct *) tiocmget;
    int (*)(struct tty_struct *, unsigned int, unsigned int) tiocmset;
    int (*)(struct tty_struct *, struct winsize *) resize;
    int (*)(struct tty_struct *, struct termiox *) set_termiox;
    int (*)(struct tty_struct *, struct serial_icounter_struct *) get_icount;
    int (*)(struct tty_struct *, struct serial_struct *) get_serial;
    int (*)(struct tty_struct *, struct serial_struct *) set_serial;
    void (*)(struct tty_struct *, struct seq_file *) show_fdinfo;
    int (*)(struct tty_driver *, int, char *) poll_init;
    int (*)(struct tty_driver *, int) poll_get_char;
    void (*)(struct tty_driver *, int, char) poll_put_char;
    int (*)(struct seq_file *, void *) proc_show;
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
<b>Field type changed. </b>
<code>struct tty_struct * (*)(struct tty_driver *, struct inode *, int) lookup</code> ➡️ <code>struct tty_struct * (*)(struct tty_driver *, struct file *, int) lookup</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct tty_struct *, struct seq_file *) show_fdinfo</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct seq_file *, void *) proc_show</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct file_operations * proc_fops</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct tty_struct *, struct serial_struct *) get_serial</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct tty_struct *, struct serial_struct *) set_serial</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct tty_struct *, struct termiox *) set_termiox</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct tty_struct *) write_room</code> ➡️ <code>unsigned int (*)(struct tty_struct *) write_room</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct tty_struct *) chars_in_buffer</code> ➡️ <code>unsigned int (*)(struct tty_struct *) chars_in_buffer</code>
</li>
</ul>
</details>
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
<code>void (*)(struct tty_struct *, struct ktermios *) set_termios</code> ➡️ <code>void (*)(struct tty_struct *, const struct ktermios *) set_termios</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct tty_struct *, const unsigned char *, int) write</code> ➡️ <code>ssize_t (*)(struct tty_struct *, const u8 *, size_t) write</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct tty_struct *, unsigned char) put_char</code> ➡️ <code>int (*)(struct tty_struct *, u8) put_char</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct tty_struct *, char) send_xchar</code> ➡️ <code>void (*)(struct tty_struct *, u8) send_xchar</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct tty_driver *, int, char *) poll_init</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct tty_driver *, int) poll_get_char</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct tty_driver *, int, char) poll_put_char</code>
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
