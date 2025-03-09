# Struct: <code>kernfs_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
    loff_t (*)(struct kernfs_open_file *, loff_t, int) llseek;
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
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
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
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct kernfs_ops {
    int (*)(struct kernfs_open_file *) open;
    void (*)(struct kernfs_open_file *) release;
    int (*)(struct seq_file *, void *) seq_show;
    void * (*)(struct seq_file *, loff_t *) seq_start;
    void * (*)(struct seq_file *, void *, loff_t *) seq_next;
    void (*)(struct seq_file *, void *) seq_stop;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) read;
    size_t atomic_write_len;
    bool prealloc;
    ssize_t (*)(struct kernfs_open_file *, char *, size_t, loff_t) write;
    __poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll;
    int (*)(struct kernfs_open_file *, struct vm_area_struct *) mmap;
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
<code>int (*)(struct kernfs_open_file *) open</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kernfs_open_file *) release</code>
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
<code>__poll_t (*)(struct kernfs_open_file *, struct poll_table_struct *) poll</code>
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
<b>Field added. </b>
<code>loff_t (*)(struct kernfs_open_file *, loff_t, int) llseek</code>
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
