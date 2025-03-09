# Struct: <code>shmem_sb_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    kuid_t uid;
    kgid_t gid;
    umode_t mode;
    struct mempolicy * mpol;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    long unsigned int max_inodes;
    long unsigned int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    long unsigned int max_inodes;
    long unsigned int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    bool full_inums;
    ino_t next_ino;
    ino_t * ino_batch;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    long unsigned int max_inodes;
    long unsigned int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    bool full_inums;
    ino_t next_ino;
    ino_t * ino_batch;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    long unsigned int max_inodes;
    long unsigned int free_inodes;
    raw_spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    bool full_inums;
    ino_t next_ino;
    ino_t * ino_batch;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    long unsigned int max_inodes;
    long unsigned int free_inodes;
    raw_spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    bool full_inums;
    ino_t next_ino;
    ino_t * ino_batch;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    long unsigned int max_inodes;
    long unsigned int free_inodes;
    raw_spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    bool full_inums;
    ino_t next_ino;
    ino_t * ino_batch;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    long unsigned int max_inodes;
    long unsigned int free_inodes;
    raw_spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    bool full_inums;
    bool noswap;
    ino_t next_ino;
    ino_t * ino_batch;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    long unsigned int max_inodes;
    long unsigned int free_ispace;
    raw_spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    bool full_inums;
    bool noswap;
    ino_t next_ino;
    ino_t * ino_batch;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
    struct shmem_quota_limits qlimits;
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
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
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
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct shmem_sb_info {
    struct mutex idr_lock;
    bool idr_nouse;
    struct idr idr;
    long unsigned int max_blocks;
    struct percpu_counter used_blocks;
    int max_inodes;
    int free_inodes;
    spinlock_t stat_lock;
    umode_t mode;
    unsigned char huge;
    kuid_t uid;
    kgid_t gid;
    struct mempolicy * mpol;
    spinlock_t shrinklist_lock;
    struct list_head shrinklist;
    long unsigned int shrinklist_len;
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
<code>unsigned char huge</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t shrinklist_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head shrinklist</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int shrinklist_len</code>
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
<code>struct mutex idr_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>bool idr_nouse</code>
</li>
<li>
<b>Field removed. </b>
<code>struct idr idr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int max_inodes</code> ➡️ <code>long unsigned int max_inodes</code>
</li>
<li>
<b>Field type changed. </b>
<code>int free_inodes</code> ➡️ <code>long unsigned int free_inodes</code>
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
<code>struct mutex idr_lock</code>
</li>
<li>
<b>Field added. </b>
<code>bool idr_nouse</code>
</li>
<li>
<b>Field added. </b>
<code>struct idr idr</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int max_inodes</code> ➡️ <code>int max_inodes</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int free_inodes</code> ➡️ <code>int free_inodes</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool full_inums</code>
</li>
<li>
<b>Field added. </b>
<code>ino_t next_ino</code>
</li>
<li>
<b>Field added. </b>
<code>ino_t * ino_batch</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex idr_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>bool idr_nouse</code>
</li>
<li>
<b>Field removed. </b>
<code>struct idr idr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int max_inodes</code> ➡️ <code>long unsigned int max_inodes</code>
</li>
<li>
<b>Field type changed. </b>
<code>int free_inodes</code> ➡️ <code>long unsigned int free_inodes</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>spinlock_t stat_lock</code> ➡️ <code>raw_spinlock_t stat_lock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
<code>bool noswap</code>
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
<code>long unsigned int free_ispace</code>
</li>
<li>
<b>Field added. </b>
<code>struct shmem_quota_limits qlimits</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int free_inodes</code>
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
