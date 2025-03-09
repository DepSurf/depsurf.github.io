# Struct: <code>hpet_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct clock_event_device evt;
    unsigned int num;
    int cpu;
    unsigned int irq;
    unsigned int flags;
    char[10] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct clock_event_device evt;
    unsigned int num;
    int cpu;
    unsigned int irq;
    unsigned int flags;
    char[10] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct clock_event_device evt;
    unsigned int num;
    int cpu;
    unsigned int irq;
    unsigned int flags;
    char[10] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct clock_event_device evt;
    unsigned int num;
    int cpu;
    unsigned int irq;
    unsigned int flags;
    char[10] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct clock_event_device evt;
    unsigned int num;
    int cpu;
    unsigned int irq;
    unsigned int flags;
    char[10] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct clock_event_device evt;
    unsigned int num;
    int cpu;
    unsigned int irq;
    unsigned int flags;
    char[10] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct clock_event_device evt;
    unsigned int num;
    int cpu;
    unsigned int irq;
    unsigned int flags;
    char[10] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hpets * hd_hpets</code>
</li>
<li>
<b>Field added. </b>
<code>struct hpet * hd_hpet</code>
</li>
<li>
<b>Field added. </b>
<code>struct hpet_timer * hd_timer</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int hd_ireqfreq</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int hd_irqdata</code>
</li>
<li>
<b>Field added. </b>
<code>wait_queue_head_t hd_waitqueue</code>
</li>
<li>
<b>Field added. </b>
<code>struct fasync_struct * hd_async_queue</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int hd_flags</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int hd_irq</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int hd_hdwirq</code>
</li>
<li>
<b>Field added. </b>
<code>char[7] hd_name</code>
</li>
<li>
<b>Field removed. </b>
<code>struct clock_event_device evt</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int num</code>
</li>
<li>
<b>Field removed. </b>
<code>int cpu</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int irq</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Field removed. </b>
<code>char[10] name</code>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct hpet_dev {
    struct hpets * hd_hpets;
    struct hpet * hd_hpet;
    struct hpet_timer * hd_timer;
    long unsigned int hd_ireqfreq;
    long unsigned int hd_irqdata;
    wait_queue_head_t hd_waitqueue;
    struct fasync_struct * hd_async_queue;
    unsigned int hd_flags;
    unsigned int hd_irq;
    unsigned int hd_hdwirq;
    char[7] hd_name;
}
```
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
