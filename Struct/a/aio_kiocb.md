# Struct: <code>aio_kiocb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct kiocb common;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct iocb * ki_user_iocb;
    __u64 ki_user_data;
    struct list_head ki_list;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct kiocb common;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct iocb * ki_user_iocb;
    __u64 ki_user_data;
    struct list_head ki_list;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct kiocb common;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct iocb * ki_user_iocb;
    __u64 ki_user_data;
    struct list_head ki_list;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct kiocb common;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct iocb * ki_user_iocb;
    __u64 ki_user_data;
    struct list_head ki_list;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct kiocb common;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct iocb * ki_user_iocb;
    __u64 ki_user_data;
    struct list_head ki_list;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct iocb * ki_user_iocb;
    __u64 ki_user_data;
    struct list_head ki_list;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct iocb * ki_user_iocb;
    __u64 ki_user_data;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
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
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
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
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct aio_kiocb {
    struct file * ki_filp;
    struct kiocb rw;
    struct fsync_iocb fsync;
    struct poll_iocb poll;
    struct kioctx * ki_ctx;
    kiocb_cancel_fn * ki_cancel;
    struct io_event ki_res;
    struct list_head ki_list;
    refcount_t ki_refcnt;
    struct eventfd_ctx * ki_eventfd;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct kiocb rw</code>
</li>
<li>
<b>Field added. </b>
<code>struct fsync_iocb fsync</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kiocb common</code>
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
<code>struct file * ki_filp</code>
</li>
<li>
<b>Field added. </b>
<code>struct poll_iocb poll</code>
</li>
<li>
<b>Field added. </b>
<code>refcount_t ki_refcnt</code>
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
<code>struct io_event ki_res</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iocb * ki_user_iocb</code>
</li>
<li>
<b>Field removed. </b>
<code>__u64 ki_user_data</code>
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
