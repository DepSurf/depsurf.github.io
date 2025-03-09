# Struct: <code>super_operations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    void (*)(struct super_block *) shutdown;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *, enum freeze_holder) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *, enum freeze_holder) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    void (*)(struct super_block *) shutdown;
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
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
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
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct super_operations {
    struct inode * (*)(struct super_block *) alloc_inode;
    void (*)(struct inode *) destroy_inode;
    void (*)(struct inode *) free_inode;
    void (*)(struct inode *, int) dirty_inode;
    int (*)(struct inode *, struct writeback_control *) write_inode;
    int (*)(struct inode *) drop_inode;
    void (*)(struct inode *) evict_inode;
    void (*)(struct super_block *) put_super;
    int (*)(struct super_block *, int) sync_fs;
    int (*)(struct super_block *) freeze_super;
    int (*)(struct super_block *) freeze_fs;
    int (*)(struct super_block *) thaw_super;
    int (*)(struct super_block *) unfreeze_fs;
    int (*)(struct dentry *, struct kstatfs *) statfs;
    int (*)(struct super_block *, int *, char *) remount_fs;
    void (*)(struct super_block *) umount_begin;
    int (*)(struct seq_file *, struct dentry *) show_options;
    int (*)(struct seq_file *, struct dentry *) show_devname;
    int (*)(struct seq_file *, struct dentry *) show_path;
    int (*)(struct seq_file *, struct dentry *) show_stats;
    ssize_t (*)(struct super_block *, int, char *, size_t, loff_t) quota_read;
    ssize_t (*)(struct super_block *, int, const char *, size_t, loff_t) quota_write;
    struct dquot * * (*)(struct inode *) get_dquots;
    int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page;
    long int (*)(struct super_block *, struct shrink_control *) nr_cached_objects;
    long int (*)(struct super_block *, struct shrink_control *) free_cached_objects;
    struct file * (*)(struct file *) real_loop;
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
<b>Field removed. </b>
<code>struct file * (*)(struct file *) real_loop</code>
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
<code>struct file * (*)(struct file *) real_loop</code>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct inode *) free_inode</code>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct file * (*)(struct file *) real_loop</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct file * (*)(struct file *) real_loop</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct super_block *, struct page *, gfp_t) bdev_try_to_free_page</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct file * (*)(struct file *) real_loop</code>
</li>
</ul>
</details>
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
<code>void (*)(struct super_block *) shutdown</code>
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
<code>int (*)(struct super_block *) freeze_super</code> ➡️ <code>int (*)(struct super_block *, enum freeze_holder) freeze_super</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct super_block *) thaw_super</code> ➡️ <code>int (*)(struct super_block *, enum freeze_holder) thaw_super</code>
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
