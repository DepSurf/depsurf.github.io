# Struct: <code>file_operations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct file *, struct dir_context *) iterate;
    unsigned int (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(struct kiocb *, int) aio_fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    unsigned int (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(struct kiocb *, int) aio_fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    int (*)(struct file *, loff_t, struct file *, loff_t, u64) clone_file_range;
    ssize_t (*)(struct file *, u64, u64, struct file *, u64) dedupe_file_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    unsigned int (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    int (*)(struct file *, loff_t, struct file *, loff_t, u64) clone_file_range;
    ssize_t (*)(struct file *, u64, u64, struct file *, u64) dedupe_file_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    unsigned int (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    int (*)(struct file *, loff_t, struct file *, loff_t, u64) clone_file_range;
    ssize_t (*)(struct file *, u64, u64, struct file *, u64) dedupe_file_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    unsigned int (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    int (*)(struct file *, loff_t, struct file *, loff_t, u64) clone_file_range;
    ssize_t (*)(struct file *, u64, u64, struct file *, u64) dedupe_file_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    int (*)(struct file *, loff_t, struct file *, loff_t, u64) clone_file_range;
    ssize_t (*)(struct file *, u64, u64, struct file *, u64) dedupe_file_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, bool) iopoll;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, bool) iopoll;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, bool) iopoll;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, bool) iopoll;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, bool) iopoll;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, bool) iopoll;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, struct io_comp_batch *, unsigned int) iopoll;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
    int (*)(struct io_uring_cmd *, unsigned int) uring_cmd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, struct io_comp_batch *, unsigned int) iopoll;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
    int (*)(struct io_uring_cmd *, unsigned int) uring_cmd;
    int (*)(struct io_uring_cmd *, struct io_comp_batch *, unsigned int) uring_cmd_iopoll;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, struct io_comp_batch *, unsigned int) iopoll;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct file *) splice_eof;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
    int (*)(struct io_uring_cmd *, unsigned int) uring_cmd;
    int (*)(struct io_uring_cmd *, struct io_comp_batch *, unsigned int) uring_cmd_iopoll;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, struct io_comp_batch *, unsigned int) iopoll;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct file *) splice_eof;
    int (*)(struct file *, int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
    int (*)(struct io_uring_cmd *, unsigned int) uring_cmd;
    int (*)(struct io_uring_cmd *, struct io_comp_batch *, unsigned int) uring_cmd_iopoll;
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
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, bool) iopoll;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, bool) iopoll;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, bool) iopoll;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, bool) iopoll;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
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
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, bool) iopoll;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, bool) iopoll;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, bool) iopoll;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct file_operations {
    struct module * owner;
    loff_t (*)(struct file *, loff_t, int) llseek;
    ssize_t (*)(struct file *, char *, size_t, loff_t *) read;
    ssize_t (*)(struct file *, const char *, size_t, loff_t *) write;
    ssize_t (*)(struct kiocb *, struct iov_iter *) read_iter;
    ssize_t (*)(struct kiocb *, struct iov_iter *) write_iter;
    int (*)(struct kiocb *, bool) iopoll;
    int (*)(struct file *, struct dir_context *) iterate;
    int (*)(struct file *, struct dir_context *) iterate_shared;
    __poll_t (*)(struct file *, struct poll_table_struct *) poll;
    long int (*)(struct file *, unsigned int, long unsigned int) unlocked_ioctl;
    long int (*)(struct file *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct file *, struct vm_area_struct *) mmap;
    long unsigned int mmap_supported_flags;
    int (*)(struct inode *, struct file *) open;
    int (*)(struct file *, fl_owner_t) flush;
    int (*)(struct inode *, struct file *) release;
    int (*)(struct file *, loff_t, loff_t, int) fsync;
    int (*)(int, struct file *, int) fasync;
    int (*)(struct file *, int, struct file_lock *) lock;
    ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage;
    long unsigned int (*)(struct file *, long unsigned int, long unsigned int, long unsigned int, long unsigned int) get_unmapped_area;
    int (*)(int) check_flags;
    int (*)(struct file *, long unsigned int) setfl;
    int (*)(struct file *, int, struct file_lock *) flock;
    ssize_t (*)(struct pipe_inode_info *, struct file *, loff_t *, size_t, unsigned int) splice_write;
    ssize_t (*)(struct file *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct file *, long int, struct file_lock * *, void * *) setlease;
    long int (*)(struct file *, int, loff_t, loff_t) fallocate;
    void (*)(struct seq_file *, struct file *) show_fdinfo;
    ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range;
    loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range;
    int (*)(struct file *, loff_t, loff_t, int) fadvise;
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
<code>int (*)(struct file *, struct dir_context *) iterate_shared</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct file *, long unsigned int) setfl</code>
</li>
<li>
<b>Field added. </b>
<code>ssize_t (*)(struct file *, loff_t, struct file *, loff_t, size_t, unsigned int) copy_file_range</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct file *, loff_t, struct file *, loff_t, u64) clone_file_range</code>
</li>
<li>
<b>Field added. </b>
<code>ssize_t (*)(struct file *, u64, u64, struct file *, u64) dedupe_file_range</code>
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
<code>int (*)(struct kiocb *, int) aio_fsync</code>
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
<code>long unsigned int mmap_supported_flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned int (*)(struct file *, struct poll_table_struct *) poll</code> ➡️ <code>__poll_t (*)(struct file *, struct poll_table_struct *) poll</code>
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
<code>loff_t (*)(struct file *, loff_t, struct file *, loff_t, loff_t, unsigned int) remap_file_range</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct file *, loff_t, loff_t, int) fadvise</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct file *, loff_t, struct file *, loff_t, u64) clone_file_range</code>
</li>
<li>
<b>Field removed. </b>
<code>ssize_t (*)(struct file *, u64, u64, struct file *, u64) dedupe_file_range</code>
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
<code>int (*)(struct kiocb *, bool) iopoll</code>
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
<code>int (*)(struct file *, long unsigned int) setfl</code>
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
<code>int (*)(struct file *, long unsigned int) setfl</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct io_uring_cmd *, unsigned int) uring_cmd</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct file *, long unsigned int) setfl</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct kiocb *, bool) iopoll</code> ➡️ <code>int (*)(struct kiocb *, struct io_comp_batch *, unsigned int) iopoll</code>
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
<code>int (*)(struct io_uring_cmd *, struct io_comp_batch *, unsigned int) uring_cmd_iopoll</code>
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
<code>void (*)(struct file *) splice_eof</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct file *, struct dir_context *) iterate</code>
</li>
<li>
<b>Field removed. </b>
<code>ssize_t (*)(struct file *, struct page *, int, size_t, loff_t *, int) sendpage</code>
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
<code>int (*)(struct file *, long int, struct file_lock * *, void * *) setlease</code> ➡️ <code>int (*)(struct file *, int, struct file_lock * *, void * *) setlease</code>
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
