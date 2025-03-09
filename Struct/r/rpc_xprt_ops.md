# Struct: <code>rpc_xprt_ops</code>

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
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    void * (*)(struct rpc_task *, size_t) buf_alloc;
    void (*)(void *) buf_free;
    int (*)(struct rpc_task *) send_request;
    void (*)(struct rpc_task *) set_retrans_timeout;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    int (*)(struct svc_serv *, struct net *) bc_up;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    int (*)(struct rpc_task *) send_request;
    void (*)(struct rpc_task *) set_retrans_timeout;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    int (*)(struct svc_serv *, struct net *) bc_up;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    int (*)(struct rpc_task *) send_request;
    void (*)(struct rpc_task *) set_retrans_timeout;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    int (*)(struct svc_serv *, struct net *) bc_up;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    int (*)(struct rpc_task *) send_request;
    void (*)(struct rpc_task *) set_retrans_timeout;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    int (*)(struct svc_serv *, struct net *) bc_up;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    int (*)(struct rpc_task *) send_request;
    void (*)(struct rpc_task *) set_retrans_timeout;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    int (*)(struct svc_serv *, struct net *) bc_up;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    void (*)(struct rpc_rqst *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) set_retrans_timeout;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    void (*)(struct rpc_rqst *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    void (*)(struct rpc_rqst *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
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
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    void (*)(struct rpc_rqst *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    void (*)(struct rpc_rqst *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_xprt *, char *, size_t) get_srcaddr;
    short unsigned int (*)(struct rpc_xprt *) get_srcport;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    int (*)(struct rpc_rqst *, struct xdr_buf *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_xprt *, char *, size_t) get_srcaddr;
    short unsigned int (*)(struct rpc_xprt *) get_srcport;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    int (*)(struct rpc_rqst *, struct xdr_buf *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_xprt *, char *, size_t) get_srcaddr;
    short unsigned int (*)(struct rpc_xprt *) get_srcport;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    int (*)(struct rpc_rqst *, struct xdr_buf *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_xprt *, char *, size_t) get_srcaddr;
    short unsigned int (*)(struct rpc_xprt *) get_srcport;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    int (*)(struct rpc_rqst *, struct xdr_buf *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
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
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    void (*)(struct rpc_rqst *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    void (*)(struct rpc_rqst *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    void (*)(struct rpc_rqst *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    void (*)(struct rpc_rqst *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
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
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    void (*)(struct rpc_rqst *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    void (*)(struct rpc_rqst *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    void (*)(struct rpc_rqst *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    void (*)(struct rpc_rqst *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
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
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    void * (*)(struct rpc_task *, size_t) buf_alloc;
    void (*)(void *) buf_free;
    int (*)(struct rpc_task *) send_request;
    void (*)(struct rpc_task *) set_retrans_timeout;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    int (*)(struct svc_serv *, struct net *) bc_up;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void * (*)(struct rpc_task *, size_t) buf_alloc</code> ➡️ <code>int (*)(struct rpc_task *) buf_alloc</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(void *) buf_free</code> ➡️ <code>void (*)(struct rpc_task *) buf_free</code>
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
<code>void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot</code>
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
<code>void (*)(struct rpc_rqst *) prepare_request</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct svc_serv *, struct net *) bc_up</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct rpc_task *) send_request</code> ➡️ <code>int (*)(struct rpc_rqst *) send_request</code>
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
<code>void (*)(struct rpc_task *) wait_for_reply_request</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int (*)(struct rpc_xprt *) bc_num_slots</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct rpc_task *) set_retrans_timeout</code>
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
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    void (*)(struct rpc_rqst *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct rpc_xprt_ops {
    void (*)(struct rpc_xprt *, size_t, size_t) set_buffer_size;
    int (*)(struct rpc_xprt *, struct rpc_task *) reserve_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) release_xprt;
    void (*)(struct rpc_xprt *, struct rpc_task *) alloc_slot;
    void (*)(struct rpc_xprt *, struct rpc_rqst *) free_slot;
    void (*)(struct rpc_task *) rpcbind;
    void (*)(struct rpc_xprt *, short unsigned int) set_port;
    void (*)(struct rpc_xprt *, struct rpc_task *) connect;
    int (*)(struct rpc_task *) buf_alloc;
    void (*)(struct rpc_task *) buf_free;
    void (*)(struct rpc_rqst *) prepare_request;
    int (*)(struct rpc_rqst *) send_request;
    void (*)(struct rpc_task *) wait_for_reply_request;
    void (*)(struct rpc_xprt *, struct rpc_task *) timer;
    void (*)(struct rpc_task *) release_request;
    void (*)(struct rpc_xprt *) close;
    void (*)(struct rpc_xprt *) destroy;
    void (*)(struct rpc_xprt *, long unsigned int, long unsigned int) set_connect_timeout;
    void (*)(struct rpc_xprt *, struct seq_file *) print_stats;
    int (*)(struct rpc_xprt *) enable_swap;
    void (*)(struct rpc_xprt *) disable_swap;
    void (*)(struct rpc_xprt *) inject_disconnect;
    int (*)(struct rpc_xprt *, unsigned int) bc_setup;
    size_t (*)(struct rpc_xprt *) bc_maxpayload;
    unsigned int (*)(struct rpc_xprt *) bc_num_slots;
    void (*)(struct rpc_rqst *) bc_free_rqst;
    void (*)(struct rpc_xprt *, unsigned int) bc_destroy;
}
```
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
<code>int (*)(struct rpc_xprt *, char *, size_t) get_srcaddr</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int (*)(struct rpc_xprt *) get_srcport</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct rpc_rqst *) prepare_request</code> ➡️ <code>int (*)(struct rpc_rqst *, struct xdr_buf *) prepare_request</code>
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
