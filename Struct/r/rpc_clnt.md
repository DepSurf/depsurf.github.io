# Struct: <code>rpc_clnt</code>

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
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
    const struct cred * cl_cred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
    const struct cred * cl_cred;
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
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
    struct work_struct cl_work;
    const struct cred * cl_cred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rpc_clnt {
    refcount_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_sysfs_client * cl_sysfs;
    struct rpc_xprt_iter cl_xpi;
    struct work_struct cl_work;
    const struct cred * cl_cred;
    unsigned int cl_max_connect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rpc_clnt {
    refcount_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    atomic_t cl_pid;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_sysfs_client * cl_sysfs;
    struct rpc_xprt_iter cl_xpi;
    struct work_struct cl_work;
    const struct cred * cl_cred;
    unsigned int cl_max_connect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rpc_clnt {
    refcount_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    atomic_t cl_pid;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_sysfs_client * cl_sysfs;
    struct rpc_xprt_iter cl_xpi;
    struct work_struct cl_work;
    const struct cred * cl_cred;
    unsigned int cl_max_connect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rpc_clnt {
    refcount_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    atomic_t cl_pid;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    unsigned int cl_shutdown;
    struct xprtsec_parms cl_xprtsec;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_sysfs_client * cl_sysfs;
    struct rpc_xprt_iter cl_xpi;
    struct work_struct cl_work;
    const struct cred * cl_cred;
    unsigned int cl_max_connect;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rpc_clnt {
    refcount_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    atomic_t cl_pid;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    unsigned int cl_shutdown;
    struct xprtsec_parms cl_xprtsec;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_sysfs_client * cl_sysfs;
    struct rpc_xprt_iter cl_xpi;
    struct work_struct cl_work;
    const struct cred * cl_cred;
    unsigned int cl_max_connect;
    struct super_block * pipefs_sb;
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
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
    const struct cred * cl_cred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
    const struct cred * cl_cred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
    const struct cred * cl_cred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
    const struct cred * cl_cred;
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
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
    const struct cred * cl_cred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
    const struct cred * cl_cred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
    const struct cred * cl_cred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
    const struct cred * cl_cred;
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
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
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
<b>Field type changed. </b>
<code>struct rpc_procinfo * cl_procinfo</code> ➡️ <code>const struct rpc_procinfo * cl_procinfo</code>
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
<code>const char * cl_principal</code>
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
<code>unsigned int cl_softerr</code>
</li>
<li>
<b>Field added. </b>
<code>const struct cred * cl_cred</code>
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
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
    const struct cred * cl_cred;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct rpc_clnt {
    atomic_t cl_count;
    unsigned int cl_clid;
    struct list_head cl_clients;
    struct list_head cl_tasks;
    spinlock_t cl_lock;
    struct rpc_xprt * cl_xprt;
    const struct rpc_procinfo * cl_procinfo;
    u32 cl_prog;
    u32 cl_vers;
    u32 cl_maxproc;
    struct rpc_auth * cl_auth;
    struct rpc_stat * cl_stats;
    struct rpc_iostats * cl_metrics;
    unsigned int cl_softrtry;
    unsigned int cl_softerr;
    unsigned int cl_discrtry;
    unsigned int cl_noretranstimeo;
    unsigned int cl_autobind;
    unsigned int cl_chatty;
    struct rpc_rtt * cl_rtt;
    const struct rpc_timeout * cl_timeout;
    atomic_t cl_swapper;
    int cl_nodelen;
    char[65] cl_nodename;
    struct rpc_pipe_dir_head cl_pipedir_objects;
    struct rpc_clnt * cl_parent;
    struct rpc_rtt cl_rtt_default;
    struct rpc_timeout cl_timeout_default;
    const struct rpc_program * cl_program;
    const char * cl_principal;
    struct dentry * cl_debugfs;
    struct rpc_xprt_iter cl_xpi;
    struct work_struct cl_work;
    const struct cred * cl_cred;
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
<code>struct rpc_sysfs_client * cl_sysfs</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int cl_max_connect</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t cl_count</code> ➡️ <code>refcount_t cl_count</code>
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
<code>atomic_t cl_pid</code>
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
<code>unsigned int cl_shutdown</code>
</li>
<li>
<b>Field added. </b>
<code>struct xprtsec_parms cl_xprtsec</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct rpc_sysfs_client * cl_sysfs</code> ➡️ <code>struct rpc_sysfs_client * cl_sysfs</code>
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
<code>struct super_block * pipefs_sb</code>
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
