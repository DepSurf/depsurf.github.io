# Struct: <code>file_priv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    atomic_t data_pending;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct work;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    atomic_t data_pending;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct work;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    atomic_t data_pending;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct work;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    atomic_t data_pending;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct work;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    atomic_t data_pending;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct work;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    size_t data_pending;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct work;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    size_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    size_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
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
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
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
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct file_priv {
    struct tpm_chip * chip;
    struct tpm_space * space;
    struct mutex buffer_mutex;
    struct timer_list user_read_timer;
    struct work_struct timeout_work;
    struct work_struct async_work;
    wait_queue_head_t async_wait;
    ssize_t response_length;
    bool response_read;
    bool command_enqueued;
    u8[4096] data_buffer;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>atomic_t data_pending</code> ➡️ <code>size_t data_pending</code>
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
<code>struct tpm_space * space</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct timeout_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct async_work</code>
</li>
<li>
<b>Field added. </b>
<code>wait_queue_head_t async_wait</code>
</li>
<li>
<b>Field added. </b>
<code>size_t response_length</code>
</li>
<li>
<b>Field added. </b>
<code>bool response_read</code>
</li>
<li>
<b>Field added. </b>
<code>bool command_enqueued</code>
</li>
<li>
<b>Field removed. </b>
<code>size_t data_pending</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct work</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>size_t response_length</code> ➡️ <code>ssize_t response_length</code>
</li>
</ul>
</details>
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
