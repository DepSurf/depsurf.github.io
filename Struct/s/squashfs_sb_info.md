# Struct: <code>squashfs_sb_info</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    int xattr_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    int xattr_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    int xattr_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    int xattr_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
    unsigned int ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
    unsigned int ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
    unsigned int ids;
    bool panic_on_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
    unsigned int ids;
    bool panic_on_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    void * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    unsigned int xattr_ids;
    unsigned int ids;
    bool panic_on_errors;
    const struct squashfs_decompressor_thread_ops * thread_ops;
    int max_thread_num;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    struct address_space * cache_mapping;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    void * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    unsigned int xattr_ids;
    unsigned int ids;
    bool panic_on_errors;
    const struct squashfs_decompressor_thread_ops * thread_ops;
    int max_thread_num;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    struct address_space * cache_mapping;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    void * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    unsigned int xattr_ids;
    unsigned int ids;
    bool panic_on_errors;
    const struct squashfs_decompressor_thread_ops * thread_ops;
    int max_thread_num;
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
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
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
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    unsigned int fragments;
    int xattr_ids;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct squashfs_sb_info {
    const struct squashfs_decompressor * decompressor;
    int devblksize;
    int devblksize_log2;
    struct squashfs_cache * block_cache;
    struct squashfs_cache * fragment_cache;
    struct squashfs_cache * read_page;
    int next_meta_index;
    __le64 * id_table;
    __le64 * fragment_index;
    __le64 * xattr_id_table;
    struct mutex meta_index_mutex;
    struct meta_index * meta_index;
    struct squashfs_stream * stream;
    __le64 * inode_lookup_table;
    u64 inode_table;
    u64 directory_table;
    u64 xattr_table;
    unsigned int block_size;
    short unsigned int block_log;
    long long int bytes_used;
    unsigned int inodes;
    int xattr_ids;
}
```
</details>
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int fragments</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int ids</code>
</li>
</ul>
</details>
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
<code>bool panic_on_errors</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct squashfs_decompressor_thread_ops * thread_ops</code>
</li>
<li>
<b>Field added. </b>
<code>int max_thread_num</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct squashfs_stream * stream</code> ➡️ <code>void * stream</code>
</li>
<li>
<b>Field type changed. </b>
<code>int xattr_ids</code> ➡️ <code>unsigned int xattr_ids</code>
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
<code>struct address_space * cache_mapping</code>
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
