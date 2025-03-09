# Struct: <code>drm_file</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct drm_file {
    bool authenticated;
    bool stereo_allowed;
    bool universal_planes;
    bool atomic;
    bool aspect_ratio_allowed;
    bool writeback_connectors;
    bool is_master;
    struct drm_master * master;
    struct pid * pid;
    drm_magic_t magic;
    struct list_head lhead;
    struct drm_minor * minor;
    struct idr object_idr;
    spinlock_t table_lock;
    struct idr syncobj_idr;
    spinlock_t syncobj_table_lock;
    struct file * filp;
    void * driver_priv;
    struct list_head fbs;
    struct mutex fbs_lock;
    struct list_head blobs;
    wait_queue_head_t event_wait;
    struct list_head pending_event_list;
    struct list_head event_list;
    int event_space;
    struct mutex event_read_lock;
    struct drm_prime_file_private prime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct drm_file {
    bool authenticated;
    bool stereo_allowed;
    bool universal_planes;
    bool atomic;
    bool aspect_ratio_allowed;
    bool writeback_connectors;
    bool is_master;
    struct drm_master * master;
    struct pid * pid;
    drm_magic_t magic;
    struct list_head lhead;
    struct drm_minor * minor;
    struct idr object_idr;
    spinlock_t table_lock;
    struct idr syncobj_idr;
    spinlock_t syncobj_table_lock;
    struct file * filp;
    void * driver_priv;
    struct list_head fbs;
    struct mutex fbs_lock;
    struct list_head blobs;
    wait_queue_head_t event_wait;
    struct list_head pending_event_list;
    struct list_head event_list;
    int event_space;
    struct mutex event_read_lock;
    struct drm_prime_file_private prime;
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct drm_file {
    bool authenticated;
    bool stereo_allowed;
    bool universal_planes;
    bool atomic;
    bool aspect_ratio_allowed;
    bool writeback_connectors;
    bool was_master;
    bool is_master;
    bool supports_virtualized_cursor_plane;
    struct drm_master * master;
    spinlock_t master_lookup_lock;
    struct pid * pid;
    u64 client_id;
    drm_magic_t magic;
    struct list_head lhead;
    struct drm_minor * minor;
    struct idr object_idr;
    spinlock_t table_lock;
    struct idr syncobj_idr;
    spinlock_t syncobj_table_lock;
    struct file * filp;
    void * driver_priv;
    struct list_head fbs;
    struct mutex fbs_lock;
    struct list_head blobs;
    wait_queue_head_t event_wait;
    struct list_head pending_event_list;
    struct list_head event_list;
    int event_space;
    struct mutex event_read_lock;
    struct drm_prime_file_private prime;
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
struct drm_file {
    bool authenticated;
    bool stereo_allowed;
    bool universal_planes;
    bool atomic;
    bool aspect_ratio_allowed;
    bool writeback_connectors;
    bool is_master;
    struct drm_master * master;
    struct pid * pid;
    drm_magic_t magic;
    struct list_head lhead;
    struct drm_minor * minor;
    struct idr object_idr;
    spinlock_t table_lock;
    struct idr syncobj_idr;
    spinlock_t syncobj_table_lock;
    struct file * filp;
    void * driver_priv;
    struct list_head fbs;
    struct mutex fbs_lock;
    struct list_head blobs;
    wait_queue_head_t event_wait;
    struct list_head pending_event_list;
    struct list_head event_list;
    int event_space;
    struct mutex event_read_lock;
    struct drm_prime_file_private prime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct drm_file {
    bool authenticated;
    bool stereo_allowed;
    bool universal_planes;
    bool atomic;
    bool aspect_ratio_allowed;
    bool writeback_connectors;
    bool is_master;
    struct drm_master * master;
    struct pid * pid;
    drm_magic_t magic;
    struct list_head lhead;
    struct drm_minor * minor;
    struct idr object_idr;
    spinlock_t table_lock;
    struct idr syncobj_idr;
    spinlock_t syncobj_table_lock;
    struct file * filp;
    void * driver_priv;
    struct list_head fbs;
    struct mutex fbs_lock;
    struct list_head blobs;
    wait_queue_head_t event_wait;
    struct list_head pending_event_list;
    struct list_head event_list;
    int event_space;
    struct mutex event_read_lock;
    struct drm_prime_file_private prime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct drm_file {
    bool authenticated;
    bool stereo_allowed;
    bool universal_planes;
    bool atomic;
    bool aspect_ratio_allowed;
    bool writeback_connectors;
    bool is_master;
    struct drm_master * master;
    struct pid * pid;
    drm_magic_t magic;
    struct list_head lhead;
    struct drm_minor * minor;
    struct idr object_idr;
    spinlock_t table_lock;
    struct idr syncobj_idr;
    spinlock_t syncobj_table_lock;
    struct file * filp;
    void * driver_priv;
    struct list_head fbs;
    struct mutex fbs_lock;
    struct list_head blobs;
    wait_queue_head_t event_wait;
    struct list_head pending_event_list;
    struct list_head event_list;
    int event_space;
    struct mutex event_read_lock;
    struct drm_prime_file_private prime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct drm_file {
    bool authenticated;
    bool stereo_allowed;
    bool universal_planes;
    bool atomic;
    bool aspect_ratio_allowed;
    bool writeback_connectors;
    bool is_master;
    struct drm_master * master;
    struct pid * pid;
    drm_magic_t magic;
    struct list_head lhead;
    struct drm_minor * minor;
    struct idr object_idr;
    spinlock_t table_lock;
    struct idr syncobj_idr;
    spinlock_t syncobj_table_lock;
    struct file * filp;
    void * driver_priv;
    struct list_head fbs;
    struct mutex fbs_lock;
    struct list_head blobs;
    wait_queue_head_t event_wait;
    struct list_head pending_event_list;
    struct list_head event_list;
    int event_space;
    struct mutex event_read_lock;
    struct drm_prime_file_private prime;
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
struct drm_file {
    bool authenticated;
    bool stereo_allowed;
    bool universal_planes;
    bool atomic;
    bool aspect_ratio_allowed;
    bool writeback_connectors;
    bool is_master;
    struct drm_master * master;
    struct pid * pid;
    drm_magic_t magic;
    struct list_head lhead;
    struct drm_minor * minor;
    struct idr object_idr;
    spinlock_t table_lock;
    struct idr syncobj_idr;
    spinlock_t syncobj_table_lock;
    struct file * filp;
    void * driver_priv;
    struct list_head fbs;
    struct mutex fbs_lock;
    struct list_head blobs;
    wait_queue_head_t event_wait;
    struct list_head pending_event_list;
    struct list_head event_list;
    int event_space;
    struct mutex event_read_lock;
    struct drm_prime_file_private prime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct drm_file {
    bool authenticated;
    bool stereo_allowed;
    bool universal_planes;
    bool atomic;
    bool aspect_ratio_allowed;
    bool writeback_connectors;
    bool is_master;
    struct drm_master * master;
    struct pid * pid;
    drm_magic_t magic;
    struct list_head lhead;
    struct drm_minor * minor;
    struct idr object_idr;
    spinlock_t table_lock;
    struct idr syncobj_idr;
    spinlock_t syncobj_table_lock;
    struct file * filp;
    void * driver_priv;
    struct list_head fbs;
    struct mutex fbs_lock;
    struct list_head blobs;
    wait_queue_head_t event_wait;
    struct list_head pending_event_list;
    struct list_head event_list;
    int event_space;
    struct mutex event_read_lock;
    struct drm_prime_file_private prime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct drm_file {
    bool authenticated;
    bool stereo_allowed;
    bool universal_planes;
    bool atomic;
    bool aspect_ratio_allowed;
    bool writeback_connectors;
    bool is_master;
    struct drm_master * master;
    struct pid * pid;
    drm_magic_t magic;
    struct list_head lhead;
    struct drm_minor * minor;
    struct idr object_idr;
    spinlock_t table_lock;
    struct idr syncobj_idr;
    spinlock_t syncobj_table_lock;
    struct file * filp;
    void * driver_priv;
    struct list_head fbs;
    struct mutex fbs_lock;
    struct list_head blobs;
    wait_queue_head_t event_wait;
    struct list_head pending_event_list;
    struct list_head event_list;
    int event_space;
    struct mutex event_read_lock;
    struct drm_prime_file_private prime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct drm_file {
    bool authenticated;
    bool stereo_allowed;
    bool universal_planes;
    bool atomic;
    bool aspect_ratio_allowed;
    bool writeback_connectors;
    bool is_master;
    struct drm_master * master;
    struct pid * pid;
    drm_magic_t magic;
    struct list_head lhead;
    struct drm_minor * minor;
    struct idr object_idr;
    spinlock_t table_lock;
    struct idr syncobj_idr;
    spinlock_t syncobj_table_lock;
    struct file * filp;
    void * driver_priv;
    struct list_head fbs;
    struct mutex fbs_lock;
    struct list_head blobs;
    wait_queue_head_t event_wait;
    struct list_head pending_event_list;
    struct list_head event_list;
    int event_space;
    struct mutex event_read_lock;
    struct drm_prime_file_private prime;
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct drm_file {
    bool authenticated;
    bool stereo_allowed;
    bool universal_planes;
    bool atomic;
    bool aspect_ratio_allowed;
    bool writeback_connectors;
    bool is_master;
    struct drm_master * master;
    struct pid * pid;
    drm_magic_t magic;
    struct list_head lhead;
    struct drm_minor * minor;
    struct idr object_idr;
    spinlock_t table_lock;
    struct idr syncobj_idr;
    spinlock_t syncobj_table_lock;
    struct file * filp;
    void * driver_priv;
    struct list_head fbs;
    struct mutex fbs_lock;
    struct list_head blobs;
    wait_queue_head_t event_wait;
    struct list_head pending_event_list;
    struct list_head event_list;
    int event_space;
    struct mutex event_read_lock;
    struct drm_prime_file_private prime;
}
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct drm_file {
    bool authenticated;
    bool stereo_allowed;
    bool universal_planes;
    bool atomic;
    bool aspect_ratio_allowed;
    bool writeback_connectors;
    bool is_master;
    struct drm_master * master;
    struct pid * pid;
    drm_magic_t magic;
    struct list_head lhead;
    struct drm_minor * minor;
    struct idr object_idr;
    spinlock_t table_lock;
    struct idr syncobj_idr;
    spinlock_t syncobj_table_lock;
    struct file * filp;
    void * driver_priv;
    struct list_head fbs;
    struct mutex fbs_lock;
    struct list_head blobs;
    wait_queue_head_t event_wait;
    struct list_head pending_event_list;
    struct list_head event_list;
    int event_space;
    struct mutex event_read_lock;
    struct drm_prime_file_private prime;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct drm_file {
    bool authenticated;
    bool stereo_allowed;
    bool universal_planes;
    bool atomic;
    bool aspect_ratio_allowed;
    bool writeback_connectors;
    bool was_master;
    bool is_master;
    bool supports_virtualized_cursor_plane;
    struct drm_master * master;
    spinlock_t master_lookup_lock;
    struct pid * pid;
    u64 client_id;
    drm_magic_t magic;
    struct list_head lhead;
    struct drm_minor * minor;
    struct idr object_idr;
    spinlock_t table_lock;
    struct idr syncobj_idr;
    spinlock_t syncobj_table_lock;
    struct file * filp;
    void * driver_priv;
    struct list_head fbs;
    struct mutex fbs_lock;
    struct list_head blobs;
    wait_queue_head_t event_wait;
    struct list_head pending_event_list;
    struct list_head event_list;
    int event_space;
    struct mutex event_read_lock;
    struct drm_prime_file_private prime;
}
```
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
