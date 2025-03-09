# Struct: <code>kiocb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    enum rw_hint ki_hint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    enum rw_hint ki_hint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_hint;
    u16 ki_ioprio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_hint;
    u16 ki_ioprio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_hint;
    u16 ki_ioprio;
    unsigned int ki_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_hint;
    u16 ki_ioprio;
    unsigned int ki_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_hint;
    u16 ki_ioprio;
    unsigned int ki_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_hint;
    u16 ki_ioprio;
    unsigned int ki_cookie;
    struct wait_page_queue * ki_waitq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_hint;
    u16 ki_ioprio;
    unsigned int ki_cookie;
    struct wait_page_queue * ki_waitq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_hint;
    u16 ki_ioprio;
    unsigned int ki_cookie;
    struct wait_page_queue * ki_waitq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_ioprio;
    struct wait_page_queue * ki_waitq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_ioprio;
    struct wait_page_queue * ki_waitq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_ioprio;
    struct wait_page_queue * ki_waitq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_ioprio;
    struct wait_page_queue * ki_waitq;
    ssize_t (*)(void *) dio_complete;
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
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_hint;
    u16 ki_ioprio;
    unsigned int ki_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_hint;
    u16 ki_ioprio;
    unsigned int ki_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_hint;
    u16 ki_ioprio;
    unsigned int ki_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_hint;
    u16 ki_ioprio;
    unsigned int ki_cookie;
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
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_hint;
    u16 ki_ioprio;
    unsigned int ki_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_hint;
    u16 ki_ioprio;
    unsigned int ki_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_hint;
    u16 ki_ioprio;
    unsigned int ki_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct kiocb {
    struct file * ki_filp;
    loff_t ki_pos;
    void (*)(struct kiocb *, long int, long int) ki_complete;
    void * private;
    int ki_flags;
    u16 ki_hint;
    u16 ki_ioprio;
    unsigned int ki_cookie;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum rw_hint ki_hint</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 ki_ioprio</code>
</li>
<li>
<b>Field type changed. </b>
<code>enum rw_hint ki_hint</code> ➡️ <code>u16 ki_hint</code>
</li>
</ul>
</details>
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
<code>unsigned int ki_cookie</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>struct wait_page_queue * ki_waitq</code>
</li>
</ul>
</details>
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
<code>u16 ki_hint</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int ki_cookie</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct kiocb *, long int, long int) ki_complete</code> ➡️ <code>void (*)(struct kiocb *, long int) ki_complete</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>ssize_t (*)(void *) dio_complete</code>
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
