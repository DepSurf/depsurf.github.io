# Struct: <code>k_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec *) clock_getres;
    int (*)(const clockid_t, const struct timespec *) clock_set;
    int (*)(const clockid_t, struct timespec *) clock_get;
    int (*)(const clockid_t, struct timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, struct timespec *, struct timespec *) nsleep;
    long int (*)(struct restart_block *) nsleep_restart;
    int (*)(struct k_itimer *, int, struct itimerspec *, struct itimerspec *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec *) timer_get;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec *) clock_getres;
    int (*)(const clockid_t, const struct timespec *) clock_set;
    int (*)(const clockid_t, struct timespec *) clock_get;
    int (*)(const clockid_t, struct timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, struct timespec *, struct timespec *) nsleep;
    long int (*)(struct restart_block *) nsleep_restart;
    int (*)(struct k_itimer *, int, struct itimerspec *, struct itimerspec *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec *) timer_get;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec *) clock_getres;
    int (*)(const clockid_t, const struct timespec *) clock_set;
    int (*)(const clockid_t, struct timespec *) clock_get;
    int (*)(const clockid_t, struct timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, struct timespec *, struct timespec *) nsleep;
    long int (*)(struct restart_block *) nsleep_restart;
    int (*)(struct k_itimer *, int, struct itimerspec *, struct itimerspec *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec *) timer_get;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec *) clock_getres;
    int (*)(const clockid_t, const struct timespec *) clock_set;
    int (*)(const clockid_t, struct timespec *) clock_get;
    int (*)(const clockid_t, struct timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec *, struct itimerspec *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    int (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec *) clock_getres;
    int (*)(const clockid_t, const struct timespec *) clock_set;
    int (*)(const clockid_t, struct timespec *) clock_get;
    int (*)(const clockid_t, struct timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec *, struct itimerspec *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    int (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get;
    int (*)(const clockid_t, struct timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get;
    int (*)(const clockid_t, struct timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get_timespec;
    ktime_t (*)(const clockid_t) clock_get_ktime;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get_timespec;
    ktime_t (*)(const clockid_t) clock_get_ktime;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get_timespec;
    ktime_t (*)(const clockid_t) clock_get_ktime;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get_timespec;
    ktime_t (*)(const clockid_t) clock_get_ktime;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get_timespec;
    ktime_t (*)(const clockid_t) clock_get_ktime;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get_timespec;
    ktime_t (*)(const clockid_t) clock_get_ktime;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get_timespec;
    ktime_t (*)(const clockid_t) clock_get_ktime;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get_timespec;
    ktime_t (*)(const clockid_t) clock_get_ktime;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
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
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
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
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct k_clock {
    int (*)(const clockid_t, struct timespec64 *) clock_getres;
    int (*)(const clockid_t, const struct timespec64 *) clock_set;
    int (*)(const clockid_t, struct timespec64 *) clock_get;
    int (*)(const clockid_t, struct __kernel_timex *) clock_adj;
    int (*)(struct k_itimer *) timer_create;
    int (*)(const clockid_t, int, const struct timespec64 *) nsleep;
    int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set;
    int (*)(struct k_itimer *) timer_del;
    void (*)(struct k_itimer *, struct itimerspec64 *) timer_get;
    void (*)(struct k_itimer *) timer_rearm;
    s64 (*)(struct k_itimer *, ktime_t) timer_forward;
    ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining;
    int (*)(struct k_itimer *) timer_try_to_cancel;
    void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm;
    void (*)(struct k_itimer *) timer_wait_running;
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
<code>void (*)(struct k_itimer *) timer_rearm</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct k_itimer *, ktime_t) timer_forward</code>
</li>
<li>
<b>Field added. </b>
<code>ktime_t (*)(struct k_itimer *, ktime_t) timer_remaining</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct k_itimer *) timer_try_to_cancel</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct k_itimer *, ktime_t, bool, bool) timer_arm</code>
</li>
<li>
<b>Field removed. </b>
<code>long int (*)(struct restart_block *) nsleep_restart</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(const clockid_t, int, struct timespec *, struct timespec *) nsleep</code> ➡️ <code>int (*)(const clockid_t, int, const struct timespec *) nsleep</code>
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
<code>int (*)(const clockid_t, struct timespec *) clock_getres</code> ➡️ <code>int (*)(const clockid_t, struct timespec64 *) clock_getres</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(const clockid_t, const struct timespec *) clock_set</code> ➡️ <code>int (*)(const clockid_t, const struct timespec64 *) clock_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(const clockid_t, struct timespec *) clock_get</code> ➡️ <code>int (*)(const clockid_t, struct timespec64 *) clock_get</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(const clockid_t, int, const struct timespec *) nsleep</code> ➡️ <code>int (*)(const clockid_t, int, const struct timespec64 *) nsleep</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct k_itimer *, int, struct itimerspec *, struct itimerspec *) timer_set</code> ➡️ <code>int (*)(struct k_itimer *, int, struct itimerspec64 *, struct itimerspec64 *) timer_set</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct k_itimer *, struct itimerspec *) timer_get</code> ➡️ <code>void (*)(struct k_itimer *, struct itimerspec64 *) timer_get</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct k_itimer *, ktime_t) timer_forward</code> ➡️ <code>s64 (*)(struct k_itimer *, ktime_t) timer_forward</code>
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
<code>int (*)(const clockid_t, struct timex *) clock_adj</code> ➡️ <code>int (*)(const clockid_t, struct __kernel_timex *) clock_adj</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct k_itimer *) timer_wait_running</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(const clockid_t, struct timespec64 *) clock_get_timespec</code>
</li>
<li>
<b>Field added. </b>
<code>ktime_t (*)(const clockid_t) clock_get_ktime</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(const clockid_t, struct timespec64 *) clock_get</code>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
