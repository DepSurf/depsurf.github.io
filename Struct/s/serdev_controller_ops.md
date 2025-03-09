# Struct: <code>serdev_controller_ops</code>

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
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
    int (*)(struct serdev_controller *, unsigned int) break_ctl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct serdev_controller_ops {
    ssize_t (*)(struct serdev_controller *, const u8 *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
    int (*)(struct serdev_controller *, unsigned int) break_ctl;
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
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
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
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct serdev_controller *, enum serdev_parity) set_parity</code>
</li>
</ul>
</details>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct serdev_controller *, unsigned int) break_ctl</code>
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
<code>int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf</code> ➡️ <code>ssize_t (*)(struct serdev_controller *, const u8 *, size_t) write_buf</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct serdev_controller_ops {
    int (*)(struct serdev_controller *, const unsigned char *, size_t) write_buf;
    void (*)(struct serdev_controller *) write_flush;
    int (*)(struct serdev_controller *) write_room;
    int (*)(struct serdev_controller *) open;
    void (*)(struct serdev_controller *) close;
    void (*)(struct serdev_controller *, bool) set_flow_control;
    int (*)(struct serdev_controller *, enum serdev_parity) set_parity;
    unsigned int (*)(struct serdev_controller *, unsigned int) set_baudrate;
    void (*)(struct serdev_controller *, long int) wait_until_sent;
    int (*)(struct serdev_controller *) get_tiocm;
    int (*)(struct serdev_controller *, unsigned int, unsigned int) set_tiocm;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
