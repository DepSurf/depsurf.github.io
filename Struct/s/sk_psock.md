# Struct: <code>sk_psock</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct sk_psock_parser parser;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    struct proto * sk_proto;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct callback_head rcu;
    struct work_struct gc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct sk_psock_parser parser;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    struct proto * sk_proto;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct callback_head rcu;
    struct work_struct gc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct sk_psock_parser parser;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    struct proto * sk_proto;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct callback_head rcu;
    struct work_struct gc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct sk_psock_parser parser;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    struct proto * sk_proto;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct callback_head rcu;
    struct work_struct gc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct sk_psock_parser parser;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    struct proto * sk_proto;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct callback_head rcu;
    struct work_struct gc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct strparser strp;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    spinlock_t ingress_lock;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    void (*)(struct sock *) saved_data_ready;
    int (*)(struct sock *, struct sk_psock *, bool) psock_update_sk_prot;
    struct proto * sk_proto;
    struct mutex work_mutex;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct rcu_work rwork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct strparser strp;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    spinlock_t ingress_lock;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    void (*)(struct sock *) saved_data_ready;
    int (*)(struct sock *, struct sk_psock *, bool) psock_update_sk_prot;
    struct proto * sk_proto;
    struct mutex work_mutex;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct rcu_work rwork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct strparser strp;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    spinlock_t ingress_lock;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    void (*)(struct sock *) saved_data_ready;
    int (*)(struct sock *, struct sk_psock *, bool) psock_update_sk_prot;
    struct proto * sk_proto;
    struct mutex work_mutex;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct rcu_work rwork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    bool redir_ingress;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct strparser strp;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    spinlock_t ingress_lock;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *) saved_destroy;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    void (*)(struct sock *) saved_data_ready;
    int (*)(struct sock *, struct sk_psock *, bool) psock_update_sk_prot;
    struct proto * sk_proto;
    struct mutex work_mutex;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct rcu_work rwork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    bool redir_ingress;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct strparser strp;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    spinlock_t ingress_lock;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *) saved_destroy;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    void (*)(struct sock *) saved_data_ready;
    int (*)(struct sock *, struct sk_psock *, bool) psock_update_sk_prot;
    struct proto * sk_proto;
    struct mutex work_mutex;
    struct sk_psock_work_state work_state;
    struct delayed_work work;
    struct rcu_work rwork;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    bool redir_ingress;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct strparser strp;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    spinlock_t ingress_lock;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *) saved_destroy;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    void (*)(struct sock *) saved_data_ready;
    int (*)(struct sock *, struct sk_psock *, bool) psock_update_sk_prot;
    struct proto * sk_proto;
    struct mutex work_mutex;
    struct sk_psock_work_state work_state;
    struct delayed_work work;
    struct sock * sk_pair;
    struct rcu_work rwork;
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
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct sk_psock_parser parser;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    struct proto * sk_proto;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct callback_head rcu;
    struct work_struct gc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct sk_psock_parser parser;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    struct proto * sk_proto;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct callback_head rcu;
    struct work_struct gc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct sk_psock_parser parser;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    struct proto * sk_proto;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct callback_head rcu;
    struct work_struct gc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct sk_psock_parser parser;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    struct proto * sk_proto;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct callback_head rcu;
    struct work_struct gc;
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
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct sk_psock_parser parser;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    struct proto * sk_proto;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct callback_head rcu;
    struct work_struct gc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct sk_psock_parser parser;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    struct proto * sk_proto;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct callback_head rcu;
    struct work_struct gc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct sk_psock_parser parser;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    struct proto * sk_proto;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct callback_head rcu;
    struct work_struct gc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct sk_psock_parser parser;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    struct proto * sk_proto;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct callback_head rcu;
    struct work_struct gc;
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct sk_psock {
    struct sock * sk;
    struct sock * sk_redir;
    u32 apply_bytes;
    u32 cork_bytes;
    u32 eval;
    struct sk_msg * cork;
    struct sk_psock_progs progs;
    struct sk_psock_parser parser;
    struct sk_buff_head ingress_skb;
    struct list_head ingress_msg;
    long unsigned int state;
    struct list_head link;
    spinlock_t link_lock;
    refcount_t refcnt;
    void (*)(struct sock *) saved_unhash;
    void (*)(struct sock *, long int) saved_close;
    void (*)(struct sock *) saved_write_space;
    struct proto * sk_proto;
    struct sk_psock_work_state work_state;
    struct work_struct work;
    struct callback_head rcu;
    struct work_struct gc;
}
```
</details>
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
<code>struct strparser strp</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t ingress_lock</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct sock *) saved_data_ready</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sock *, struct sk_psock *, bool) psock_update_sk_prot</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex work_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>struct rcu_work rwork</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sk_psock_parser parser</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head rcu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct gc</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool redir_ingress</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct sock *) saved_destroy</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct work_struct work</code> ➡️ <code>struct delayed_work work</code>
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
<code>struct sock * sk_pair</code>
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
