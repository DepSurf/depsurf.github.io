# Struct: <code>fsnotify_mark_connector</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    unsigned int flags;
    struct inode * inode;
    struct vfsmount * mnt;
    struct hlist_head list;
    struct fsnotify_mark_connector * destroy_next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    unsigned int flags;
    struct inode * inode;
    struct vfsmount * mnt;
    struct hlist_head list;
    struct fsnotify_mark_connector * destroy_next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    unsigned int type;
    struct inode * inode;
    struct vfsmount * mnt;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    unsigned int type;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
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
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
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
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    short unsigned int type;
    short unsigned int flags;
    __kernel_fsid_t fsid;
    fsnotify_connp_t * obj;
    struct fsnotify_mark_connector * destroy_next;
    struct hlist_head list;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct fsnotify_mark_connector {
    spinlock_t lock;
    unsigned int flags;
    struct inode * inode;
    struct vfsmount * mnt;
    struct hlist_head list;
    struct fsnotify_mark_connector * destroy_next;
}
```
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
<code>unsigned int type</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int flags</code>
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
<code>fsnotify_connp_t * obj</code>
</li>
<li>
<b>Field removed. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Field removed. </b>
<code>struct vfsmount * mnt</code>
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
<code>short unsigned int flags</code>
</li>
<li>
<b>Field added. </b>
<code>__kernel_fsid_t fsid</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int type</code> ➡️ <code>short unsigned int type</code>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>__kernel_fsid_t fsid</code>
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
