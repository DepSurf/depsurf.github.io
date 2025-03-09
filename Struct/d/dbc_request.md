# Struct: <code>dbc_request</code>

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
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_hcd *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct dbc_ep * dep;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_hcd *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct dbc_ep * dep;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_hcd *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct dbc_ep * dep;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_hcd *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct dbc_ep * dep;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_hcd *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct dbc_ep * dep;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_hcd *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct dbc_ep * dep;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_dbc *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct xhci_dbc * dbc;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_dbc *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct xhci_dbc * dbc;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_dbc *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct xhci_dbc * dbc;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_dbc *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct xhci_dbc * dbc;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_dbc *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct xhci_dbc * dbc;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_dbc *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct xhci_dbc * dbc;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_dbc *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct xhci_dbc * dbc;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
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
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_hcd *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct dbc_ep * dep;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_hcd *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct dbc_ep * dep;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_hcd *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct dbc_ep * dep;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_hcd *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct dbc_ep * dep;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
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
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_hcd *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct dbc_ep * dep;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_hcd *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct dbc_ep * dep;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_hcd *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct dbc_ep * dep;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_hcd *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct dbc_ep * dep;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
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
struct dbc_request {
    void * buf;
    unsigned int length;
    dma_addr_t dma;
    void (*)(struct xhci_hcd *, struct dbc_request *) complete;
    struct list_head list_pool;
    int status;
    unsigned int actual;
    struct dbc_ep * dep;
    struct list_head list_pending;
    dma_addr_t trb_dma;
    union xhci_trb * trb;
    unsigned int direction;
}
```
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct xhci_dbc * dbc</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dbc_ep * dep</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct xhci_hcd *, struct dbc_request *) complete</code> ➡️ <code>void (*)(struct xhci_dbc *, struct dbc_request *) complete</code>
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
