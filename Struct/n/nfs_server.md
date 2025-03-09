# Struct: <code>nfs_server</code>

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
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    struct backing_dev_info backing_dev_info;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    struct backing_dev_info backing_dev_info;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
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
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    unsigned int flags;
    unsigned int fattr_valid;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int gxasize;
    unsigned int sxasize;
    unsigned int lxasize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    enum nfs4_change_attr_type change_attr_type;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec64 time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
    bool has_sec_mnt_opts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    unsigned int flags;
    unsigned int fattr_valid;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int gxasize;
    unsigned int sxasize;
    unsigned int lxasize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    enum nfs4_change_attr_type change_attr_type;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec64 time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
    bool has_sec_mnt_opts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    unsigned int write_congested;
    unsigned int flags;
    unsigned int fattr_valid;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int gxasize;
    unsigned int sxasize;
    unsigned int lxasize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    enum nfs4_change_attr_type change_attr_type;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec64 time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct fscache_volume * fscache;
    char * fscache_uniq;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
    bool has_sec_mnt_opts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    unsigned int write_congested;
    unsigned int flags;
    unsigned int fattr_valid;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int gxasize;
    unsigned int sxasize;
    unsigned int lxasize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    enum nfs4_change_attr_type change_attr_type;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec64 time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct fscache_volume * fscache;
    char * fscache_uniq;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
    bool has_sec_mnt_opts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    unsigned int write_congested;
    unsigned int flags;
    unsigned int fattr_valid;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int gxasize;
    unsigned int sxasize;
    unsigned int lxasize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    enum nfs4_change_attr_type change_attr_type;
    struct nfs_fsid fsid;
    int s_sysfs_id;
    __u64 maxfilesize;
    struct timespec64 time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct fscache_volume * fscache;
    char * fscache_uniq;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
    bool has_sec_mnt_opts;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    unsigned int write_congested;
    unsigned int flags;
    unsigned int fattr_valid;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int gxasize;
    unsigned int sxasize;
    unsigned int lxasize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    enum nfs4_change_attr_type change_attr_type;
    struct nfs_fsid fsid;
    int s_sysfs_id;
    __u64 maxfilesize;
    struct timespec64 time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct fscache_volume * fscache;
    char * fscache_uniq;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int delegation_gen;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
    bool has_sec_mnt_opts;
    struct kobject kobj;
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
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
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
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
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
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    struct backing_dev_info backing_dev_info;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
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
<code>struct rpc_wait_queue uoc_rpcwaitq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct backing_dev_info backing_dev_info</code>
</li>
</ul>
</details>
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
<code>struct list_head ss_copies</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int read_hdrsize</code>
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
<code>const struct cred * cred</code>
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
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    int flags;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct nfs_server {
    struct nfs_client * nfs_client;
    struct list_head client_link;
    struct list_head master_link;
    struct rpc_clnt * client;
    struct rpc_clnt * client_acl;
    struct nlm_host * nlm_host;
    struct nfs_iostats * io_stats;
    atomic_long_t writeback;
    unsigned int flags;
    unsigned int fattr_valid;
    unsigned int caps;
    unsigned int rsize;
    unsigned int rpages;
    unsigned int wsize;
    unsigned int wpages;
    unsigned int wtmult;
    unsigned int dtsize;
    short unsigned int port;
    unsigned int bsize;
    unsigned int gxasize;
    unsigned int sxasize;
    unsigned int lxasize;
    unsigned int acregmin;
    unsigned int acregmax;
    unsigned int acdirmin;
    unsigned int acdirmax;
    unsigned int namelen;
    unsigned int options;
    unsigned int clone_blksize;
    enum nfs4_change_attr_type change_attr_type;
    struct nfs_fsid fsid;
    __u64 maxfilesize;
    struct timespec64 time_delta;
    long unsigned int mount_time;
    struct super_block * super;
    dev_t s_dev;
    struct nfs_auth_info auth_info;
    struct nfs_fscache_key * fscache_key;
    struct fscache_cookie * fscache;
    u32 pnfs_blksize;
    u32[3] attr_bitmask;
    u32[3] attr_bitmask_nl;
    u32[3] exclcreat_bitmask;
    u32[3] cache_consistency_bitmask;
    u32 acl_bitmask;
    u32 fh_expire_type;
    struct pnfs_layoutdriver_type * pnfs_curr_ld;
    struct rpc_wait_queue roc_rpcwaitq;
    void * pnfs_ld_data;
    struct rb_root state_owners;
    struct ida openowner_id;
    struct ida lockowner_id;
    struct list_head state_owners_lru;
    struct list_head layouts;
    struct list_head delegations;
    struct list_head ss_copies;
    long unsigned int mig_gen;
    long unsigned int mig_status;
    void (*)(struct nfs_server *) destroy;
    atomic_t active;
    struct __kernel_sockaddr_storage mountd_address;
    size_t mountd_addrlen;
    u32 mountd_version;
    short unsigned int mountd_port;
    short unsigned int mountd_protocol;
    struct rpc_wait_queue uoc_rpcwaitq;
    unsigned int read_hdrsize;
    const struct cred * cred;
    bool has_sec_mnt_opts;
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
<code>unsigned int write_congested</code>
</li>
<li>
<b>Field added. </b>
<code>char * fscache_uniq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nfs_fscache_key * fscache_key</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fscache_cookie * fscache</code> ➡️ <code>struct fscache_volume * fscache</code>
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
<code>int s_sysfs_id</code>
</li>
<li>
<b>Field added. </b>
<code>struct kobject kobj</code>
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
<code>long unsigned int delegation_gen</code>
</li>
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
