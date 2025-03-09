# Struct: <code>netlink_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct mutex pg_vec_lock;
    struct netlink_ring rx_ring;
    struct netlink_ring tx_ring;
    atomic_t mapped;
    struct rhash_head node;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    long unsigned int flags;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    void (*)(struct sock *, long unsigned int *) netlink_release;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
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
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
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
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct netlink_sock {
    struct sock sk;
    u32 portid;
    u32 dst_portid;
    u32 dst_group;
    u32 flags;
    u32 subscriptions;
    u32 ngroups;
    long unsigned int * groups;
    long unsigned int state;
    size_t max_recvmsg_len;
    wait_queue_head_t wait;
    bool bound;
    bool cb_running;
    int dump_done_errno;
    struct netlink_callback cb;
    struct mutex * cb_mutex;
    struct mutex cb_def_mutex;
    void (*)(struct sk_buff *) netlink_rcv;
    int (*)(struct net *, int) netlink_bind;
    void (*)(struct net *, int) netlink_unbind;
    struct module * module;
    struct rhash_head node;
    struct callback_head rcu;
    struct work_struct work;
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
<b>Field removed. </b>
<code>struct mutex pg_vec_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct netlink_ring rx_ring</code>
</li>
<li>
<b>Field removed. </b>
<code>struct netlink_ring tx_ring</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t mapped</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct work_struct work</code>
</li>
</ul>
</details>
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
<code>int dump_done_errno</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct sock *, long unsigned int *) netlink_release</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 flags</code> ➡️ <code>long unsigned int flags</code>
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
