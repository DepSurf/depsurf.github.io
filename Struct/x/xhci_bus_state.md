# Struct: <code>xhci_bus_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
    struct completion[31] u3exit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
    struct completion[31] u3exit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
    struct completion[31] u3exit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
    struct completion[31] u3exit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
    struct completion[31] u3exit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
    struct completion[31] u3exit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
    struct completion[31] u3exit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int resuming_ports;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int resuming_ports;
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
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
    struct completion[31] u3exit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
    struct completion[31] u3exit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
    struct completion[31] u3exit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
    struct completion[31] u3exit_done;
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
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
    struct completion[31] u3exit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
    struct completion[31] u3exit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
    struct completion[31] u3exit_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xhci_bus_state {
    long unsigned int bus_suspended;
    long unsigned int next_statechange;
    u32 port_c_suspend;
    u32 suspended_ports;
    u32 port_remote_wakeup;
    long unsigned int[31] resume_done;
    long unsigned int resuming_ports;
    long unsigned int rexit_ports;
    struct completion[31] rexit_done;
    struct completion[31] u3exit_done;
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct completion[31] u3exit_done</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int[31] resume_done</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int rexit_ports</code>
</li>
<li>
<b>Field removed. </b>
<code>struct completion[31] rexit_done</code>
</li>
<li>
<b>Field removed. </b>
<code>struct completion[31] u3exit_done</code>
</li>
</ul>
</details>
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
