# Struct: <code>dio_submit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
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
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
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
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dio_submit {
    struct bio * bio;
    unsigned int blkbits;
    unsigned int blkfactor;
    unsigned int start_zero_done;
    int pages_in_io;
    sector_t block_in_file;
    unsigned int blocks_available;
    int reap_counter;
    sector_t final_block_in_request;
    int boundary;
    get_block_t * get_block;
    dio_submit_t * submit_io;
    loff_t logical_offset_in_bio;
    sector_t final_block_in_bio;
    sector_t next_block_for_io;
    struct page * cur_page;
    unsigned int cur_page_offset;
    unsigned int cur_page_len;
    sector_t cur_page_block;
    loff_t cur_page_fs_offset;
    struct iov_iter * iter;
    unsigned int head;
    unsigned int tail;
    size_t from;
    size_t to;
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>dio_submit_t * submit_io</code>
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
