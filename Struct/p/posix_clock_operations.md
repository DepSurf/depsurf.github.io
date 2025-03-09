# Struct: <code>posix_clock_operations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec *) clock_settime;
    int (*)(struct posix_clock *, struct k_itimer *) timer_create;
    int (*)(struct posix_clock *, struct k_itimer *) timer_delete;
    void (*)(struct posix_clock *, struct k_itimer *, struct itimerspec *) timer_gettime;
    int (*)(struct posix_clock *, struct k_itimer *, int, struct itimerspec *, struct itimerspec *) timer_settime;
    int (*)(struct posix_clock *, int, struct file *, int) fasync;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, struct vm_area_struct *) mmap;
    int (*)(struct posix_clock *, fmode_t) open;
    uint (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec *) clock_settime;
    int (*)(struct posix_clock *, struct k_itimer *) timer_create;
    int (*)(struct posix_clock *, struct k_itimer *) timer_delete;
    void (*)(struct posix_clock *, struct k_itimer *, struct itimerspec *) timer_gettime;
    int (*)(struct posix_clock *, struct k_itimer *, int, struct itimerspec *, struct itimerspec *) timer_settime;
    int (*)(struct posix_clock *, int, struct file *, int) fasync;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, struct vm_area_struct *) mmap;
    int (*)(struct posix_clock *, fmode_t) open;
    uint (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec *) clock_settime;
    int (*)(struct posix_clock *, struct k_itimer *) timer_create;
    int (*)(struct posix_clock *, struct k_itimer *) timer_delete;
    void (*)(struct posix_clock *, struct k_itimer *, struct itimerspec *) timer_gettime;
    int (*)(struct posix_clock *, struct k_itimer *, int, struct itimerspec *, struct itimerspec *) timer_settime;
    int (*)(struct posix_clock *, int, struct file *, int) fasync;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, struct vm_area_struct *) mmap;
    int (*)(struct posix_clock *, fmode_t) open;
    uint (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    uint (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    uint (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock_context *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock_context *, fmode_t) open;
    __poll_t (*)(struct posix_clock_context *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock_context *) release;
    ssize_t (*)(struct posix_clock_context *, uint, char *, size_t) read;
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
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
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
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct posix_clock_operations {
    struct module * owner;
    int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_gettime;
    int (*)(struct posix_clock *, struct timespec64 *) clock_getres;
    int (*)(struct posix_clock *, const struct timespec64 *) clock_settime;
    long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl;
    int (*)(struct posix_clock *, fmode_t) open;
    __poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll;
    int (*)(struct posix_clock *) release;
    ssize_t (*)(struct posix_clock *, uint, char *, size_t) read;
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
<b>Field removed. </b>
<code>int (*)(struct posix_clock *, struct k_itimer *) timer_create</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct posix_clock *, struct k_itimer *) timer_delete</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct posix_clock *, struct k_itimer *, struct itimerspec *) timer_gettime</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct posix_clock *, struct k_itimer *, int, struct itimerspec *, struct itimerspec *) timer_settime</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct posix_clock *, int, struct file *, int) fasync</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct posix_clock *, struct vm_area_struct *) mmap</code>
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
<b>Field type changed. </b>
<code>int (*)(struct posix_clock *, struct timespec *) clock_gettime</code> ➡️ <code>int (*)(struct posix_clock *, struct timespec64 *) clock_gettime</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct posix_clock *, struct timespec *) clock_getres</code> ➡️ <code>int (*)(struct posix_clock *, struct timespec64 *) clock_getres</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct posix_clock *, const struct timespec *) clock_settime</code> ➡️ <code>int (*)(struct posix_clock *, const struct timespec64 *) clock_settime</code>
</li>
<li>
<b>Field type changed. </b>
<code>uint (*)(struct posix_clock *, struct file *, poll_table *) poll</code> ➡️ <code>__poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll</code>
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
<b>Field type changed. </b>
<code>int (*)(struct posix_clock *, struct timex *) clock_adjtime</code> ➡️ <code>int (*)(struct posix_clock *, struct __kernel_timex *) clock_adjtime</code>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long int (*)(struct posix_clock *, unsigned int, long unsigned int) ioctl</code> ➡️ <code>long int (*)(struct posix_clock_context *, unsigned int, long unsigned int) ioctl</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct posix_clock *, fmode_t) open</code> ➡️ <code>int (*)(struct posix_clock_context *, fmode_t) open</code>
</li>
<li>
<b>Field type changed. </b>
<code>__poll_t (*)(struct posix_clock *, struct file *, poll_table *) poll</code> ➡️ <code>__poll_t (*)(struct posix_clock_context *, struct file *, poll_table *) poll</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct posix_clock *) release</code> ➡️ <code>int (*)(struct posix_clock_context *) release</code>
</li>
<li>
<b>Field type changed. </b>
<code>ssize_t (*)(struct posix_clock *, uint, char *, size_t) read</code> ➡️ <code>ssize_t (*)(struct posix_clock_context *, uint, char *, size_t) read</code>
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
