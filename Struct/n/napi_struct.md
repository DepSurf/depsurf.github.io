# Struct: <code>napi_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    unsigned int gro_count;
    int (*)(struct napi_struct *, int) poll;
    spinlock_t poll_lock;
    int poll_owner;
    struct net_device * dev;
    struct sk_buff * gro_list;
    struct sk_buff * skb;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    unsigned int gro_count;
    int (*)(struct napi_struct *, int) poll;
    spinlock_t poll_lock;
    int poll_owner;
    struct net_device * dev;
    struct sk_buff * gro_list;
    struct sk_buff * skb;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    unsigned int gro_count;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct sk_buff * gro_list;
    struct sk_buff * skb;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    unsigned int gro_count;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct sk_buff * gro_list;
    struct sk_buff * skb;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    unsigned int gro_count;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct sk_buff * gro_list;
    struct sk_buff * skb;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    unsigned int gro_count;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct sk_buff * gro_list;
    struct sk_buff * skb;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    int defer_hard_irqs_count;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    int defer_hard_irqs_count;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    int defer_hard_irqs_count;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
    struct task_struct * thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    int defer_hard_irqs_count;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
    struct task_struct * thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    int defer_hard_irqs_count;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
    struct task_struct * thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    int defer_hard_irqs_count;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
    struct task_struct * thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    int defer_hard_irqs_count;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    int list_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    unsigned int napi_id;
    struct hrtimer timer;
    struct task_struct * thread;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    int defer_hard_irqs_count;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    int list_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    unsigned int napi_id;
    struct hrtimer timer;
    struct task_struct * thread;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    int irq;
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
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
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
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct napi_struct {
    struct list_head poll_list;
    long unsigned int state;
    int weight;
    long unsigned int gro_bitmask;
    int (*)(struct napi_struct *, int) poll;
    int poll_owner;
    struct net_device * dev;
    struct gro_list[8] gro_hash;
    struct sk_buff * skb;
    struct list_head rx_list;
    int rx_count;
    struct hrtimer timer;
    struct list_head dev_list;
    struct hlist_node napi_hash_node;
    unsigned int napi_id;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>spinlock_t poll_lock</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int gro_bitmask</code>
</li>
<li>
<b>Field added. </b>
<code>struct gro_list[8] gro_hash</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int gro_count</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sk_buff * gro_list</code>
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
<b>Field added. </b>
<code>struct list_head rx_list</code>
</li>
<li>
<b>Field added. </b>
<code>int rx_count</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int defer_hard_irqs_count</code>
</li>
</ul>
</details>
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
<code>struct task_struct * thread</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>int list_owner</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int irq</code>
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
