# Struct: <code>pid_namespace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct kref kref;
    struct pidmap[128] pidmap;
    struct callback_head rcu;
    int last_pid;
    unsigned int nr_hashed;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct kref kref;
    struct pidmap[128] pidmap;
    struct callback_head rcu;
    int last_pid;
    unsigned int nr_hashed;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct kref kref;
    struct pidmap[128] pidmap;
    struct callback_head rcu;
    int last_pid;
    unsigned int nr_hashed;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct kref kref;
    struct pidmap[128] pidmap;
    struct callback_head rcu;
    int last_pid;
    unsigned int nr_hashed;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct kref kref;
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct kref kref;
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct kref kref;
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct kref kref;
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct kref kref;
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct kref kref;
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    int reboot;
    struct ns_common ns;
    int memfd_noexec_scope;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    int reboot;
    struct ns_common ns;
    int memfd_noexec_scope;
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
struct pid_namespace {
    struct kref kref;
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pid_namespace {
    struct kref kref;
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pid_namespace {
    struct kref kref;
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pid_namespace {
    struct kref kref;
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
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
struct pid_namespace {
    struct kref kref;
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct kref kref;
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct kref kref;
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pid_namespace {
    struct kref kref;
    struct idr idr;
    struct callback_head rcu;
    unsigned int pid_allocated;
    struct task_struct * child_reaper;
    struct kmem_cache * pid_cachep;
    unsigned int level;
    struct pid_namespace * parent;
    struct vfsmount * proc_mnt;
    struct dentry * proc_self;
    struct dentry * proc_thread_self;
    struct fs_pin * bacct;
    struct user_namespace * user_ns;
    struct ucounts * ucounts;
    struct work_struct proc_work;
    kgid_t pid_gid;
    int hide_pid;
    int reboot;
    struct ns_common ns;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct ucounts * ucounts</code>
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
<b>Field added. </b>
<code>struct idr idr</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int pid_allocated</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pidmap[128] pidmap</code>
</li>
<li>
<b>Field removed. </b>
<code>int last_pid</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int nr_hashed</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct vfsmount * proc_mnt</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dentry * proc_self</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dentry * proc_thread_self</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct proc_work</code>
</li>
<li>
<b>Field removed. </b>
<code>kgid_t pid_gid</code>
</li>
<li>
<b>Field removed. </b>
<code>int hide_pid</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct kref kref</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int memfd_noexec_scope</code>
</li>
</ul>
</details>
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
