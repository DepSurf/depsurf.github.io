# Struct: <code>netfront_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct bpf_prog * xdp_prog;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
    struct page_pool * page_pool;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct bpf_prog * xdp_prog;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
    struct page_pool * page_pool;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct bpf_prog * xdp_prog;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    struct sk_buff *[256] tx_skbs;
    short unsigned int[256] tx_link;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    unsigned int tx_pend_queue;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
    unsigned int rx_rsp_unconsumed;
    spinlock_t rx_cons_lock;
    struct page_pool * page_pool;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct bpf_prog * xdp_prog;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    struct sk_buff *[256] tx_skbs;
    short unsigned int[256] tx_link;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    unsigned int tx_pend_queue;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
    unsigned int rx_rsp_unconsumed;
    spinlock_t rx_cons_lock;
    struct page_pool * page_pool;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct bpf_prog * xdp_prog;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    struct sk_buff *[256] tx_skbs;
    short unsigned int[256] tx_link;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    unsigned int tx_pend_queue;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
    unsigned int rx_rsp_unconsumed;
    spinlock_t rx_cons_lock;
    struct page_pool * page_pool;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct bpf_prog * xdp_prog;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    struct sk_buff *[256] tx_skbs;
    short unsigned int[256] tx_link;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    unsigned int tx_pend_queue;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
    unsigned int rx_rsp_unconsumed;
    spinlock_t rx_cons_lock;
    struct page_pool * page_pool;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct bpf_prog * xdp_prog;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    struct sk_buff *[256] tx_skbs;
    short unsigned int[256] tx_link;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    unsigned int tx_pend_queue;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
    unsigned int rx_rsp_unconsumed;
    spinlock_t rx_cons_lock;
    struct page_pool * page_pool;
    struct xdp_rxq_info xdp_rxq;
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
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
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
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
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
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct bpf_prog * xdp_prog</code>
</li>
<li>
<b>Field added. </b>
<code>struct page_pool * page_pool</code>
</li>
<li>
<b>Field added. </b>
<code>struct xdp_rxq_info xdp_rxq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>short unsigned int[256] tx_link</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int tx_pend_queue</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int rx_rsp_unconsumed</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t rx_cons_lock</code>
</li>
<li>
<b>Field type changed. </b>
<code>union skb_entry[256] tx_skbs</code> ➡️ <code>struct sk_buff *[256] tx_skbs</code>
</li>
</ul>
</details>
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
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
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
struct netfront_queue {
    unsigned int id;
    char[22] name;
    struct netfront_info * info;
    struct napi_struct napi;
    unsigned int tx_evtchn;
    unsigned int rx_evtchn;
    unsigned int tx_irq;
    unsigned int rx_irq;
    char[25] tx_irq_name;
    char[25] rx_irq_name;
    spinlock_t tx_lock;
    struct xen_netif_tx_front_ring tx;
    int tx_ring_ref;
    union skb_entry[256] tx_skbs;
    grant_ref_t gref_tx_head;
    grant_ref_t[256] grant_tx_ref;
    struct page *[256] grant_tx_page;
    unsigned int tx_skb_freelist;
    spinlock_t rx_lock;
    struct xen_netif_rx_front_ring rx;
    int rx_ring_ref;
    struct timer_list rx_refill_timer;
    struct sk_buff *[256] rx_skbs;
    grant_ref_t gref_rx_head;
    grant_ref_t[256] grant_rx_ref;
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
