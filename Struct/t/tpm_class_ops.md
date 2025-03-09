# Struct: <code>tpm_class_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    bool (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    bool (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    bool (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    bool (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    int (*)(struct tpm_chip *, int) request_locality;
    void (*)(struct tpm_chip *, int) relinquish_locality;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    bool (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    int (*)(struct tpm_chip *, int) request_locality;
    void (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    bool (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    bool (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    void (*)(struct tpm_chip *, long unsigned int *) update_durations;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    void (*)(struct tpm_chip *, long unsigned int *) update_durations;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    void (*)(struct tpm_chip *, long unsigned int *) update_durations;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    void (*)(struct tpm_chip *, long unsigned int *) update_durations;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    void (*)(struct tpm_chip *, long unsigned int *) update_durations;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    void (*)(struct tpm_chip *, long unsigned int *) update_durations;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    void (*)(struct tpm_chip *, long unsigned int *) update_durations;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    void (*)(struct tpm_chip *, long unsigned int *) update_durations;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
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
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
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
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tpm_class_ops {
    unsigned int flags;
    const u8 req_complete_mask;
    const u8 req_complete_val;
    bool (*)(struct tpm_chip *, u8) req_canceled;
    int (*)(struct tpm_chip *, u8 *, size_t) recv;
    int (*)(struct tpm_chip *, u8 *, size_t) send;
    void (*)(struct tpm_chip *) cancel;
    u8 (*)(struct tpm_chip *) status;
    void (*)(struct tpm_chip *, long unsigned int *) update_timeouts;
    int (*)(struct tpm_chip *) go_idle;
    int (*)(struct tpm_chip *) cmd_ready;
    int (*)(struct tpm_chip *, int) request_locality;
    int (*)(struct tpm_chip *, int) relinquish_locality;
    void (*)(struct tpm_chip *, bool) clk_enable;
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
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
<code>int (*)(struct tpm_chip *, int) request_locality</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct tpm_chip *, int) relinquish_locality</code>
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
<code>void (*)(struct tpm_chip *, bool) clk_enable</code>
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
<code>int (*)(struct tpm_chip *) go_idle</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct tpm_chip *) cmd_ready</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct tpm_chip *, int) relinquish_locality</code> ➡️ <code>int (*)(struct tpm_chip *, int) relinquish_locality</code>
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
<code>bool (*)(struct tpm_chip *, long unsigned int *) update_timeouts</code> ➡️ <code>void (*)(struct tpm_chip *, long unsigned int *) update_timeouts</code>
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
<code>void (*)(struct tpm_chip *, long unsigned int *) update_durations</code>
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
