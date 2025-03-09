# Struct: <code>skb_shared_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    unsigned char nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    short unsigned int gso_type;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    u32 tskey;
    __be32 ip6_frag_id;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    unsigned char nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    short unsigned int gso_type;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    u32 tskey;
    __be32 ip6_frag_id;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    unsigned char nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    short unsigned int gso_type;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    u32 tskey;
    __be32 ip6_frag_id;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    short unsigned int _unused;
    unsigned char nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    __be32 ip6_frag_id;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 __unused;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 __unused;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 __unused;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 __unused;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 __unused;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 __unused;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 __unused;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 flags;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 flags;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 flags;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    unsigned int xdp_frags_size;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 flags;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    unsigned int xdp_frags_size;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 flags;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    unsigned int xdp_frags_size;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 flags;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    struct xsk_tx_metadata_compl xsk_meta;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    unsigned int xdp_frags_size;
    void * destructor_arg;
    skb_frag_t[17] frags;
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
struct skb_shared_info {
    __u8 __unused;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 __unused;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 __unused;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[16] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 __unused;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
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
struct skb_shared_info {
    __u8 __unused;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 __unused;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 __unused;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct skb_shared_info {
    __u8 __unused;
    __u8 meta_len;
    __u8 nr_frags;
    __u8 tx_flags;
    short unsigned int gso_size;
    short unsigned int gso_segs;
    struct sk_buff * frag_list;
    struct skb_shared_hwtstamps hwtstamps;
    unsigned int gso_type;
    u32 tskey;
    atomic_t dataref;
    void * destructor_arg;
    skb_frag_t[17] frags;
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
<code>short unsigned int _unused</code>
</li>
<li>
<b>Field type changed. </b>
<code>short unsigned int gso_type</code> ➡️ <code>unsigned int gso_type</code>
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
<code>__u8 __unused</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 meta_len</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int _unused</code>
</li>
<li>
<b>Field removed. </b>
<code>__be32 ip6_frag_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned char nr_frags</code> ➡️ <code>__u8 nr_frags</code>
</li>
</ul>
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u8 flags</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 __unused</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int xdp_frags_size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct xsk_tx_metadata_compl xsk_meta</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>skb_frag_t[17] frags</code> ➡️ <code>skb_frag_t[16] frags</code>
</li>
</ul>
</details>
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
