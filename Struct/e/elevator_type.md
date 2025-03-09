# Struct: <code>elevator_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    char[16] elevator_name;
    struct module * elevator_owner;
    char[21] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    char[16] elevator_name;
    struct module * elevator_owner;
    char[21] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    char[16] elevator_name;
    struct module * elevator_owner;
    char[21] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    union (anon) ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    char[16] elevator_name;
    struct module * elevator_owner;
    bool uses_mq;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    union (anon) ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    char[16] elevator_name;
    const char * elevator_alias;
    struct module * elevator_owner;
    bool uses_mq;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    union (anon) ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    char[16] elevator_name;
    const char * elevator_alias;
    struct module * elevator_owner;
    bool uses_mq;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    char[16] elevator_name;
    const char * elevator_alias;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
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
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
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
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct elevator_type {
    struct kmem_cache * icq_cache;
    struct elevator_mq_ops ops;
    size_t icq_size;
    size_t icq_align;
    struct elv_fs_entry * elevator_attrs;
    const char * elevator_name;
    const char * elevator_alias;
    const unsigned int elevator_features;
    struct module * elevator_owner;
    const struct blk_mq_debugfs_attr * queue_debugfs_attrs;
    const struct blk_mq_debugfs_attr * hctx_debugfs_attrs;
    char[22] icq_cache_name;
    struct list_head list;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<code>bool uses_mq</code>
</li>
<li>
<b>Field added. </b>
<code>const struct blk_mq_debugfs_attr * queue_debugfs_attrs</code>
</li>
<li>
<b>Field added. </b>
<code>const struct blk_mq_debugfs_attr * hctx_debugfs_attrs</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct elevator_ops ops</code> ➡️ <code>union (anon) ops</code>
</li>
<li>
<b>Field type changed. </b>
<code>char[21] icq_cache_name</code> ➡️ <code>char[22] icq_cache_name</code>
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
<code>const char * elevator_alias</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool uses_mq</code>
</li>
<li>
<b>Field type changed. </b>
<code>union (anon) ops</code> ➡️ <code>struct elevator_mq_ops ops</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>char[16] elevator_name</code> ➡️ <code>const char * elevator_name</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const unsigned int elevator_features</code>
</li>
</ul>
</details>
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
