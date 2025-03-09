# Struct: <code>io_kiocb</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct io_kiocb {
    struct file * file;
    struct kiocb rw;
    struct io_poll_iocb poll;
    struct sqe_submit submit;
    struct io_ring_ctx * ctx;
    struct list_head list;
    struct list_head link_list;
    unsigned int flags;
    refcount_t refs;
    u64 user_data;
    u32 result;
    u32 sequence;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct io_kiocb {
    struct file * file;
    struct kiocb rw;
    struct io_poll_iocb poll;
    struct io_timeout timeout;
    struct sqe_submit submit;
    struct io_ring_ctx * ctx;
    struct list_head list;
    struct list_head link_list;
    unsigned int flags;
    refcount_t refs;
    u64 user_data;
    u32 result;
    u32 sequence;
    struct fs_struct * fs;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_kiocb {
    struct file * file;
    struct io_rw rw;
    struct io_poll_iocb poll;
    struct io_accept accept;
    struct io_sync sync;
    struct io_cancel cancel;
    struct io_timeout timeout;
    struct io_connect connect;
    struct io_sr_msg sr_msg;
    struct io_open open;
    struct io_close close;
    struct io_files_update files_update;
    struct io_fadvise fadvise;
    struct io_madvise madvise;
    struct io_epoll epoll;
    struct io_splice splice;
    struct io_provide_buf pbuf;
    struct io_statx statx;
    struct io_async_ctx * io;
    int cflags;
    u8 opcode;
    u8 iopoll_completed;
    u16 buf_index;
    struct io_ring_ctx * ctx;
    struct list_head list;
    unsigned int flags;
    refcount_t refs;
    struct task_struct * task;
    long unsigned int fsize;
    u64 user_data;
    u32 result;
    u32 sequence;
    struct list_head link_list;
    struct list_head inflight_entry;
    struct percpu_ref * fixed_file_refs;
    struct hlist_node hash_node;
    struct async_poll * apoll;
    struct io_wq_work work;
    struct callback_head task_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct io_kiocb {
    struct file * file;
    struct io_rw rw;
    struct io_poll_iocb poll;
    struct io_poll_remove poll_remove;
    struct io_accept accept;
    struct io_sync sync;
    struct io_cancel cancel;
    struct io_timeout timeout;
    struct io_timeout_rem timeout_rem;
    struct io_connect connect;
    struct io_sr_msg sr_msg;
    struct io_open open;
    struct io_close close;
    struct io_files_update files_update;
    struct io_fadvise fadvise;
    struct io_madvise madvise;
    struct io_epoll epoll;
    struct io_splice splice;
    struct io_provide_buf pbuf;
    struct io_statx statx;
    struct io_shutdown shutdown;
    struct io_rename rename;
    struct io_unlink unlink;
    struct io_completion compl;
    void * async_data;
    u8 opcode;
    u8 iopoll_completed;
    u16 buf_index;
    u32 result;
    struct io_ring_ctx * ctx;
    unsigned int flags;
    refcount_t refs;
    struct task_struct * task;
    u64 user_data;
    struct io_kiocb * link;
    struct percpu_ref * fixed_file_refs;
    struct list_head inflight_entry;
    struct callback_head task_work;
    struct hlist_node hash_node;
    struct async_poll * apoll;
    struct io_wq_work work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct io_kiocb {
    struct file * file;
    struct io_rw rw;
    struct io_poll_iocb poll;
    struct io_poll_update poll_update;
    struct io_accept accept;
    struct io_sync sync;
    struct io_cancel cancel;
    struct io_timeout timeout;
    struct io_timeout_rem timeout_rem;
    struct io_connect connect;
    struct io_sr_msg sr_msg;
    struct io_open open;
    struct io_close close;
    struct io_rsrc_update rsrc_update;
    struct io_fadvise fadvise;
    struct io_madvise madvise;
    struct io_epoll epoll;
    struct io_splice splice;
    struct io_provide_buf pbuf;
    struct io_statx statx;
    struct io_shutdown shutdown;
    struct io_rename rename;
    struct io_unlink unlink;
    struct io_completion compl;
    void * async_data;
    u8 opcode;
    u8 iopoll_completed;
    u16 buf_index;
    u32 result;
    struct io_ring_ctx * ctx;
    unsigned int flags;
    atomic_t refs;
    struct task_struct * task;
    u64 user_data;
    struct io_kiocb * link;
    struct percpu_ref * fixed_rsrc_refs;
    struct list_head inflight_entry;
    struct io_task_work io_task_work;
    struct callback_head task_work;
    struct hlist_node hash_node;
    struct async_poll * apoll;
    struct io_wq_work work;
    const struct cred * creds;
    struct io_mapped_ubuf * imu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_kiocb {
    struct file * file;
    struct io_rw rw;
    struct io_poll_iocb poll;
    struct io_poll_update poll_update;
    struct io_accept accept;
    struct io_sync sync;
    struct io_cancel cancel;
    struct io_timeout timeout;
    struct io_timeout_rem timeout_rem;
    struct io_connect connect;
    struct io_sr_msg sr_msg;
    struct io_open open;
    struct io_close close;
    struct io_rsrc_update rsrc_update;
    struct io_fadvise fadvise;
    struct io_madvise madvise;
    struct io_epoll epoll;
    struct io_splice splice;
    struct io_provide_buf pbuf;
    struct io_statx statx;
    struct io_shutdown shutdown;
    struct io_rename rename;
    struct io_unlink unlink;
    struct io_mkdir mkdir;
    struct io_symlink symlink;
    struct io_hardlink hardlink;
    struct io_completion compl;
    void * async_data;
    u8 opcode;
    u8 iopoll_completed;
    u16 buf_index;
    u32 result;
    struct io_ring_ctx * ctx;
    unsigned int flags;
    atomic_t refs;
    struct task_struct * task;
    u64 user_data;
    struct io_kiocb * link;
    struct percpu_ref * fixed_rsrc_refs;
    struct list_head inflight_entry;
    struct io_task_work io_task_work;
    struct hlist_node hash_node;
    struct async_poll * apoll;
    struct io_wq_work work;
    const struct cred * creds;
    struct io_mapped_ubuf * imu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_kiocb {
    struct file * file;
    struct io_rw rw;
    struct io_poll_iocb poll;
    struct io_poll_update poll_update;
    struct io_accept accept;
    struct io_sync sync;
    struct io_cancel cancel;
    struct io_timeout timeout;
    struct io_timeout_rem timeout_rem;
    struct io_connect connect;
    struct io_sr_msg sr_msg;
    struct io_open open;
    struct io_close close;
    struct io_rsrc_update rsrc_update;
    struct io_fadvise fadvise;
    struct io_madvise madvise;
    struct io_epoll epoll;
    struct io_splice splice;
    struct io_provide_buf pbuf;
    struct io_statx statx;
    struct io_shutdown shutdown;
    struct io_rename rename;
    struct io_unlink unlink;
    struct io_mkdir mkdir;
    struct io_symlink symlink;
    struct io_hardlink hardlink;
    struct io_msg msg;
    struct io_xattr xattr;
    struct io_socket sock;
    struct io_uring_cmd uring_cmd;
    u8 opcode;
    u8 iopoll_completed;
    u16 buf_index;
    unsigned int flags;
    struct io_cqe cqe;
    struct io_ring_ctx * ctx;
    struct task_struct * task;
    struct io_rsrc_node * rsrc_node;
    struct io_mapped_ubuf * imu;
    struct io_buffer * kbuf;
    struct io_buffer_list * buf_list;
    struct io_wq_work_node comp_list;
    __poll_t apoll_events;
    atomic_t refs;
    atomic_t poll_refs;
    struct io_task_work io_task_work;
    struct hlist_node hash_node;
    u64 extra1;
    u64 extra2;
    struct async_poll * apoll;
    void * async_data;
    struct io_kiocb * link;
    const struct cred * creds;
    struct io_wq_work work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct io_kiocb {
    struct file * file;
    struct io_cmd_data cmd;
    u8 opcode;
    u8 iopoll_completed;
    u16 buf_index;
    unsigned int flags;
    struct io_cqe cqe;
    struct io_ring_ctx * ctx;
    struct task_struct * task;
    struct io_rsrc_node * rsrc_node;
    struct io_mapped_ubuf * imu;
    struct io_buffer * kbuf;
    struct io_buffer_list * buf_list;
    struct io_wq_work_node comp_list;
    __poll_t apoll_events;
    atomic_t refs;
    atomic_t poll_refs;
    struct io_task_work io_task_work;
    struct hlist_node hash_node;
    u64 extra1;
    u64 extra2;
    struct async_poll * apoll;
    void * async_data;
    struct io_kiocb * link;
    const struct cred * creds;
    struct io_wq_work work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct io_kiocb {
    struct file * file;
    struct io_cmd_data cmd;
    u8 opcode;
    u8 iopoll_completed;
    u16 buf_index;
    unsigned int flags;
    struct io_cqe cqe;
    struct io_ring_ctx * ctx;
    struct task_struct * task;
    struct io_rsrc_node * rsrc_node;
    struct io_mapped_ubuf * imu;
    struct io_buffer * kbuf;
    struct io_buffer_list * buf_list;
    struct io_wq_work_node comp_list;
    __poll_t apoll_events;
    atomic_t refs;
    atomic_t poll_refs;
    struct io_task_work io_task_work;
    unsigned int nr_tw;
    struct hlist_node hash_node;
    u64 extra1;
    u64 extra2;
    struct async_poll * apoll;
    void * async_data;
    struct io_kiocb * link;
    const struct cred * creds;
    struct io_wq_work work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct io_kiocb {
    struct file * file;
    struct io_cmd_data cmd;
    u8 opcode;
    u8 iopoll_completed;
    u16 buf_index;
    unsigned int flags;
    struct io_cqe cqe;
    struct io_ring_ctx * ctx;
    struct task_struct * task;
    struct io_rsrc_node * rsrc_node;
    struct io_mapped_ubuf * imu;
    struct io_buffer * kbuf;
    struct io_buffer_list * buf_list;
    struct io_wq_work_node comp_list;
    __poll_t apoll_events;
    atomic_t refs;
    atomic_t poll_refs;
    struct io_task_work io_task_work;
    unsigned int nr_tw;
    struct hlist_node hash_node;
    struct async_poll * apoll;
    void * async_data;
    struct io_kiocb * link;
    const struct cred * creds;
    struct io_wq_work work;
    struct (anon) big_cqe;
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
struct io_kiocb {
    struct file * file;
    struct kiocb rw;
    struct io_poll_iocb poll;
    struct io_timeout timeout;
    struct sqe_submit submit;
    struct io_ring_ctx * ctx;
    struct list_head list;
    struct list_head link_list;
    unsigned int flags;
    refcount_t refs;
    u64 user_data;
    u32 result;
    u32 sequence;
    struct fs_struct * fs;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct io_kiocb {
    struct file * file;
    struct kiocb rw;
    struct io_poll_iocb poll;
    struct io_timeout timeout;
    struct sqe_submit submit;
    struct io_ring_ctx * ctx;
    struct list_head list;
    struct list_head link_list;
    unsigned int flags;
    refcount_t refs;
    u64 user_data;
    u32 result;
    u32 sequence;
    struct fs_struct * fs;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct io_kiocb {
    struct file * file;
    struct kiocb rw;
    struct io_poll_iocb poll;
    struct io_timeout timeout;
    struct sqe_submit submit;
    struct io_ring_ctx * ctx;
    struct list_head list;
    struct list_head link_list;
    unsigned int flags;
    refcount_t refs;
    u64 user_data;
    u32 result;
    u32 sequence;
    struct fs_struct * fs;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct io_kiocb {
    struct file * file;
    struct kiocb rw;
    struct io_poll_iocb poll;
    struct io_timeout timeout;
    struct sqe_submit submit;
    struct io_ring_ctx * ctx;
    struct list_head list;
    struct list_head link_list;
    unsigned int flags;
    refcount_t refs;
    u64 user_data;
    u32 result;
    u32 sequence;
    struct fs_struct * fs;
    struct work_struct work;
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
struct io_kiocb {
    struct file * file;
    struct kiocb rw;
    struct io_poll_iocb poll;
    struct io_timeout timeout;
    struct sqe_submit submit;
    struct io_ring_ctx * ctx;
    struct list_head list;
    struct list_head link_list;
    unsigned int flags;
    refcount_t refs;
    u64 user_data;
    u32 result;
    u32 sequence;
    struct fs_struct * fs;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct io_kiocb {
    struct file * file;
    struct kiocb rw;
    struct io_poll_iocb poll;
    struct io_timeout timeout;
    struct sqe_submit submit;
    struct io_ring_ctx * ctx;
    struct list_head list;
    struct list_head link_list;
    unsigned int flags;
    refcount_t refs;
    u64 user_data;
    u32 result;
    u32 sequence;
    struct fs_struct * fs;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct io_kiocb {
    struct file * file;
    struct kiocb rw;
    struct io_poll_iocb poll;
    struct io_timeout timeout;
    struct sqe_submit submit;
    struct io_ring_ctx * ctx;
    struct list_head list;
    struct list_head link_list;
    unsigned int flags;
    refcount_t refs;
    u64 user_data;
    u32 result;
    u32 sequence;
    struct fs_struct * fs;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct io_kiocb {
    struct file * file;
    struct kiocb rw;
    struct io_poll_iocb poll;
    struct io_timeout timeout;
    struct sqe_submit submit;
    struct io_ring_ctx * ctx;
    struct list_head list;
    struct list_head link_list;
    unsigned int flags;
    refcount_t refs;
    u64 user_data;
    u32 result;
    u32 sequence;
    struct fs_struct * fs;
    struct work_struct work;
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct io_kiocb {
    struct file * file;
    struct kiocb rw;
    struct io_poll_iocb poll;
    struct sqe_submit submit;
    struct io_ring_ctx * ctx;
    struct list_head list;
    struct list_head link_list;
    unsigned int flags;
    refcount_t refs;
    u64 user_data;
    u32 result;
    u32 sequence;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct io_timeout timeout</code>
</li>
<li>
<b>Field added. </b>
<code>struct fs_struct * fs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct io_accept accept</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_sync sync</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_cancel cancel</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_connect connect</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_sr_msg sr_msg</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_open open</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_close close</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_files_update files_update</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_fadvise fadvise</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_madvise madvise</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_epoll epoll</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_splice splice</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_provide_buf pbuf</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_statx statx</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_async_ctx * io</code>
</li>
<li>
<b>Field added. </b>
<code>int cflags</code>
</li>
<li>
<b>Field added. </b>
<code>u8 opcode</code>
</li>
<li>
<b>Field added. </b>
<code>u8 iopoll_completed</code>
</li>
<li>
<b>Field added. </b>
<code>u16 buf_index</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_struct * task</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int fsize</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head inflight_entry</code>
</li>
<li>
<b>Field added. </b>
<code>struct percpu_ref * fixed_file_refs</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_node hash_node</code>
</li>
<li>
<b>Field added. </b>
<code>struct async_poll * apoll</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head task_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sqe_submit submit</code>
</li>
<li>
<b>Field removed. </b>
<code>struct fs_struct * fs</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct kiocb rw</code> ➡️ <code>struct io_rw rw</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct work_struct work</code> ➡️ <code>struct io_wq_work work</code>
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
<code>struct io_poll_remove poll_remove</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_timeout_rem timeout_rem</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_shutdown shutdown</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_rename rename</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_unlink unlink</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_completion compl</code>
</li>
<li>
<b>Field added. </b>
<code>void * async_data</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_kiocb * link</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_async_ctx * io</code>
</li>
<li>
<b>Field removed. </b>
<code>int cflags</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int fsize</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 sequence</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head link_list</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct io_poll_update poll_update</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_rsrc_update rsrc_update</code>
</li>
<li>
<b>Field added. </b>
<code>struct percpu_ref * fixed_rsrc_refs</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_task_work io_task_work</code>
</li>
<li>
<b>Field added. </b>
<code>const struct cred * creds</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_mapped_ubuf * imu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_poll_remove poll_remove</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_files_update files_update</code>
</li>
<li>
<b>Field removed. </b>
<code>struct percpu_ref * fixed_file_refs</code>
</li>
<li>
<b>Field type changed. </b>
<code>refcount_t refs</code> ➡️ <code>atomic_t refs</code>
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
<code>struct io_mkdir mkdir</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_symlink symlink</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_hardlink hardlink</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head task_work</code>
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
<code>struct io_msg msg</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_xattr xattr</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_socket sock</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_uring_cmd uring_cmd</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_cqe cqe</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_rsrc_node * rsrc_node</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_buffer * kbuf</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_buffer_list * buf_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_wq_work_node comp_list</code>
</li>
<li>
<b>Field added. </b>
<code>__poll_t apoll_events</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t poll_refs</code>
</li>
<li>
<b>Field added. </b>
<code>u64 extra1</code>
</li>
<li>
<b>Field added. </b>
<code>u64 extra2</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_completion compl</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 result</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 user_data</code>
</li>
<li>
<b>Field removed. </b>
<code>struct percpu_ref * fixed_rsrc_refs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head inflight_entry</code>
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
<code>struct io_cmd_data cmd</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_rw rw</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_poll_iocb poll</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_poll_update poll_update</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_accept accept</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_sync sync</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_cancel cancel</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_timeout timeout</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_timeout_rem timeout_rem</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_connect connect</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_sr_msg sr_msg</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_open open</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_close close</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_rsrc_update rsrc_update</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_fadvise fadvise</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_madvise madvise</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_epoll epoll</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_splice splice</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_provide_buf pbuf</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_statx statx</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_shutdown shutdown</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_rename rename</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_unlink unlink</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_mkdir mkdir</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_symlink symlink</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_hardlink hardlink</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_msg msg</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_xattr xattr</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_socket sock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_uring_cmd uring_cmd</code>
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
<code>unsigned int nr_tw</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct (anon) big_cqe</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 extra1</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 extra2</code>
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
