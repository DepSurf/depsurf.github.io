# Struct: <code>svc_rqst</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct svc_rqst {
    struct list_head rq_all;
    struct callback_head rq_rcu_head;
    struct svc_xprt * rq_xprt;
    struct __kernel_sockaddr_storage rq_addr;
    size_t rq_addrlen;
    struct __kernel_sockaddr_storage rq_daddr;
    size_t rq_daddrlen;
    struct svc_serv * rq_server;
    struct svc_pool * rq_pool;
    const struct svc_procedure * rq_procinfo;
    struct auth_ops * rq_authop;
    struct svc_cred rq_cred;
    void * rq_xprt_ctxt;
    struct svc_deferred_req * rq_deferred;
    size_t rq_xprt_hlen;
    struct xdr_buf rq_arg;
    struct xdr_stream rq_arg_stream;
    struct xdr_stream rq_res_stream;
    struct page * rq_scratch_page;
    struct xdr_buf rq_res;
    struct page *[260] rq_pages;
    struct page * * rq_respages;
    struct page * * rq_next_page;
    struct page * * rq_page_end;
    struct pagevec rq_pvec;
    struct kvec[259] rq_vec;
    struct bio_vec[259] rq_bvec;
    __be32 rq_xid;
    u32 rq_prog;
    u32 rq_vers;
    u32 rq_proc;
    u32 rq_prot;
    int rq_cachetype;
    long unsigned int rq_flags;
    ktime_t rq_qtime;
    void * rq_argp;
    void * rq_resp;
    void * rq_auth_data;
    __be32 rq_auth_stat;
    int rq_auth_slack;
    int rq_reserved;
    ktime_t rq_stime;
    struct cache_req rq_chandle;
    struct auth_domain * rq_client;
    struct auth_domain * rq_gssclient;
    struct svc_cacherep * rq_cacherep;
    struct task_struct * rq_task;
    spinlock_t rq_lock;
    struct net * rq_bc_net;
    void * * rq_lease_breaker;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct svc_rqst {
    struct list_head rq_all;
    struct callback_head rq_rcu_head;
    struct svc_xprt * rq_xprt;
    struct __kernel_sockaddr_storage rq_addr;
    size_t rq_addrlen;
    struct __kernel_sockaddr_storage rq_daddr;
    size_t rq_daddrlen;
    struct svc_serv * rq_server;
    struct svc_pool * rq_pool;
    const struct svc_procedure * rq_procinfo;
    struct auth_ops * rq_authop;
    struct svc_cred rq_cred;
    void * rq_xprt_ctxt;
    struct svc_deferred_req * rq_deferred;
    struct xdr_buf rq_arg;
    struct xdr_stream rq_arg_stream;
    struct xdr_stream rq_res_stream;
    struct page * rq_scratch_page;
    struct xdr_buf rq_res;
    struct page *[260] rq_pages;
    struct page * * rq_respages;
    struct page * * rq_next_page;
    struct page * * rq_page_end;
    struct pagevec rq_pvec;
    struct kvec[259] rq_vec;
    struct bio_vec[259] rq_bvec;
    __be32 rq_xid;
    u32 rq_prog;
    u32 rq_vers;
    u32 rq_proc;
    u32 rq_prot;
    int rq_cachetype;
    long unsigned int rq_flags;
    ktime_t rq_qtime;
    void * rq_argp;
    void * rq_resp;
    void * rq_auth_data;
    __be32 rq_auth_stat;
    int rq_auth_slack;
    int rq_reserved;
    ktime_t rq_stime;
    struct cache_req rq_chandle;
    struct auth_domain * rq_client;
    struct auth_domain * rq_gssclient;
    struct svc_cacherep * rq_cacherep;
    struct task_struct * rq_task;
    spinlock_t rq_lock;
    struct net * rq_bc_net;
    void * * rq_lease_breaker;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct svc_rqst {
    struct list_head rq_all;
    struct callback_head rq_rcu_head;
    struct svc_xprt * rq_xprt;
    struct __kernel_sockaddr_storage rq_addr;
    size_t rq_addrlen;
    struct __kernel_sockaddr_storage rq_daddr;
    size_t rq_daddrlen;
    struct svc_serv * rq_server;
    struct svc_pool * rq_pool;
    const struct svc_procedure * rq_procinfo;
    struct auth_ops * rq_authop;
    struct svc_cred rq_cred;
    void * rq_xprt_ctxt;
    struct svc_deferred_req * rq_deferred;
    struct xdr_buf rq_arg;
    struct xdr_stream rq_arg_stream;
    struct xdr_stream rq_res_stream;
    struct page * rq_scratch_page;
    struct xdr_buf rq_res;
    struct page *[260] rq_pages;
    struct page * * rq_respages;
    struct page * * rq_next_page;
    struct page * * rq_page_end;
    struct pagevec rq_pvec;
    struct kvec[259] rq_vec;
    struct bio_vec[259] rq_bvec;
    __be32 rq_xid;
    u32 rq_prog;
    u32 rq_vers;
    u32 rq_proc;
    u32 rq_prot;
    int rq_cachetype;
    long unsigned int rq_flags;
    ktime_t rq_qtime;
    void * rq_argp;
    void * rq_resp;
    void * rq_auth_data;
    __be32 rq_auth_stat;
    int rq_auth_slack;
    int rq_reserved;
    ktime_t rq_stime;
    struct cache_req rq_chandle;
    struct auth_domain * rq_client;
    struct auth_domain * rq_gssclient;
    struct svc_cacherep * rq_cacherep;
    struct task_struct * rq_task;
    struct net * rq_bc_net;
    void * * rq_lease_breaker;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct svc_rqst {
    struct list_head rq_all;
    struct callback_head rq_rcu_head;
    struct svc_xprt * rq_xprt;
    struct __kernel_sockaddr_storage rq_addr;
    size_t rq_addrlen;
    struct __kernel_sockaddr_storage rq_daddr;
    size_t rq_daddrlen;
    struct svc_serv * rq_server;
    struct svc_pool * rq_pool;
    const struct svc_procedure * rq_procinfo;
    struct auth_ops * rq_authop;
    struct svc_cred rq_cred;
    void * rq_xprt_ctxt;
    struct svc_deferred_req * rq_deferred;
    struct xdr_buf rq_arg;
    struct xdr_stream rq_arg_stream;
    struct xdr_stream rq_res_stream;
    struct page * rq_scratch_page;
    struct xdr_buf rq_res;
    struct page *[260] rq_pages;
    struct page * * rq_respages;
    struct page * * rq_next_page;
    struct page * * rq_page_end;
    struct folio_batch rq_fbatch;
    struct kvec[259] rq_vec;
    struct bio_vec[259] rq_bvec;
    __be32 rq_xid;
    u32 rq_prog;
    u32 rq_vers;
    u32 rq_proc;
    u32 rq_prot;
    int rq_cachetype;
    long unsigned int rq_flags;
    ktime_t rq_qtime;
    void * rq_argp;
    void * rq_resp;
    __be32 * rq_accept_statp;
    void * rq_auth_data;
    __be32 rq_auth_stat;
    int rq_auth_slack;
    int rq_reserved;
    ktime_t rq_stime;
    struct cache_req rq_chandle;
    struct auth_domain * rq_client;
    struct auth_domain * rq_gssclient;
    struct svc_cacherep * rq_cacherep;
    struct task_struct * rq_task;
    struct net * rq_bc_net;
    void * * rq_lease_breaker;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct svc_rqst {
    struct list_head rq_all;
    struct llist_node rq_idle;
    struct callback_head rq_rcu_head;
    struct svc_xprt * rq_xprt;
    struct __kernel_sockaddr_storage rq_addr;
    size_t rq_addrlen;
    struct __kernel_sockaddr_storage rq_daddr;
    size_t rq_daddrlen;
    struct svc_serv * rq_server;
    struct svc_pool * rq_pool;
    const struct svc_procedure * rq_procinfo;
    struct auth_ops * rq_authop;
    struct svc_cred rq_cred;
    void * rq_xprt_ctxt;
    struct svc_deferred_req * rq_deferred;
    struct xdr_buf rq_arg;
    struct xdr_stream rq_arg_stream;
    struct xdr_stream rq_res_stream;
    struct page * rq_scratch_page;
    struct xdr_buf rq_res;
    struct page *[260] rq_pages;
    struct page * * rq_respages;
    struct page * * rq_next_page;
    struct page * * rq_page_end;
    struct folio_batch rq_fbatch;
    struct kvec[259] rq_vec;
    struct bio_vec[259] rq_bvec;
    __be32 rq_xid;
    u32 rq_prog;
    u32 rq_vers;
    u32 rq_proc;
    u32 rq_prot;
    int rq_cachetype;
    long unsigned int rq_flags;
    ktime_t rq_qtime;
    void * rq_argp;
    void * rq_resp;
    __be32 * rq_accept_statp;
    void * rq_auth_data;
    __be32 rq_auth_stat;
    int rq_auth_slack;
    int rq_reserved;
    ktime_t rq_stime;
    struct cache_req rq_chandle;
    struct auth_domain * rq_client;
    struct auth_domain * rq_gssclient;
    struct task_struct * rq_task;
    struct net * rq_bc_net;
    long unsigned int bc_to_initval;
    unsigned int bc_to_retries;
    void * * rq_lease_breaker;
    unsigned int rq_status_counter;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct svc_rqst {
    struct list_head rq_all;
    struct callback_head rq_rcu_head;
    struct svc_xprt * rq_xprt;
    struct __kernel_sockaddr_storage rq_addr;
    size_t rq_addrlen;
    struct __kernel_sockaddr_storage rq_daddr;
    size_t rq_daddrlen;
    struct svc_serv * rq_server;
    struct svc_pool * rq_pool;
    const struct svc_procedure * rq_procinfo;
    struct auth_ops * rq_authop;
    struct svc_cred rq_cred;
    void * rq_xprt_ctxt;
    struct svc_deferred_req * rq_deferred;
    size_t rq_xprt_hlen;
    struct xdr_buf rq_arg;
    struct xdr_stream rq_arg_stream;
    struct xdr_stream rq_res_stream;
    struct page * rq_scratch_page;
    struct xdr_buf rq_res;
    struct page *[260] rq_pages;
    struct page * * rq_respages;
    struct page * * rq_next_page;
    struct page * * rq_page_end;
    struct pagevec rq_pvec;
    struct kvec[259] rq_vec;
    struct bio_vec[259] rq_bvec;
    __be32 rq_xid;
    u32 rq_prog;
    u32 rq_vers;
    u32 rq_proc;
    u32 rq_prot;
    int rq_cachetype;
    long unsigned int rq_flags;
    ktime_t rq_qtime;
    void * rq_argp;
    void * rq_resp;
    void * rq_auth_data;
    __be32 rq_auth_stat;
    int rq_auth_slack;
    int rq_reserved;
    ktime_t rq_stime;
    struct cache_req rq_chandle;
    struct auth_domain * rq_client;
    struct auth_domain * rq_gssclient;
    struct svc_cacherep * rq_cacherep;
    struct task_struct * rq_task;
    spinlock_t rq_lock;
    struct net * rq_bc_net;
    void * * rq_lease_breaker;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>size_t rq_xprt_hlen</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>spinlock_t rq_lock</code>
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
<code>struct folio_batch rq_fbatch</code>
</li>
<li>
<b>Field added. </b>
<code>__be32 * rq_accept_statp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pagevec rq_pvec</code>
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
<code>struct llist_node rq_idle</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int bc_to_initval</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int bc_to_retries</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int rq_status_counter</code>
</li>
<li>
<b>Field removed. </b>
<code>struct svc_cacherep * rq_cacherep</code>
</li>
</ul>
</details>
</li>
</ul>
