# Struct: <code>rpc_xprt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    unsigned int tsh_size;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    atomic_t num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int max_reconnect_timeout;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    int bc_alloc_count;
    atomic_t bc_free_slots;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct list_head recv;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    unsigned int tsh_size;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    atomic_t num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int max_reconnect_timeout;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    int bc_alloc_count;
    atomic_t bc_free_slots;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct list_head recv;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    unsigned int tsh_size;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    atomic_t num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    int bc_alloc_count;
    atomic_t bc_free_slots;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct list_head recv;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    unsigned int tsh_size;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    atomic_t num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t recv_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    int bc_alloc_count;
    atomic_t bc_free_slots;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct list_head recv;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    unsigned int tsh_size;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t recv_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    int bc_alloc_count;
    atomic_t bc_free_slots;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct list_head recv;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    unsigned int tsh_size;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    int bc_alloc_count;
    atomic_t bc_free_slots;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    unsigned char reuseport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    atomic_long_t xmit_queuelen;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    unsigned int id;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    unsigned char reuseport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    atomic_long_t xmit_queuelen;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    struct callback_head rcu;
    const struct xprt_class * xprt_class;
    struct rpc_sysfs_xprt * xprt_sysfs;
    bool main;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    unsigned int id;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    unsigned char reuseport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    atomic_long_t xmit_queuelen;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    netns_tracker ns_tracker;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    struct callback_head rcu;
    const struct xprt_class * xprt_class;
    struct rpc_sysfs_xprt * xprt_sysfs;
    bool main;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    unsigned int id;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    unsigned char reuseport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    atomic_long_t xmit_queuelen;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    netns_tracker ns_tracker;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    struct callback_head rcu;
    const struct xprt_class * xprt_class;
    struct rpc_sysfs_xprt * xprt_sysfs;
    bool main;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    unsigned int id;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    unsigned char reuseport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    struct xprtsec_parms xprtsec;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    atomic_long_t xmit_queuelen;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    netns_tracker ns_tracker;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    struct callback_head rcu;
    const struct xprt_class * xprt_class;
    struct rpc_sysfs_xprt * xprt_sysfs;
    bool main;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    unsigned int id;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    unsigned char reuseport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    struct xprtsec_parms xprtsec;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    atomic_long_t xmit_queuelen;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    netns_tracker ns_tracker;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    struct callback_head rcu;
    const struct xprt_class * xprt_class;
    struct rpc_sysfs_xprt * xprt_sysfs;
    bool main;
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
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
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
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct rpc_xprt {
    struct kref kref;
    struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    unsigned int tsh_size;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    atomic_t num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int max_reconnect_timeout;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    int bc_alloc_count;
    atomic_t bc_free_slots;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct list_head recv;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
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
<code>long unsigned int connect_timeout</code>
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
<code>spinlock_t recv_lock</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct rpc_xprt_ops * ops</code> ➡️ <code>const struct rpc_xprt_ops * ops</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>atomic_t num_reqs</code> ➡️ <code>unsigned int num_reqs</code>
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
<code>spinlock_t queue_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head xmit_queue</code>
</li>
<li>
<b>Field added. </b>
<code>struct rb_root recv_queue</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t recv_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head recv</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>atomic_long_t queuelen</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int bc_alloc_max</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t bc_slot_count</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int tsh_size</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t bc_free_slots</code>
</li>
<li>
<b>Field type changed. </b>
<code>int bc_alloc_count</code> ➡️ <code>unsigned int bc_alloc_count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct rpc_xprt {
    struct kref kref;
    const struct rpc_xprt_ops * ops;
    const struct rpc_timeout * timeout;
    struct __kernel_sockaddr_storage addr;
    size_t addrlen;
    int prot;
    long unsigned int cong;
    long unsigned int cwnd;
    size_t max_payload;
    struct rpc_wait_queue binding;
    struct rpc_wait_queue sending;
    struct rpc_wait_queue pending;
    struct rpc_wait_queue backlog;
    struct list_head free;
    unsigned int max_reqs;
    unsigned int min_reqs;
    unsigned int num_reqs;
    long unsigned int state;
    unsigned char resvport;
    unsigned char reuseport;
    atomic_t swapper;
    unsigned int bind_index;
    struct list_head xprt_switch;
    long unsigned int bind_timeout;
    long unsigned int reestablish_timeout;
    unsigned int connect_cookie;
    struct work_struct task_cleanup;
    struct timer_list timer;
    long unsigned int last_used;
    long unsigned int idle_timeout;
    long unsigned int connect_timeout;
    long unsigned int max_reconnect_timeout;
    atomic_long_t queuelen;
    spinlock_t transport_lock;
    spinlock_t reserve_lock;
    spinlock_t queue_lock;
    u32 xid;
    struct rpc_task * snd_task;
    struct list_head xmit_queue;
    atomic_long_t xmit_queuelen;
    struct svc_xprt * bc_xprt;
    struct svc_serv * bc_serv;
    unsigned int bc_alloc_max;
    unsigned int bc_alloc_count;
    atomic_t bc_slot_count;
    spinlock_t bc_pa_lock;
    struct list_head bc_pa_list;
    struct rb_root recv_queue;
    struct (anon) stat;
    struct net * xprt_net;
    const char * servername;
    const char *[6] address_strings;
    struct dentry * debugfs;
    atomic_t inject_disconnect;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int id</code>
</li>
<li>
<b>Field added. </b>
<code>const struct xprt_class * xprt_class</code>
</li>
<li>
<b>Field added. </b>
<code>struct rpc_sysfs_xprt * xprt_sysfs</code>
</li>
<li>
<b>Field added. </b>
<code>bool main</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t inject_disconnect</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct svc_serv * bc_serv</code> ➡️ <code>struct svc_serv * bc_serv</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>netns_tracker ns_tracker</code>
</li>
</ul>
</details>
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
<code>struct xprtsec_parms xprtsec</code>
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
