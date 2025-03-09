# Struct: <code>nfs_client</code>

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
struct nfs_client {
    atomic_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    struct rpc_cred * cl_machine_cred;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nfs_client {
    atomic_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    struct rpc_cred * cl_machine_cred;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nfs_client {
    atomic_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    struct rpc_cred * cl_machine_cred;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    struct rpc_cred * cl_machine_cred;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    seqcount_t cl_callback_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    struct rpc_cred * cl_machine_cred;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
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
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    unsigned int cl_max_connect;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    unsigned int cl_max_connect;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    unsigned int cl_max_connect;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    unsigned int cl_max_connect;
    const char * cl_principal;
    struct xprtsec_parms cl_xprtsec;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    unsigned int cl_max_connect;
    const char * cl_principal;
    struct xprtsec_parms cl_xprtsec;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
    struct callback_head rcu;
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
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
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
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
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
struct nfs_client {
    atomic_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    struct rpc_cred * cl_machine_cred;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>wait_queue_head_t cl_lock_waitq</code>
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
<b>Field type changed. </b>
<code>atomic_t cl_count</code> ➡️ <code>refcount_t cl_count</code>
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
<code>seqcount_t cl_callback_count</code>
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
<code>const char * cl_principal</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head pending_cb_stateids</code>
</li>
<li>
<b>Field removed. </b>
<code>seqcount_t cl_callback_count</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rpc_cred * cl_machine_cred</code>
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
<code>unsigned int cl_nconnect</code>
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
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct nfs_client {
    refcount_t cl_count;
    atomic_t cl_mds_count;
    int cl_cons_state;
    long unsigned int cl_res_state;
    long unsigned int cl_flags;
    struct __kernel_sockaddr_storage cl_addr;
    size_t cl_addrlen;
    char * cl_hostname;
    char * cl_acceptor;
    struct list_head cl_share_link;
    struct list_head cl_superblocks;
    struct rpc_clnt * cl_rpcclient;
    const struct nfs_rpc_ops * rpc_ops;
    int cl_proto;
    struct nfs_subversion * cl_nfs_mod;
    u32 cl_minorversion;
    unsigned int cl_nconnect;
    const char * cl_principal;
    struct list_head cl_ds_clients;
    u64 cl_clientid;
    nfs4_verifier cl_confirm;
    long unsigned int cl_state;
    spinlock_t cl_lock;
    long unsigned int cl_lease_time;
    long unsigned int cl_last_renewal;
    struct delayed_work cl_renewd;
    struct rpc_wait_queue cl_rpcwaitq;
    struct idmap * cl_idmap;
    const char * cl_owner_id;
    u32 cl_cb_ident;
    const struct nfs4_minor_version_ops * cl_mvops;
    long unsigned int cl_mig_gen;
    struct nfs4_slot_table * cl_slot_tbl;
    u32 cl_seqid;
    u32 cl_exchange_flags;
    struct nfs4_session * cl_session;
    bool cl_preserve_clid;
    struct nfs41_server_owner * cl_serverowner;
    struct nfs41_server_scope * cl_serverscope;
    struct nfs41_impl_id * cl_implid;
    long unsigned int cl_sp4_flags;
    wait_queue_head_t cl_lock_waitq;
    char[48] cl_ipaddr;
    struct fscache_cookie * fscache;
    struct net * cl_net;
    struct list_head pending_cb_stateids;
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
<code>unsigned int cl_max_connect</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct fscache_cookie * fscache</code>
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
<code>struct xprtsec_parms cl_xprtsec</code>
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
<code>struct callback_head rcu</code>
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
