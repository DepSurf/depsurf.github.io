# Struct: <code>proto</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    void (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    void (*)(struct sock *, int) clear_sk;
    unsigned int inuse_idx;
    bool (*)(const struct sock *) stream_memory_free;
    void (*)(struct sock *) enter_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    int slab_flags;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct mem_cgroup *, struct cgroup_subsys *) init_cgroup;
    void (*)(struct mem_cgroup *) destroy_cgroup;
    struct cg_proto * (*)(struct mem_cgroup *) proto_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    void (*)(struct sock *, int) clear_sk;
    unsigned int inuse_idx;
    bool (*)(const struct sock *) stream_memory_free;
    void (*)(struct sock *) enter_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    int slab_flags;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *) stream_memory_free;
    void (*)(struct sock *) enter_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    int slab_flags;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *) stream_memory_free;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    int slab_flags;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *) stream_memory_free;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *) stream_memory_free;
    bool (*)(const struct sock *) stream_memory_read;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(const struct sock *) stream_memory_read;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(const struct sock *) stream_memory_read;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(const struct sock *) stream_memory_read;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sockaddr *, int) bind_add;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(const struct sock *) stream_memory_read;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sockaddr *, int) bind_add;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(const struct sock *) stream_memory_read;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sockaddr *, int) bind_add;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    bool (*)(int, int) bpf_bypass_getsockopt;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    int (*)(struct sock *, struct sk_psock *, bool) psock_update_sk_prot;
    unsigned int inuse_idx;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(const struct sock *) stream_memory_read;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sockaddr *, int) bind_add;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    bool (*)(int, int) bpf_bypass_getsockopt;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    int (*)(struct sock *, struct sk_psock *, bool) psock_update_sk_prot;
    unsigned int inuse_idx;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(struct sock *) sock_is_readable;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    unsigned int * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sockaddr *, int) bind_add;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    bool (*)(int, int) bpf_bypass_getsockopt;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    void (*)(struct sock *) put_port;
    int (*)(struct sock *, struct sk_psock *, bool) psock_update_sk_prot;
    unsigned int inuse_idx;
    int (*)(const struct sock *) forward_alloc_get;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(struct sock *) sock_is_readable;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    unsigned int * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sockaddr *, int) bind_add;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    bool (*)(int, int) bpf_bypass_getsockopt;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    void (*)(struct sock *) put_port;
    int (*)(struct sock *, struct sk_psock *, bool) psock_update_sk_prot;
    unsigned int inuse_idx;
    int (*)(const struct sock *) forward_alloc_get;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(struct sock *) sock_is_readable;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    int * per_cpu_fw_alloc;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    unsigned int * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, int *) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int *) recvmsg;
    void (*)(struct socket *) splice_eof;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sockaddr *, int) bind_add;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    bool (*)(int, int) bpf_bypass_getsockopt;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    void (*)(struct sock *) put_port;
    int (*)(struct sock *, struct sk_psock *, bool) psock_update_sk_prot;
    unsigned int inuse_idx;
    int (*)(const struct sock *) forward_alloc_get;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(struct sock *) sock_is_readable;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    int * per_cpu_fw_alloc;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    unsigned int ipv6_pinfo_offset;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    unsigned int * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, int *) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int *) recvmsg;
    void (*)(struct socket *) splice_eof;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sockaddr *, int) bind_add;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    bool (*)(int, int) bpf_bypass_getsockopt;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    void (*)(struct sock *) put_port;
    int (*)(struct sock *, struct sk_psock *, bool) psock_update_sk_prot;
    unsigned int inuse_idx;
    int (*)(const struct sock *) forward_alloc_get;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(struct sock *) sock_is_readable;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    int * per_cpu_fw_alloc;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    unsigned int ipv6_pinfo_offset;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    unsigned int * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
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
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(const struct sock *) stream_memory_read;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(const struct sock *) stream_memory_read;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(const struct sock *) stream_memory_read;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(const struct sock *) stream_memory_read;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
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
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(const struct sock *) stream_memory_read;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(const struct sock *) stream_memory_read;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(const struct sock *) stream_memory_read;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct proto {
    void (*)(struct sock *, long int) close;
    int (*)(struct sock *, struct sockaddr *, int) pre_connect;
    int (*)(struct sock *, struct sockaddr *, int) connect;
    int (*)(struct sock *, int) disconnect;
    struct sock * (*)(struct sock *, int, int *, bool) accept;
    int (*)(struct sock *, int, long unsigned int) ioctl;
    int (*)(struct sock *) init;
    void (*)(struct sock *) destroy;
    void (*)(struct sock *, int) shutdown;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, int) keepalive;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg;
    int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage;
    int (*)(struct sock *, struct sockaddr *, int) bind;
    int (*)(struct sock *, struct sk_buff *) backlog_rcv;
    void (*)(struct sock *) release_cb;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    void (*)(struct sock *) rehash;
    int (*)(struct sock *, short unsigned int) get_port;
    unsigned int inuse_idx;
    bool (*)(const struct sock *, int) stream_memory_free;
    bool (*)(const struct sock *) stream_memory_read;
    void (*)(struct sock *) enter_memory_pressure;
    void (*)(struct sock *) leave_memory_pressure;
    atomic_long_t * memory_allocated;
    struct percpu_counter * sockets_allocated;
    long unsigned int * memory_pressure;
    long int * sysctl_mem;
    int * sysctl_wmem;
    int * sysctl_rmem;
    u32 sysctl_wmem_offset;
    u32 sysctl_rmem_offset;
    int max_header;
    bool no_autobind;
    struct kmem_cache * slab;
    unsigned int obj_size;
    slab_flags_t slab_flags;
    unsigned int useroffset;
    unsigned int usersize;
    struct percpu_counter * orphan_count;
    struct request_sock_ops * rsk_prot;
    struct timewait_sock_ops * twsk_prot;
    union (anon) h;
    struct module * owner;
    char[32] name;
    struct list_head node;
    int (*)(struct sock *, int) diag_destroy;
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
<code>int (*)(struct sock *, int) diag_destroy</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct mem_cgroup *, struct cgroup_subsys *) init_cgroup</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mem_cgroup *) destroy_cgroup</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cg_proto * (*)(struct mem_cgroup *) proto_cgroup</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct sock *) hash</code> ➡️ <code>int (*)(struct sock *) hash</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void (*)(struct sock *, int) clear_sk</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct sock *, int) keepalive</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct sock *) leave_memory_pressure</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct sock * (*)(struct sock *, int, int *) accept</code> ➡️ <code>struct sock * (*)(struct sock *, int, int *, bool) accept</code>
</li>
<li>
<b>Field type changed. </b>
<code>int * memory_pressure</code> ➡️ <code>long unsigned int * memory_pressure</code>
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
<code>u32 sysctl_wmem_offset</code>
</li>
<li>
<b>Field added. </b>
<code>u32 sysctl_rmem_offset</code>
</li>
<li>
<b>Field type changed. </b>
<code>int slab_flags</code> ➡️ <code>slab_flags_t slab_flags</code>
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
<code>int (*)(struct sock *, struct sockaddr *, int) pre_connect</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(const struct sock *) stream_memory_read</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int useroffset</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int usersize</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>bool (*)(const struct sock *) stream_memory_free</code> ➡️ <code>bool (*)(const struct sock *, int) stream_memory_free</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct sock *, struct sockaddr *, int) bind_add</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, int, int, char *, int *) compat_getsockopt</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct sock *, int, int, char *, unsigned int) setsockopt</code> ➡️ <code>int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool (*)(int, int) bpf_bypass_getsockopt</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sock *, struct sk_psock *, bool) psock_update_sk_prot</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool (*)(struct sock *) sock_is_readable</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(const struct sock *) stream_memory_read</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct percpu_counter * orphan_count</code> ➡️ <code>unsigned int * orphan_count</code>
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
<code>void (*)(struct sock *) put_port</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(const struct sock *) forward_alloc_get</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct sock *, struct msghdr *, size_t, int, int, int *) recvmsg</code> ➡️ <code>int (*)(struct sock *, struct msghdr *, size_t, int, int *) recvmsg</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int * per_cpu_fw_alloc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct socket *) splice_eof</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int ipv6_pinfo_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, struct page *, int, size_t, int) sendpage</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct sock *, int, long unsigned int) ioctl</code> ➡️ <code>int (*)(struct sock *, int, int *) ioctl</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, int, int, char *, int *) compat_getsockopt</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, int, int, char *, int *) compat_getsockopt</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, unsigned int, long unsigned int) compat_ioctl</code>
</li>
</ul>
</details>
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
