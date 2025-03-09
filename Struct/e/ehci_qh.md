# Struct: <code>ehci_qh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int exception;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
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
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
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
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
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
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
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
<code>u8 unlink_reason</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int should_be_inactive</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int exception</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct ehci_qh {
    struct ehci_qh_hw * hw;
    dma_addr_t qh_dma;
    union ehci_shadow qh_next;
    struct list_head qtd_list;
    struct list_head intr_node;
    struct ehci_qtd * dummy;
    struct list_head unlink_node;
    struct ehci_per_sched ps;
    unsigned int unlink_cycle;
    u8 qh_state;
    u8 xacterrs;
    u8 unlink_reason;
    u8 gap_uf;
    unsigned int is_out;
    unsigned int clearing_tt;
    unsigned int dequeue_during_giveback;
    unsigned int should_be_inactive;
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
