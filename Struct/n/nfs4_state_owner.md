# Struct: <code>nfs4_state_owner</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nfs4_state_owner {
    struct nfs_server * so_server;
    struct list_head so_lru;
    long unsigned int so_expires;
    struct rb_node so_server_node;
    const struct cred * so_cred;
    spinlock_t so_lock;
    atomic_t so_count;
    long unsigned int so_flags;
    struct list_head so_states;
    struct nfs_seqid_counter so_seqid;
    seqcount_spinlock_t so_reclaim_seqcount;
    struct mutex so_delegreturn_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nfs4_state_owner {
    struct nfs_server * so_server;
    struct list_head so_lru;
    long unsigned int so_expires;
    struct rb_node so_server_node;
    const struct cred * so_cred;
    spinlock_t so_lock;
    atomic_t so_count;
    long unsigned int so_flags;
    struct list_head so_states;
    struct nfs_seqid_counter so_seqid;
    seqcount_spinlock_t so_reclaim_seqcount;
    struct mutex so_delegreturn_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nfs4_state_owner {
    struct nfs_server * so_server;
    struct list_head so_lru;
    long unsigned int so_expires;
    struct rb_node so_server_node;
    const struct cred * so_cred;
    spinlock_t so_lock;
    atomic_t so_count;
    long unsigned int so_flags;
    struct list_head so_states;
    struct nfs_seqid_counter so_seqid;
    seqcount_spinlock_t so_reclaim_seqcount;
    struct mutex so_delegreturn_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nfs4_state_owner {
    struct nfs_server * so_server;
    struct list_head so_lru;
    long unsigned int so_expires;
    struct rb_node so_server_node;
    const struct cred * so_cred;
    spinlock_t so_lock;
    atomic_t so_count;
    long unsigned int so_flags;
    struct list_head so_states;
    struct nfs_seqid_counter so_seqid;
    seqcount_spinlock_t so_reclaim_seqcount;
    struct mutex so_delegreturn_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nfs4_state_owner {
    struct nfs_server * so_server;
    struct list_head so_lru;
    long unsigned int so_expires;
    struct rb_node so_server_node;
    const struct cred * so_cred;
    spinlock_t so_lock;
    atomic_t so_count;
    long unsigned int so_flags;
    struct list_head so_states;
    struct nfs_seqid_counter so_seqid;
    seqcount_spinlock_t so_reclaim_seqcount;
    struct mutex so_delegreturn_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nfs4_state_owner {
    struct nfs_server * so_server;
    struct list_head so_lru;
    long unsigned int so_expires;
    struct rb_node so_server_node;
    const struct cred * so_cred;
    spinlock_t so_lock;
    atomic_t so_count;
    long unsigned int so_flags;
    struct list_head so_states;
    struct nfs_seqid_counter so_seqid;
    seqcount_spinlock_t so_reclaim_seqcount;
    struct mutex so_delegreturn_mutex;
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct nfs4_state_owner {
    struct nfs_server * so_server;
    struct list_head so_lru;
    long unsigned int so_expires;
    struct rb_node so_server_node;
    const struct cred * so_cred;
    spinlock_t so_lock;
    atomic_t so_count;
    long unsigned int so_flags;
    struct list_head so_states;
    struct nfs_seqid_counter so_seqid;
    seqcount_spinlock_t so_reclaim_seqcount;
    struct mutex so_delegreturn_mutex;
}
```
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
