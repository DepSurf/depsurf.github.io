# Struct: <code>buffer_head</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
    spinlock_t b_uptodate_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
    spinlock_t b_uptodate_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
    spinlock_t b_uptodate_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
    spinlock_t b_uptodate_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
    spinlock_t b_uptodate_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
    spinlock_t b_uptodate_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    struct folio * b_folio;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
    spinlock_t b_uptodate_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    struct folio * b_folio;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
    spinlock_t b_uptodate_lock;
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
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
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
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct buffer_head {
    long unsigned int b_state;
    struct buffer_head * b_this_page;
    struct page * b_page;
    sector_t b_blocknr;
    size_t b_size;
    char * b_data;
    struct block_device * b_bdev;
    bh_end_io_t * b_end_io;
    void * b_private;
    struct list_head b_assoc_buffers;
    struct address_space * b_assoc_map;
    atomic_t b_count;
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
<code>spinlock_t b_uptodate_lock</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct folio * b_folio</code>
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
