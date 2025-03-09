# Struct: <code>zs_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class * * size_class;
    struct kmem_cache * handle_cachep;
    gfp_t flags;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    bool shrinker_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class * * size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    bool shrinker_enabled;
    struct inode * inode;
    struct work_struct free_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class * * size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    bool shrinker_enabled;
    struct inode * inode;
    struct work_struct free_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    bool shrinker_enabled;
    struct inode * inode;
    struct work_struct free_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    bool shrinker_enabled;
    struct inode * inode;
    struct work_struct free_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
    struct wait_queue_head migration_wait;
    atomic_long_t isolated_pages;
    bool destroying;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
    struct wait_queue_head migration_wait;
    atomic_long_t isolated_pages;
    bool destroying;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
    struct wait_queue_head migration_wait;
    atomic_long_t isolated_pages;
    bool destroying;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
    struct wait_queue_head migration_wait;
    atomic_long_t isolated_pages;
    bool destroying;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
    struct wait_queue_head migration_wait;
    atomic_long_t isolated_pages;
    bool destroying;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
    struct wait_queue_head migration_wait;
    atomic_long_t isolated_pages;
    bool destroying;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
    rwlock_t migrate_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct list_head lru;
    struct zpool * zpool;
    const struct zpool_ops * zpool_ops;
    struct work_struct free_work;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct work_struct free_work;
    spinlock_t lock;
    atomic_t compaction_in_progress;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker * shrinker;
    struct work_struct free_work;
    spinlock_t lock;
    atomic_t compaction_in_progress;
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
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
    struct wait_queue_head migration_wait;
    atomic_long_t isolated_pages;
    bool destroying;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
    struct wait_queue_head migration_wait;
    atomic_long_t isolated_pages;
    bool destroying;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[257] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
    struct wait_queue_head migration_wait;
    atomic_long_t isolated_pages;
    bool destroying;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
    struct wait_queue_head migration_wait;
    atomic_long_t isolated_pages;
    bool destroying;
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
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
    struct wait_queue_head migration_wait;
    atomic_long_t isolated_pages;
    bool destroying;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
    struct wait_queue_head migration_wait;
    atomic_long_t isolated_pages;
    bool destroying;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
    struct wait_queue_head migration_wait;
    atomic_long_t isolated_pages;
    bool destroying;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct zs_pool {
    const char * name;
    struct size_class *[255] size_class;
    struct kmem_cache * handle_cachep;
    struct kmem_cache * zspage_cachep;
    atomic_long_t pages_allocated;
    struct zs_pool_stats stats;
    struct shrinker shrinker;
    struct inode * inode;
    struct work_struct free_work;
    struct wait_queue_head migration_wait;
    atomic_long_t isolated_pages;
    bool destroying;
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
<code>struct kmem_cache * zspage_cachep</code>
</li>
<li>
<b>Field added. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct free_work</code>
</li>
<li>
<b>Field removed. </b>
<code>gfp_t flags</code>
</li>
</ul>
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
<code>struct size_class * * size_class</code> ➡️ <code>struct size_class *[255] size_class</code>
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
<b>Field removed. </b>
<code>bool shrinker_enabled</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct wait_queue_head migration_wait</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_long_t isolated_pages</code>
</li>
<li>
<b>Field added. </b>
<code>bool destroying</code>
</li>
</ul>
</details>
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
<code>rwlock_t migrate_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct wait_queue_head migration_wait</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t isolated_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>bool destroying</code>
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
<code>struct list_head lru</code>
</li>
<li>
<b>Field added. </b>
<code>struct zpool * zpool</code>
</li>
<li>
<b>Field added. </b>
<code>const struct zpool_ops * zpool_ops</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Field removed. </b>
<code>rwlock_t migrate_lock</code>
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
<code>atomic_t compaction_in_progress</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head lru</code>
</li>
<li>
<b>Field removed. </b>
<code>struct zpool * zpool</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct zpool_ops * zpool_ops</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct shrinker shrinker</code> ➡️ <code>struct shrinker * shrinker</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct size_class *[255] size_class</code> ➡️ <code>struct size_class *[257] size_class</code>
</li>
</ul>
</details>
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
