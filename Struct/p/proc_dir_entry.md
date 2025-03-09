# Struct: <code>proc_dir_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    unsigned int low_ino;
    umode_t mode;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    void * data;
    atomic_t count;
    atomic_t in_use;
    struct completion * pde_unload_completion;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    u8 namelen;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    unsigned int low_ino;
    umode_t mode;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    void * data;
    atomic_t count;
    atomic_t in_use;
    struct completion * pde_unload_completion;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    u8 namelen;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    unsigned int low_ino;
    umode_t mode;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    void * data;
    atomic_t count;
    atomic_t in_use;
    struct completion * pde_unload_completion;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    u8 namelen;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    unsigned int low_ino;
    umode_t mode;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    void * data;
    atomic_t count;
    atomic_t in_use;
    struct completion * pde_unload_completion;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    u8 namelen;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    unsigned int low_ino;
    umode_t mode;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    struct proc_dir_entry * parent;
    struct rb_root_cached subdir;
    struct rb_node subdir_node;
    void * data;
    atomic_t count;
    atomic_t in_use;
    struct completion * pde_unload_completion;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    u8 namelen;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct proc_ops * proc_ops;
    const struct file_operations * proc_dir_ops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 flags;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct proc_ops * proc_ops;
    const struct file_operations * proc_dir_ops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 flags;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct proc_ops * proc_ops;
    const struct file_operations * proc_dir_ops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 flags;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct proc_ops * proc_ops;
    const struct file_operations * proc_dir_ops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 flags;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct proc_ops * proc_ops;
    const struct file_operations * proc_dir_ops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 flags;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct proc_ops * proc_ops;
    const struct file_operations * proc_dir_ops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 flags;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct proc_ops * proc_ops;
    const struct file_operations * proc_dir_ops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 flags;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct proc_ops * proc_ops;
    const struct file_operations * proc_dir_ops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 flags;
    u8 namelen;
    char[0] inline_name;
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
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 namelen;
    char[0] inline_name;
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
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 namelen;
    char[0] inline_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct proc_dir_entry {
    atomic_t in_use;
    refcount_t refcnt;
    struct list_head pde_openers;
    spinlock_t pde_unload_lock;
    struct completion * pde_unload_completion;
    const struct inode_operations * proc_iops;
    const struct file_operations * proc_fops;
    const struct dentry_operations * proc_dops;
    const struct seq_operations * seq_ops;
    int (*)(struct seq_file *, void *) single_show;
    proc_write_t write;
    void * data;
    unsigned int state_size;
    unsigned int low_ino;
    nlink_t nlink;
    kuid_t uid;
    kgid_t gid;
    loff_t size;
    struct proc_dir_entry * parent;
    struct rb_root subdir;
    struct rb_node subdir_node;
    char * name;
    umode_t mode;
    u8 namelen;
    char[0] inline_name;
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct rb_root subdir</code> ➡️ <code>struct rb_root_cached subdir</code>
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
<code>refcount_t refcnt</code>
</li>
<li>
<b>Field added. </b>
<code>const struct seq_operations * seq_ops</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct seq_file *, void *) single_show</code>
</li>
<li>
<b>Field added. </b>
<code>proc_write_t write</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int state_size</code>
</li>
<li>
<b>Field added. </b>
<code>char[0] inline_name</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t count</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct rb_root_cached subdir</code> ➡️ <code>struct rb_root subdir</code>
</li>
<li>
<b>Field type changed. </b>
<code>char[0] name</code> ➡️ <code>char * name</code>
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
<code>const struct dentry_operations * proc_dops</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>const struct proc_ops * proc_ops</code>
</li>
<li>
<b>Field added. </b>
<code>const struct file_operations * proc_dir_ops</code>
</li>
<li>
<b>Field added. </b>
<code>u8 flags</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct file_operations * proc_fops</code>
</li>
</ul>
</details>
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
