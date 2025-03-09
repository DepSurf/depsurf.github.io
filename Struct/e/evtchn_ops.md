# Struct: <code>evtchn_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(evtchn_port_t) clear_pending;
    void (*)(evtchn_port_t) set_pending;
    bool (*)(evtchn_port_t) is_pending;
    bool (*)(evtchn_port_t) test_and_set_mask;
    void (*)(evtchn_port_t) mask;
    void (*)(evtchn_port_t) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(evtchn_port_t) setup;
    void (*)(evtchn_port_t, unsigned int) remove;
    void (*)(evtchn_port_t, unsigned int, unsigned int) bind_to_cpu;
    void (*)(evtchn_port_t) clear_pending;
    void (*)(evtchn_port_t) set_pending;
    bool (*)(evtchn_port_t) is_pending;
    void (*)(evtchn_port_t) mask;
    void (*)(evtchn_port_t) unmask;
    void (*)(unsigned int, struct evtchn_loop_ctrl *) handle_events;
    void (*)() resume;
    int (*)(unsigned int) percpu_init;
    int (*)(unsigned int) percpu_deinit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(evtchn_port_t) setup;
    void (*)(evtchn_port_t, unsigned int) remove;
    void (*)(evtchn_port_t, unsigned int, unsigned int) bind_to_cpu;
    void (*)(evtchn_port_t) clear_pending;
    void (*)(evtchn_port_t) set_pending;
    bool (*)(evtchn_port_t) is_pending;
    void (*)(evtchn_port_t) mask;
    void (*)(evtchn_port_t) unmask;
    void (*)(unsigned int, struct evtchn_loop_ctrl *) handle_events;
    void (*)() resume;
    int (*)(unsigned int) percpu_init;
    int (*)(unsigned int) percpu_deinit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(evtchn_port_t) setup;
    void (*)(evtchn_port_t, unsigned int) remove;
    void (*)(evtchn_port_t, unsigned int, unsigned int) bind_to_cpu;
    void (*)(evtchn_port_t) clear_pending;
    void (*)(evtchn_port_t) set_pending;
    bool (*)(evtchn_port_t) is_pending;
    void (*)(evtchn_port_t) mask;
    void (*)(evtchn_port_t) unmask;
    void (*)(unsigned int, struct evtchn_loop_ctrl *) handle_events;
    void (*)() resume;
    int (*)(unsigned int) percpu_init;
    int (*)(unsigned int) percpu_deinit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(evtchn_port_t) setup;
    void (*)(evtchn_port_t, unsigned int) remove;
    void (*)(evtchn_port_t, unsigned int, unsigned int) bind_to_cpu;
    void (*)(evtchn_port_t) clear_pending;
    void (*)(evtchn_port_t) set_pending;
    bool (*)(evtchn_port_t) is_pending;
    void (*)(evtchn_port_t) mask;
    void (*)(evtchn_port_t) unmask;
    void (*)(unsigned int, struct evtchn_loop_ctrl *) handle_events;
    void (*)() resume;
    int (*)(unsigned int) percpu_init;
    int (*)(unsigned int) percpu_deinit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(evtchn_port_t) setup;
    void (*)(evtchn_port_t, unsigned int) remove;
    void (*)(evtchn_port_t, unsigned int, unsigned int) bind_to_cpu;
    void (*)(evtchn_port_t) clear_pending;
    void (*)(evtchn_port_t) set_pending;
    bool (*)(evtchn_port_t) is_pending;
    void (*)(evtchn_port_t) mask;
    void (*)(evtchn_port_t) unmask;
    void (*)(unsigned int, struct evtchn_loop_ctrl *) handle_events;
    void (*)() resume;
    int (*)(unsigned int) percpu_init;
    int (*)(unsigned int) percpu_deinit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(evtchn_port_t) setup;
    void (*)(evtchn_port_t, unsigned int) remove;
    void (*)(evtchn_port_t, unsigned int, unsigned int) bind_to_cpu;
    void (*)(evtchn_port_t) clear_pending;
    void (*)(evtchn_port_t) set_pending;
    bool (*)(evtchn_port_t) is_pending;
    void (*)(evtchn_port_t) mask;
    void (*)(evtchn_port_t) unmask;
    void (*)(unsigned int, struct evtchn_loop_ctrl *) handle_events;
    void (*)() resume;
    int (*)(unsigned int) percpu_init;
    int (*)(unsigned int) percpu_deinit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(evtchn_port_t) setup;
    void (*)(evtchn_port_t, unsigned int) remove;
    void (*)(evtchn_port_t, unsigned int, unsigned int) bind_to_cpu;
    void (*)(evtchn_port_t) clear_pending;
    void (*)(evtchn_port_t) set_pending;
    bool (*)(evtchn_port_t) is_pending;
    void (*)(evtchn_port_t) mask;
    void (*)(evtchn_port_t) unmask;
    void (*)(unsigned int, struct evtchn_loop_ctrl *) handle_events;
    void (*)() resume;
    int (*)(unsigned int) percpu_init;
    int (*)(unsigned int) percpu_deinit;
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
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
}
```
</details>
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
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
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
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(unsigned int) clear_pending</code> ➡️ <code>void (*)(evtchn_port_t) clear_pending</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(unsigned int) set_pending</code> ➡️ <code>void (*)(evtchn_port_t) set_pending</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(unsigned int) is_pending</code> ➡️ <code>bool (*)(evtchn_port_t) is_pending</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(unsigned int) test_and_set_mask</code> ➡️ <code>bool (*)(evtchn_port_t) test_and_set_mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(unsigned int) mask</code> ➡️ <code>void (*)(evtchn_port_t) mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(unsigned int) unmask</code> ➡️ <code>void (*)(evtchn_port_t) unmask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(evtchn_port_t, unsigned int) remove</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(unsigned int) percpu_init</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(unsigned int) percpu_deinit</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(evtchn_port_t) test_and_set_mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct irq_info *) setup</code> ➡️ <code>int (*)(evtchn_port_t) setup</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct irq_info *, unsigned int) bind_to_cpu</code> ➡️ <code>void (*)(evtchn_port_t, unsigned int, unsigned int) bind_to_cpu</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(unsigned int) handle_events</code> ➡️ <code>void (*)(unsigned int, struct evtchn_loop_ctrl *) handle_events</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct evtchn_ops {
    unsigned int (*)() max_channels;
    unsigned int (*)() nr_channels;
    int (*)(struct irq_info *) setup;
    void (*)(struct irq_info *, unsigned int) bind_to_cpu;
    void (*)(unsigned int) clear_pending;
    void (*)(unsigned int) set_pending;
    bool (*)(unsigned int) is_pending;
    bool (*)(unsigned int) test_and_set_mask;
    void (*)(unsigned int) mask;
    void (*)(unsigned int) unmask;
    void (*)(unsigned int) handle_events;
    void (*)() resume;
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
