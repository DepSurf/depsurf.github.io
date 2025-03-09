# Struct: <code>tun_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct socket_wq wq;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct list_head next;
    struct tun_struct * detached;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct socket_wq wq;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct list_head next;
    struct tun_struct * detached;
    struct skb_array tx_array;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct socket_wq wq;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct list_head next;
    struct tun_struct * detached;
    struct skb_array tx_array;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct socket_wq wq;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct list_head next;
    struct tun_struct * detached;
    struct skb_array tx_array;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct socket_wq wq;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct skb_array tx_array;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct socket_wq wq;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct socket_wq wq;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
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
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
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
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tun_file {
    struct sock sk;
    struct socket socket;
    struct tun_struct * tun;
    struct fasync_struct * fasync;
    unsigned int flags;
    u16 queue_index;
    unsigned int ifindex;
    struct napi_struct napi;
    bool napi_enabled;
    bool napi_frags_enabled;
    struct mutex napi_mutex;
    struct list_head next;
    struct tun_struct * detached;
    struct ptr_ring tx_ring;
    struct xdp_rxq_info xdp_rxq;
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
<code>struct skb_array tx_array</code>
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct napi_struct napi</code>
</li>
<li>
<b>Field added. </b>
<code>bool napi_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex napi_mutex</code>
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
<code>struct ptr_ring tx_ring</code>
</li>
<li>
<b>Field added. </b>
<code>struct xdp_rxq_info xdp_rxq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct skb_array tx_array</code>
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
<code>bool napi_frags_enabled</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct socket_wq wq</code>
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
