# Struct: <code>file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
    errseq_t f_sb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct hlist_head * f_ep;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
    errseq_t f_sb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct hlist_head * f_ep;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
    errseq_t f_sb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct hlist_head * f_ep;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
    errseq_t f_sb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct hlist_head * f_ep;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
    errseq_t f_sb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct file {
    struct llist_node f_llist;
    struct callback_head f_rcuhead;
    unsigned int f_iocb_flags;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct hlist_head * f_ep;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
    errseq_t f_sb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct file {
    struct llist_node f_llist;
    struct callback_head f_rcuhead;
    unsigned int f_iocb_flags;
    spinlock_t f_lock;
    fmode_t f_mode;
    atomic_long_t f_count;
    struct mutex f_pos_lock;
    loff_t f_pos;
    unsigned int f_flags;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct hlist_head * f_ep;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
    errseq_t f_sb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct file {
    struct callback_head f_task_work;
    struct llist_node f_llist;
    unsigned int f_iocb_flags;
    spinlock_t f_lock;
    fmode_t f_mode;
    atomic_long_t f_count;
    struct mutex f_pos_lock;
    loff_t f_pos;
    unsigned int f_flags;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct hlist_head * f_ep;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
    errseq_t f_sb_err;
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
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
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
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct file {
    union (anon) f_u;
    struct path f_path;
    struct inode * f_inode;
    const struct file_operations * f_op;
    spinlock_t f_lock;
    enum rw_hint f_write_hint;
    atomic_long_t f_count;
    unsigned int f_flags;
    fmode_t f_mode;
    struct mutex f_pos_lock;
    loff_t f_pos;
    struct fown_struct f_owner;
    const struct cred * f_cred;
    struct file_ra_state f_ra;
    u64 f_version;
    void * f_security;
    void * private_data;
    struct list_head f_ep_links;
    struct list_head f_tfile_llink;
    struct address_space * f_mapping;
    errseq_t f_wb_err;
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
<code>enum rw_hint f_write_hint</code>
</li>
<li>
<b>Field added. </b>
<code>errseq_t f_wb_err</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>errseq_t f_sb_err</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_head * f_ep</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head f_ep_links</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head f_tfile_llink</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>enum rw_hint f_write_hint</code>
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
<code>struct llist_node f_llist</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head f_rcuhead</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int f_iocb_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>union (anon) f_u</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct callback_head f_task_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head f_rcuhead</code>
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
