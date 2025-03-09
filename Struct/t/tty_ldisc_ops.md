# Struct: <code>tty_ldisc_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *) chars_in_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    unsigned int (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    void (*)(struct tty_struct *, int) fasync;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    unsigned int (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    unsigned int (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    unsigned int (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    unsigned int (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    long int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t, void * *, long unsigned int) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t, void * *, long unsigned int) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t, void * *, long unsigned int) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, const char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, const char *, int) receive_buf2;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    char * name;
    int num;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t, void * *, long unsigned int) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    void (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, const char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, const char *, int) receive_buf2;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    char * name;
    int num;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t, void * *, long unsigned int) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, const struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    void (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, const char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, const char *, int) receive_buf2;
    void (*)(struct tty_struct *, const unsigned char *, const unsigned char *, unsigned int) lookahead_buf;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    char * name;
    int num;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t, void * *, long unsigned int) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, const struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    void (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, const char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, bool) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, const char *, int) receive_buf2;
    void (*)(struct tty_struct *, const unsigned char *, const unsigned char *, unsigned int) lookahead_buf;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    char * name;
    int num;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, u8 *, size_t, void * *, long unsigned int) read;
    ssize_t (*)(struct tty_struct *, struct file *, const u8 *, size_t) write;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, const struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    void (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const u8 *, const u8 *, size_t) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, bool) dcd_change;
    size_t (*)(struct tty_struct *, const u8 *, const u8 *, size_t) receive_buf2;
    void (*)(struct tty_struct *, const u8 *, const u8 *, size_t) lookahead_buf;
    struct module * owner;
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
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
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
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tty_ldisc_ops {
    int magic;
    char * name;
    int num;
    int flags;
    int (*)(struct tty_struct *) open;
    void (*)(struct tty_struct *) close;
    void (*)(struct tty_struct *) flush_buffer;
    ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read;
    ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl;
    int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl;
    void (*)(struct tty_struct *, struct ktermios *) set_termios;
    __poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll;
    int (*)(struct tty_struct *) hangup;
    void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf;
    void (*)(struct tty_struct *) write_wakeup;
    void (*)(struct tty_struct *, unsigned int) dcd_change;
    int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2;
    struct module * owner;
    int refcount;
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
<b>Field removed. </b>
<code>ssize_t (*)(struct tty_struct *) chars_in_buffer</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct tty_struct *, int) fasync</code>
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned int (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll</code> ➡️ <code>__poll_t (*)(struct tty_struct *, struct file *, struct poll_table_struct *) poll</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl</code> ➡️ <code>int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl</code>
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
<b>Field type changed. </b>
<code>ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t) read</code> ➡️ <code>ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t, void * *, long unsigned int) read</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int magic</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int refcount</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf</code> ➡️ <code>void (*)(struct tty_struct *, const unsigned char *, const char *, int) receive_buf</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct tty_struct *, const unsigned char *, char *, int) receive_buf2</code> ➡️ <code>int (*)(struct tty_struct *, const unsigned char *, const char *, int) receive_buf2</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int flags</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) ioctl</code> ➡️ <code>int (*)(struct tty_struct *, unsigned int, long unsigned int) ioctl</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct tty_struct *, struct file *, unsigned int, long unsigned int) compat_ioctl</code> ➡️ <code>int (*)(struct tty_struct *, unsigned int, long unsigned int) compat_ioctl</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct tty_struct *) hangup</code> ➡️ <code>void (*)(struct tty_struct *) hangup</code>
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
<code>void (*)(struct tty_struct *, const unsigned char *, const unsigned char *, unsigned int) lookahead_buf</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct tty_struct *, struct ktermios *) set_termios</code> ➡️ <code>void (*)(struct tty_struct *, const struct ktermios *) set_termios</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(struct tty_struct *, unsigned int) dcd_change</code> ➡️ <code>void (*)(struct tty_struct *, bool) dcd_change</code>
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
<code>ssize_t (*)(struct tty_struct *, struct file *, unsigned char *, size_t, void * *, long unsigned int) read</code> ➡️ <code>ssize_t (*)(struct tty_struct *, struct file *, u8 *, size_t, void * *, long unsigned int) read</code>
</li>
<li>
<b>Field type changed. </b>
<code>ssize_t (*)(struct tty_struct *, struct file *, const unsigned char *, size_t) write</code> ➡️ <code>ssize_t (*)(struct tty_struct *, struct file *, const u8 *, size_t) write</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct tty_struct *, const unsigned char *, const char *, int) receive_buf</code> ➡️ <code>void (*)(struct tty_struct *, const u8 *, const u8 *, size_t) receive_buf</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct tty_struct *, const unsigned char *, const char *, int) receive_buf2</code> ➡️ <code>size_t (*)(struct tty_struct *, const u8 *, const u8 *, size_t) receive_buf2</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct tty_struct *, const unsigned char *, const unsigned char *, unsigned int) lookahead_buf</code> ➡️ <code>void (*)(struct tty_struct *, const u8 *, const u8 *, size_t) lookahead_buf</code>
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
