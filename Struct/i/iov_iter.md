# Struct: <code>iov_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    long unsigned int nr_segs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    long unsigned int nr_segs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    int idx;
    int start_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    int idx;
    int start_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    int idx;
    int start_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    unsigned int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    int idx;
    int start_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    unsigned int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    int idx;
    int start_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    unsigned int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    int idx;
    int start_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    unsigned int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    unsigned int head;
    unsigned int start_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    unsigned int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    unsigned int head;
    unsigned int start_head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    unsigned int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct xarray * xarray;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    unsigned int head;
    unsigned int start_head;
    loff_t xarray_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    u8 iter_type;
    bool data_source;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct xarray * xarray;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    unsigned int head;
    unsigned int start_head;
    loff_t xarray_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    u8 iter_type;
    bool nofault;
    bool data_source;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct xarray * xarray;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    unsigned int head;
    unsigned int start_head;
    loff_t xarray_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    u8 iter_type;
    bool nofault;
    bool data_source;
    bool user_backed;
    size_t iov_offset;
    int last_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct xarray * xarray;
    struct pipe_inode_info * pipe;
    void * ubuf;
    long unsigned int nr_segs;
    unsigned int head;
    unsigned int start_head;
    loff_t xarray_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    u8 iter_type;
    bool copy_mc;
    bool nofault;
    bool data_source;
    bool user_backed;
    size_t iov_offset;
    int last_offset;
    struct iovec __ubuf_iovec;
    const struct iovec * __iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct xarray * xarray;
    void * ubuf;
    size_t count;
    long unsigned int nr_segs;
    loff_t xarray_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct iov_iter {
    u8 iter_type;
    bool nofault;
    bool data_source;
    size_t iov_offset;
    struct iovec __ubuf_iovec;
    const struct iovec * __iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct xarray * xarray;
    void * ubuf;
    size_t count;
    long unsigned int nr_segs;
    loff_t xarray_start;
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
struct iov_iter {
    unsigned int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    int idx;
    int start_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct iov_iter {
    unsigned int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    int idx;
    int start_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct iov_iter {
    unsigned int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    int idx;
    int start_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct iov_iter {
    unsigned int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    int idx;
    int start_idx;
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
struct iov_iter {
    unsigned int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    int idx;
    int start_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct iov_iter {
    unsigned int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    int idx;
    int start_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct iov_iter {
    unsigned int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    int idx;
    int start_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct iov_iter {
    unsigned int type;
    size_t iov_offset;
    size_t count;
    const struct iovec * iov;
    const struct kvec * kvec;
    const struct bio_vec * bvec;
    struct pipe_inode_info * pipe;
    long unsigned int nr_segs;
    int idx;
    int start_idx;
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
<code>struct pipe_inode_info * pipe</code>
</li>
<li>
<b>Field added. </b>
<code>int idx</code>
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
<code>int start_idx</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int type</code> ➡️ <code>unsigned int type</code>
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
<code>unsigned int head</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int start_head</code>
</li>
<li>
<b>Field removed. </b>
<code>int idx</code>
</li>
<li>
<b>Field removed. </b>
<code>int start_idx</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct xarray * xarray</code>
</li>
<li>
<b>Field added. </b>
<code>loff_t xarray_start</code>
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
<code>u8 iter_type</code>
</li>
<li>
<b>Field added. </b>
<code>bool data_source</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int type</code>
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
<code>bool nofault</code>
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
<code>bool user_backed</code>
</li>
<li>
<b>Field added. </b>
<code>int last_offset</code>
</li>
<li>
<b>Field added. </b>
<code>void * ubuf</code>
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
<code>bool copy_mc</code>
</li>
<li>
<b>Field added. </b>
<code>struct iovec __ubuf_iovec</code>
</li>
<li>
<b>Field added. </b>
<code>const struct iovec * __iov</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct iovec * iov</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pipe_inode_info * pipe</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int head</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int start_head</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool copy_mc</code>
</li>
<li>
<b>Field removed. </b>
<code>bool user_backed</code>
</li>
<li>
<b>Field removed. </b>
<code>int last_offset</code>
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
