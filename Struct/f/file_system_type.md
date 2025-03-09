# Struct: <code>file_system_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_description * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_description * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_spec * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_spec * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_spec * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_spec * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key invalidate_lock_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_spec * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key invalidate_lock_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_spec * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key invalidate_lock_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_spec * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key invalidate_lock_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_spec * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key invalidate_lock_key;
    struct lock_class_key i_mutex_dir_key;
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
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_description * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_description * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_description * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_description * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
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
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_description * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_description * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_description * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct file_system_type {
    const char * name;
    int fs_flags;
    int (*)(struct fs_context *) init_fs_context;
    const struct fs_parameter_description * parameters;
    struct dentry * (*)(struct file_system_type *, int, const char *, void *) mount;
    void (*)(struct super_block *) kill_sb;
    struct module * owner;
    struct file_system_type * next;
    struct hlist_head fs_supers;
    struct lock_class_key s_lock_key;
    struct lock_class_key s_umount_key;
    struct lock_class_key s_vfs_rename_key;
    struct lock_class_key[3] s_writers_key;
    struct lock_class_key i_lock_key;
    struct lock_class_key i_mutex_key;
    struct lock_class_key i_mutex_dir_key;
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<code>int (*)(struct fs_context *) init_fs_context</code>
</li>
<li>
<b>Field added. </b>
<code>const struct fs_parameter_description * parameters</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>const struct fs_parameter_description * parameters</code> ➡️ <code>const struct fs_parameter_spec * parameters</code>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct lock_class_key invalidate_lock_key</code>
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
