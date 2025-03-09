# Struct: <code>io_ring_ctx</code>

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
struct io_ring_ctx {
    struct percpu_ref refs;
    unsigned int flags;
    bool compat;
    bool account_mem;
    struct io_sq_ring * sq_ring;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    unsigned int sq_mask;
    unsigned int sq_thread_idle;
    struct io_uring_sqe * sq_sqes;
    struct list_head defer_list;
    struct workqueue_struct * sqo_wq;
    struct task_struct * sqo_thread;
    struct mm_struct * sqo_mm;
    wait_queue_head_t sqo_wait;
    struct completion sqo_thread_started;
    struct io_cq_ring * cq_ring;
    unsigned int cached_cq_tail;
    unsigned int cq_entries;
    unsigned int cq_mask;
    struct wait_queue_head cq_wait;
    struct fasync_struct * cq_fasync;
    struct eventfd_ctx * cq_ev_fd;
    struct file * * user_files;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * user_bufs;
    struct user_struct * user;
    struct completion ctx_done;
    struct mutex uring_lock;
    wait_queue_head_t wait;
    spinlock_t completion_lock;
    bool poll_multi_file;
    struct list_head poll_list;
    struct list_head cancel_list;
    struct async_list[2] pending_async;
    struct socket * ring_sock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct io_ring_ctx {
    struct percpu_ref refs;
    unsigned int flags;
    bool compat;
    bool account_mem;
    u32 * sq_array;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    unsigned int sq_mask;
    unsigned int sq_thread_idle;
    unsigned int cached_sq_dropped;
    struct io_uring_sqe * sq_sqes;
    struct list_head defer_list;
    struct list_head timeout_list;
    struct workqueue_struct *[2] sqo_wq;
    struct task_struct * sqo_thread;
    struct mm_struct * sqo_mm;
    wait_queue_head_t sqo_wait;
    struct completion sqo_thread_started;
    unsigned int cached_cq_tail;
    atomic_t cached_cq_overflow;
    unsigned int cq_entries;
    unsigned int cq_mask;
    struct wait_queue_head cq_wait;
    struct fasync_struct * cq_fasync;
    struct eventfd_ctx * cq_ev_fd;
    atomic_t cq_timeouts;
    struct io_rings * rings;
    struct file * * user_files;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * user_bufs;
    struct user_struct * user;
    const struct cred * creds;
    struct completion ctx_done;
    struct mutex uring_lock;
    wait_queue_head_t wait;
    spinlock_t completion_lock;
    bool poll_multi_file;
    struct list_head poll_list;
    struct list_head cancel_list;
    struct async_list[2] pending_async;
    struct socket * ring_sock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_ring_ctx {
    struct percpu_ref refs;
    unsigned int flags;
    unsigned int compat;
    unsigned int account_mem;
    unsigned int cq_overflow_flushed;
    unsigned int drain_next;
    unsigned int eventfd_async;
    u32 * sq_array;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    unsigned int sq_mask;
    unsigned int sq_thread_idle;
    unsigned int cached_sq_dropped;
    atomic_t cached_cq_overflow;
    long unsigned int sq_check_overflow;
    struct list_head defer_list;
    struct list_head timeout_list;
    struct list_head cq_overflow_list;
    wait_queue_head_t inflight_wait;
    struct io_uring_sqe * sq_sqes;
    struct io_rings * rings;
    struct io_wq * io_wq;
    struct task_struct * sqo_thread;
    struct mm_struct * sqo_mm;
    wait_queue_head_t sqo_wait;
    struct fixed_file_data * file_data;
    unsigned int nr_user_files;
    int ring_fd;
    struct file * ring_file;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * user_bufs;
    struct user_struct * user;
    const struct cred * creds;
    struct completion ref_comp;
    struct completion sq_thread_comp;
    struct io_kiocb * fallback_req;
    struct socket * ring_sock;
    struct idr io_buffer_idr;
    struct idr personality_idr;
    unsigned int cached_cq_tail;
    unsigned int cq_entries;
    unsigned int cq_mask;
    atomic_t cq_timeouts;
    long unsigned int cq_check_overflow;
    struct wait_queue_head cq_wait;
    struct fasync_struct * cq_fasync;
    struct eventfd_ctx * cq_ev_fd;
    struct mutex uring_lock;
    wait_queue_head_t wait;
    spinlock_t completion_lock;
    struct list_head poll_list;
    struct hlist_head * cancel_hash;
    unsigned int cancel_hash_bits;
    bool poll_multi_file;
    spinlock_t inflight_lock;
    struct list_head inflight_list;
    struct delayed_work file_put_work;
    struct llist_head file_put_llist;
    struct work_struct exit_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct io_ring_ctx {
    struct percpu_ref refs;
    unsigned int flags;
    unsigned int compat;
    unsigned int limit_mem;
    unsigned int cq_overflow_flushed;
    unsigned int drain_next;
    unsigned int eventfd_async;
    unsigned int restricted;
    unsigned int sqo_dead;
    u32 * sq_array;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    unsigned int sq_mask;
    unsigned int sq_thread_idle;
    unsigned int cached_sq_dropped;
    unsigned int cached_cq_overflow;
    long unsigned int sq_check_overflow;
    struct list_head defer_list;
    struct list_head timeout_list;
    struct list_head cq_overflow_list;
    struct io_uring_sqe * sq_sqes;
    struct io_rings * rings;
    struct io_wq * io_wq;
    struct task_struct * sqo_task;
    struct mm_struct * mm_account;
    struct cgroup_subsys_state * sqo_blkcg_css;
    struct io_sq_data * sq_data;
    struct wait_queue_head sqo_sq_wait;
    struct list_head sqd_list;
    struct fixed_file_data * file_data;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * user_bufs;
    struct user_struct * user;
    const struct cred * creds;
    kuid_t loginuid;
    unsigned int sessionid;
    struct completion ref_comp;
    struct completion sq_thread_comp;
    struct io_kiocb * fallback_req;
    struct socket * ring_sock;
    struct idr io_buffer_idr;
    struct idr personality_idr;
    unsigned int cached_cq_tail;
    unsigned int cq_entries;
    unsigned int cq_mask;
    atomic_t cq_timeouts;
    unsigned int cq_last_tm_flush;
    long unsigned int cq_check_overflow;
    struct wait_queue_head cq_wait;
    struct fasync_struct * cq_fasync;
    struct eventfd_ctx * cq_ev_fd;
    struct mutex uring_lock;
    wait_queue_head_t wait;
    spinlock_t completion_lock;
    struct list_head iopoll_list;
    struct hlist_head * cancel_hash;
    unsigned int cancel_hash_bits;
    bool poll_multi_file;
    spinlock_t inflight_lock;
    struct list_head inflight_list;
    struct delayed_work file_put_work;
    struct llist_head file_put_llist;
    struct work_struct exit_work;
    struct io_restriction restrictions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct io_ring_ctx {
    struct percpu_ref refs;
    unsigned int flags;
    unsigned int compat;
    unsigned int drain_next;
    unsigned int eventfd_async;
    unsigned int restricted;
    u32 * sq_array;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    unsigned int sq_mask;
    unsigned int sq_thread_idle;
    unsigned int cached_sq_dropped;
    unsigned int cached_cq_overflow;
    long unsigned int sq_check_overflow;
    struct list_head defer_list;
    struct list_head timeout_list;
    struct list_head cq_overflow_list;
    struct io_uring_sqe * sq_sqes;
    struct mutex uring_lock;
    wait_queue_head_t wait;
    struct io_submit_state submit_state;
    struct list_head locked_free_list;
    unsigned int locked_free_nr;
    struct io_rings * rings;
    const struct cred * sq_creds;
    struct io_sq_data * sq_data;
    struct wait_queue_head sqo_sq_wait;
    struct list_head sqd_list;
    struct io_rsrc_data * file_data;
    struct io_file_table file_table;
    unsigned int nr_user_files;
    struct io_rsrc_data * buf_data;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * * user_bufs;
    struct xarray io_buffers;
    struct xarray personalities;
    u32 pers_next;
    unsigned int cached_cq_tail;
    unsigned int cq_entries;
    unsigned int cq_mask;
    atomic_t cq_timeouts;
    unsigned int cq_last_tm_flush;
    unsigned int cq_extra;
    long unsigned int cq_check_overflow;
    struct wait_queue_head cq_wait;
    struct fasync_struct * cq_fasync;
    struct eventfd_ctx * cq_ev_fd;
    spinlock_t completion_lock;
    struct list_head iopoll_list;
    struct hlist_head * cancel_hash;
    unsigned int cancel_hash_bits;
    bool poll_multi_file;
    struct delayed_work rsrc_put_work;
    struct llist_head rsrc_put_llist;
    struct list_head rsrc_ref_list;
    spinlock_t rsrc_ref_lock;
    struct io_rsrc_node * rsrc_node;
    struct io_rsrc_node * rsrc_backup_node;
    struct io_mapped_ubuf * dummy_ubuf;
    struct io_restriction restrictions;
    struct socket * ring_sock;
    struct io_wq_hash * hash_map;
    struct user_struct * user;
    struct mm_struct * mm_account;
    struct callback_head * exit_task_work;
    struct work_struct exit_work;
    struct list_head tctx_list;
    struct completion ref_comp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_ring_ctx {
    struct percpu_ref refs;
    struct io_rings * rings;
    unsigned int flags;
    unsigned int compat;
    unsigned int drain_next;
    unsigned int eventfd_async;
    unsigned int restricted;
    unsigned int off_timeout_used;
    unsigned int drain_active;
    struct mutex uring_lock;
    u32 * sq_array;
    struct io_uring_sqe * sq_sqes;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    struct list_head defer_list;
    struct io_rsrc_node * rsrc_node;
    struct io_file_table file_table;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * * user_bufs;
    struct io_submit_state submit_state;
    struct list_head timeout_list;
    struct list_head ltimeout_list;
    struct list_head cq_overflow_list;
    struct xarray io_buffers;
    struct xarray personalities;
    u32 pers_next;
    unsigned int sq_thread_idle;
    struct list_head locked_free_list;
    unsigned int locked_free_nr;
    const struct cred * sq_creds;
    struct io_sq_data * sq_data;
    struct wait_queue_head sqo_sq_wait;
    struct list_head sqd_list;
    long unsigned int check_cq_overflow;
    unsigned int cached_cq_tail;
    unsigned int cq_entries;
    struct eventfd_ctx * cq_ev_fd;
    struct wait_queue_head poll_wait;
    struct wait_queue_head cq_wait;
    unsigned int cq_extra;
    atomic_t cq_timeouts;
    unsigned int cq_last_tm_flush;
    spinlock_t completion_lock;
    spinlock_t timeout_lock;
    struct list_head iopoll_list;
    struct hlist_head * cancel_hash;
    unsigned int cancel_hash_bits;
    bool poll_multi_queue;
    struct io_restriction restrictions;
    struct io_rsrc_node * rsrc_backup_node;
    struct io_mapped_ubuf * dummy_ubuf;
    struct io_rsrc_data * file_data;
    struct io_rsrc_data * buf_data;
    struct delayed_work rsrc_put_work;
    struct llist_head rsrc_put_llist;
    struct list_head rsrc_ref_list;
    spinlock_t rsrc_ref_lock;
    struct socket * ring_sock;
    struct io_wq_hash * hash_map;
    struct user_struct * user;
    struct mm_struct * mm_account;
    struct llist_head fallback_llist;
    struct delayed_work fallback_work;
    struct work_struct exit_work;
    struct list_head tctx_list;
    struct completion ref_comp;
    u32[2] iowq_limits;
    bool iowq_limits_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_ring_ctx {
    struct percpu_ref refs;
    struct io_rings * rings;
    unsigned int flags;
    enum task_work_notify_mode notify_method;
    unsigned int compat;
    unsigned int drain_next;
    unsigned int restricted;
    unsigned int off_timeout_used;
    unsigned int drain_active;
    unsigned int drain_disabled;
    unsigned int has_evfd;
    unsigned int syscall_iopoll;
    struct mutex uring_lock;
    u32 * sq_array;
    struct io_uring_sqe * sq_sqes;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    struct list_head defer_list;
    struct io_rsrc_node * rsrc_node;
    int rsrc_cached_refs;
    atomic_t cancel_seq;
    struct io_file_table file_table;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * * user_bufs;
    struct io_submit_state submit_state;
    struct io_buffer_list * io_bl;
    struct xarray io_bl_xa;
    struct list_head io_buffers_cache;
    struct list_head timeout_list;
    struct list_head ltimeout_list;
    struct list_head cq_overflow_list;
    struct list_head apoll_cache;
    struct xarray personalities;
    u32 pers_next;
    unsigned int sq_thread_idle;
    struct io_wq_work_list locked_free_list;
    unsigned int locked_free_nr;
    const struct cred * sq_creds;
    struct io_sq_data * sq_data;
    struct wait_queue_head sqo_sq_wait;
    struct list_head sqd_list;
    long unsigned int check_cq;
    struct io_uring_cqe * cqe_cached;
    struct io_uring_cqe * cqe_sentinel;
    unsigned int cached_cq_tail;
    unsigned int cq_entries;
    struct io_ev_fd * io_ev_fd;
    struct wait_queue_head cq_wait;
    unsigned int cq_extra;
    atomic_t cq_timeouts;
    unsigned int cq_last_tm_flush;
    spinlock_t completion_lock;
    spinlock_t timeout_lock;
    struct io_wq_work_list iopoll_list;
    struct hlist_head * cancel_hash;
    unsigned int cancel_hash_bits;
    bool poll_multi_queue;
    struct list_head io_buffers_comp;
    struct io_restriction restrictions;
    struct io_rsrc_node * rsrc_backup_node;
    struct io_mapped_ubuf * dummy_ubuf;
    struct io_rsrc_data * file_data;
    struct io_rsrc_data * buf_data;
    struct delayed_work rsrc_put_work;
    struct llist_head rsrc_put_llist;
    struct list_head rsrc_ref_list;
    spinlock_t rsrc_ref_lock;
    struct list_head io_buffers_pages;
    struct socket * ring_sock;
    struct io_wq_hash * hash_map;
    struct user_struct * user;
    struct mm_struct * mm_account;
    struct llist_head fallback_llist;
    struct delayed_work fallback_work;
    struct work_struct exit_work;
    struct list_head tctx_list;
    struct completion ref_comp;
    u32[2] iowq_limits;
    bool iowq_limits_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct io_ring_ctx {
    struct percpu_ref refs;
    struct io_rings * rings;
    unsigned int flags;
    enum task_work_notify_mode notify_method;
    unsigned int compat;
    unsigned int drain_next;
    unsigned int restricted;
    unsigned int off_timeout_used;
    unsigned int drain_active;
    unsigned int drain_disabled;
    unsigned int has_evfd;
    unsigned int syscall_iopoll;
    unsigned int task_complete;
    struct mutex uring_lock;
    u32 * sq_array;
    struct io_uring_sqe * sq_sqes;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    struct io_rsrc_node * rsrc_node;
    int rsrc_cached_refs;
    atomic_t cancel_seq;
    struct io_file_table file_table;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * * user_bufs;
    struct io_submit_state submit_state;
    struct io_buffer_list * io_bl;
    struct xarray io_bl_xa;
    struct list_head io_buffers_cache;
    struct io_hash_table cancel_table_locked;
    struct list_head cq_overflow_list;
    struct io_alloc_cache apoll_cache;
    struct io_alloc_cache netmsg_cache;
    struct io_wq_work_list locked_free_list;
    unsigned int locked_free_nr;
    const struct cred * sq_creds;
    struct io_sq_data * sq_data;
    struct wait_queue_head sqo_sq_wait;
    struct list_head sqd_list;
    long unsigned int check_cq;
    unsigned int file_alloc_start;
    unsigned int file_alloc_end;
    struct xarray personalities;
    u32 pers_next;
    struct io_uring_cqe * cqe_cached;
    struct io_uring_cqe * cqe_sentinel;
    unsigned int cached_cq_tail;
    unsigned int cq_entries;
    struct io_ev_fd * io_ev_fd;
    struct wait_queue_head cq_wait;
    unsigned int cq_extra;
    spinlock_t completion_lock;
    bool poll_multi_queue;
    struct io_wq_work_list iopoll_list;
    struct io_hash_table cancel_table;
    struct llist_head work_llist;
    struct list_head io_buffers_comp;
    spinlock_t timeout_lock;
    atomic_t cq_timeouts;
    struct list_head timeout_list;
    struct list_head ltimeout_list;
    unsigned int cq_last_tm_flush;
    struct io_restriction restrictions;
    struct task_struct * submitter_task;
    struct io_rsrc_node * rsrc_backup_node;
    struct io_mapped_ubuf * dummy_ubuf;
    struct io_rsrc_data * file_data;
    struct io_rsrc_data * buf_data;
    struct delayed_work rsrc_put_work;
    struct callback_head rsrc_put_tw;
    struct llist_head rsrc_put_llist;
    struct list_head rsrc_ref_list;
    spinlock_t rsrc_ref_lock;
    struct list_head io_buffers_pages;
    struct socket * ring_sock;
    struct io_wq_hash * hash_map;
    struct user_struct * user;
    struct mm_struct * mm_account;
    struct llist_head fallback_llist;
    struct delayed_work fallback_work;
    struct work_struct exit_work;
    struct list_head tctx_list;
    struct completion ref_comp;
    u32[2] iowq_limits;
    bool iowq_limits_set;
    struct list_head defer_list;
    unsigned int sq_thread_idle;
    unsigned int evfd_last_cq_tail;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct io_ring_ctx {
    unsigned int flags;
    unsigned int drain_next;
    unsigned int restricted;
    unsigned int off_timeout_used;
    unsigned int drain_active;
    unsigned int has_evfd;
    unsigned int task_complete;
    unsigned int syscall_iopoll;
    unsigned int poll_activated;
    unsigned int drain_disabled;
    unsigned int compat;
    enum task_work_notify_mode notify_method;
    short unsigned int n_ring_pages;
    short unsigned int n_sqe_pages;
    struct page * * ring_pages;
    struct page * * sqe_pages;
    struct io_rings * rings;
    struct task_struct * submitter_task;
    struct percpu_ref refs;
    struct mutex uring_lock;
    u32 * sq_array;
    struct io_uring_sqe * sq_sqes;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    struct io_rsrc_node * rsrc_node;
    atomic_t cancel_seq;
    struct io_file_table file_table;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * * user_bufs;
    struct io_submit_state submit_state;
    struct io_buffer_list * io_bl;
    struct xarray io_bl_xa;
    struct list_head io_buffers_cache;
    struct io_hash_table cancel_table_locked;
    struct list_head cq_overflow_list;
    struct io_alloc_cache apoll_cache;
    struct io_alloc_cache netmsg_cache;
    struct io_wq_work_list locked_free_list;
    unsigned int locked_free_nr;
    const struct cred * sq_creds;
    struct io_sq_data * sq_data;
    struct wait_queue_head sqo_sq_wait;
    struct list_head sqd_list;
    long unsigned int check_cq;
    unsigned int file_alloc_start;
    unsigned int file_alloc_end;
    struct xarray personalities;
    u32 pers_next;
    struct io_uring_cqe * cqe_cached;
    struct io_uring_cqe * cqe_sentinel;
    unsigned int cached_cq_tail;
    unsigned int cq_entries;
    struct io_ev_fd * io_ev_fd;
    struct wait_queue_head cq_wait;
    unsigned int cq_extra;
    spinlock_t completion_lock;
    bool poll_multi_queue;
    atomic_t cq_wait_nr;
    struct io_wq_work_list iopoll_list;
    struct io_hash_table cancel_table;
    struct llist_head work_llist;
    struct list_head io_buffers_comp;
    spinlock_t timeout_lock;
    atomic_t cq_timeouts;
    struct list_head timeout_list;
    struct list_head ltimeout_list;
    unsigned int cq_last_tm_flush;
    struct wait_queue_head poll_wq;
    struct io_restriction restrictions;
    struct io_mapped_ubuf * dummy_ubuf;
    struct io_rsrc_data * file_data;
    struct io_rsrc_data * buf_data;
    struct list_head rsrc_ref_list;
    struct io_alloc_cache rsrc_node_cache;
    struct wait_queue_head rsrc_quiesce_wq;
    unsigned int rsrc_quiesce;
    struct list_head io_buffers_pages;
    struct socket * ring_sock;
    struct io_wq_hash * hash_map;
    struct user_struct * user;
    struct mm_struct * mm_account;
    struct llist_head fallback_llist;
    struct delayed_work fallback_work;
    struct work_struct exit_work;
    struct list_head tctx_list;
    struct completion ref_comp;
    u32[2] iowq_limits;
    bool iowq_limits_set;
    struct callback_head poll_wq_task_work;
    struct list_head defer_list;
    unsigned int sq_thread_idle;
    unsigned int evfd_last_cq_tail;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct io_ring_ctx {
    unsigned int flags;
    unsigned int drain_next;
    unsigned int restricted;
    unsigned int off_timeout_used;
    unsigned int drain_active;
    unsigned int has_evfd;
    unsigned int task_complete;
    unsigned int lockless_cq;
    unsigned int syscall_iopoll;
    unsigned int poll_activated;
    unsigned int drain_disabled;
    unsigned int compat;
    struct task_struct * submitter_task;
    struct io_rings * rings;
    struct percpu_ref refs;
    enum task_work_notify_mode notify_method;
    struct mutex uring_lock;
    u32 * sq_array;
    struct io_uring_sqe * sq_sqes;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    struct io_rsrc_node * rsrc_node;
    atomic_t cancel_seq;
    struct io_file_table file_table;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * * user_bufs;
    struct io_submit_state submit_state;
    struct io_buffer_list * io_bl;
    struct xarray io_bl_xa;
    struct io_hash_table cancel_table_locked;
    struct io_alloc_cache apoll_cache;
    struct io_alloc_cache netmsg_cache;
    struct io_wq_work_list iopoll_list;
    bool poll_multi_queue;
    struct hlist_head cancelable_uring_cmd;
    struct io_uring_cqe * cqe_cached;
    struct io_uring_cqe * cqe_sentinel;
    unsigned int cached_cq_tail;
    unsigned int cq_entries;
    struct io_ev_fd * io_ev_fd;
    unsigned int cq_extra;
    struct llist_head work_llist;
    long unsigned int check_cq;
    atomic_t cq_wait_nr;
    atomic_t cq_timeouts;
    struct wait_queue_head cq_wait;
    spinlock_t timeout_lock;
    struct list_head timeout_list;
    struct list_head ltimeout_list;
    unsigned int cq_last_tm_flush;
    struct io_uring_cqe[16] completion_cqes;
    spinlock_t completion_lock;
    struct io_wq_work_list locked_free_list;
    unsigned int locked_free_nr;
    struct list_head io_buffers_comp;
    struct list_head cq_overflow_list;
    struct io_hash_table cancel_table;
    struct hlist_head waitid_list;
    struct hlist_head futex_list;
    struct io_alloc_cache futex_cache;
    const struct cred * sq_creds;
    struct io_sq_data * sq_data;
    struct wait_queue_head sqo_sq_wait;
    struct list_head sqd_list;
    unsigned int file_alloc_start;
    unsigned int file_alloc_end;
    struct xarray personalities;
    u32 pers_next;
    struct list_head io_buffers_cache;
    struct hlist_head io_buf_list;
    struct wait_queue_head poll_wq;
    struct io_restriction restrictions;
    struct io_mapped_ubuf * dummy_ubuf;
    struct io_rsrc_data * file_data;
    struct io_rsrc_data * buf_data;
    struct list_head rsrc_ref_list;
    struct io_alloc_cache rsrc_node_cache;
    struct wait_queue_head rsrc_quiesce_wq;
    unsigned int rsrc_quiesce;
    struct io_wq_hash * hash_map;
    struct user_struct * user;
    struct mm_struct * mm_account;
    struct llist_head fallback_llist;
    struct delayed_work fallback_work;
    struct work_struct exit_work;
    struct list_head tctx_list;
    struct completion ref_comp;
    u32[2] iowq_limits;
    bool iowq_limits_set;
    struct callback_head poll_wq_task_work;
    struct list_head defer_list;
    unsigned int sq_thread_idle;
    unsigned int evfd_last_cq_tail;
    short unsigned int n_ring_pages;
    short unsigned int n_sqe_pages;
    struct page * * ring_pages;
    struct page * * sqe_pages;
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
struct io_ring_ctx {
    struct percpu_ref refs;
    unsigned int flags;
    bool compat;
    bool account_mem;
    u32 * sq_array;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    unsigned int sq_mask;
    unsigned int sq_thread_idle;
    unsigned int cached_sq_dropped;
    struct io_uring_sqe * sq_sqes;
    struct list_head defer_list;
    struct list_head timeout_list;
    struct workqueue_struct *[2] sqo_wq;
    struct task_struct * sqo_thread;
    struct mm_struct * sqo_mm;
    wait_queue_head_t sqo_wait;
    struct completion sqo_thread_started;
    unsigned int cached_cq_tail;
    atomic_t cached_cq_overflow;
    unsigned int cq_entries;
    unsigned int cq_mask;
    struct wait_queue_head cq_wait;
    struct fasync_struct * cq_fasync;
    struct eventfd_ctx * cq_ev_fd;
    atomic_t cq_timeouts;
    struct io_rings * rings;
    struct file * * user_files;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * user_bufs;
    struct user_struct * user;
    const struct cred * creds;
    struct completion ctx_done;
    struct mutex uring_lock;
    wait_queue_head_t wait;
    spinlock_t completion_lock;
    bool poll_multi_file;
    struct list_head poll_list;
    struct list_head cancel_list;
    struct async_list[2] pending_async;
    struct socket * ring_sock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct io_ring_ctx {
    struct percpu_ref refs;
    unsigned int flags;
    bool compat;
    bool account_mem;
    u32 * sq_array;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    unsigned int sq_mask;
    unsigned int sq_thread_idle;
    unsigned int cached_sq_dropped;
    struct io_uring_sqe * sq_sqes;
    struct list_head defer_list;
    struct list_head timeout_list;
    struct workqueue_struct *[2] sqo_wq;
    struct task_struct * sqo_thread;
    struct mm_struct * sqo_mm;
    wait_queue_head_t sqo_wait;
    struct completion sqo_thread_started;
    unsigned int cached_cq_tail;
    atomic_t cached_cq_overflow;
    unsigned int cq_entries;
    unsigned int cq_mask;
    struct wait_queue_head cq_wait;
    struct fasync_struct * cq_fasync;
    struct eventfd_ctx * cq_ev_fd;
    atomic_t cq_timeouts;
    struct io_rings * rings;
    struct file * * user_files;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * user_bufs;
    struct user_struct * user;
    const struct cred * creds;
    struct completion ctx_done;
    struct mutex uring_lock;
    wait_queue_head_t wait;
    spinlock_t completion_lock;
    bool poll_multi_file;
    struct list_head poll_list;
    struct list_head cancel_list;
    struct async_list[2] pending_async;
    struct socket * ring_sock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct io_ring_ctx {
    struct percpu_ref refs;
    unsigned int flags;
    bool compat;
    bool account_mem;
    u32 * sq_array;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    unsigned int sq_mask;
    unsigned int sq_thread_idle;
    unsigned int cached_sq_dropped;
    struct io_uring_sqe * sq_sqes;
    struct list_head defer_list;
    struct list_head timeout_list;
    struct workqueue_struct *[2] sqo_wq;
    struct task_struct * sqo_thread;
    struct mm_struct * sqo_mm;
    wait_queue_head_t sqo_wait;
    struct completion sqo_thread_started;
    unsigned int cached_cq_tail;
    atomic_t cached_cq_overflow;
    unsigned int cq_entries;
    unsigned int cq_mask;
    struct wait_queue_head cq_wait;
    struct fasync_struct * cq_fasync;
    struct eventfd_ctx * cq_ev_fd;
    atomic_t cq_timeouts;
    struct io_rings * rings;
    struct file * * user_files;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * user_bufs;
    struct user_struct * user;
    const struct cred * creds;
    struct completion ctx_done;
    struct mutex uring_lock;
    wait_queue_head_t wait;
    spinlock_t completion_lock;
    bool poll_multi_file;
    struct list_head poll_list;
    struct list_head cancel_list;
    struct async_list[2] pending_async;
    struct socket * ring_sock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct io_ring_ctx {
    struct percpu_ref refs;
    unsigned int flags;
    bool compat;
    bool account_mem;
    u32 * sq_array;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    unsigned int sq_mask;
    unsigned int sq_thread_idle;
    unsigned int cached_sq_dropped;
    struct io_uring_sqe * sq_sqes;
    struct list_head defer_list;
    struct list_head timeout_list;
    struct workqueue_struct *[2] sqo_wq;
    struct task_struct * sqo_thread;
    struct mm_struct * sqo_mm;
    wait_queue_head_t sqo_wait;
    struct completion sqo_thread_started;
    unsigned int cached_cq_tail;
    atomic_t cached_cq_overflow;
    unsigned int cq_entries;
    unsigned int cq_mask;
    struct wait_queue_head cq_wait;
    struct fasync_struct * cq_fasync;
    struct eventfd_ctx * cq_ev_fd;
    atomic_t cq_timeouts;
    struct io_rings * rings;
    struct file * * user_files;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * user_bufs;
    struct user_struct * user;
    const struct cred * creds;
    struct completion ctx_done;
    struct mutex uring_lock;
    wait_queue_head_t wait;
    spinlock_t completion_lock;
    bool poll_multi_file;
    struct list_head poll_list;
    struct list_head cancel_list;
    struct async_list[2] pending_async;
    struct socket * ring_sock;
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
struct io_ring_ctx {
    struct percpu_ref refs;
    unsigned int flags;
    bool compat;
    bool account_mem;
    u32 * sq_array;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    unsigned int sq_mask;
    unsigned int sq_thread_idle;
    unsigned int cached_sq_dropped;
    struct io_uring_sqe * sq_sqes;
    struct list_head defer_list;
    struct list_head timeout_list;
    struct workqueue_struct *[2] sqo_wq;
    struct task_struct * sqo_thread;
    struct mm_struct * sqo_mm;
    wait_queue_head_t sqo_wait;
    struct completion sqo_thread_started;
    unsigned int cached_cq_tail;
    atomic_t cached_cq_overflow;
    unsigned int cq_entries;
    unsigned int cq_mask;
    struct wait_queue_head cq_wait;
    struct fasync_struct * cq_fasync;
    struct eventfd_ctx * cq_ev_fd;
    atomic_t cq_timeouts;
    struct io_rings * rings;
    struct file * * user_files;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * user_bufs;
    struct user_struct * user;
    const struct cred * creds;
    struct completion ctx_done;
    struct mutex uring_lock;
    wait_queue_head_t wait;
    spinlock_t completion_lock;
    bool poll_multi_file;
    struct list_head poll_list;
    struct list_head cancel_list;
    struct async_list[2] pending_async;
    struct socket * ring_sock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct io_ring_ctx {
    struct percpu_ref refs;
    unsigned int flags;
    bool compat;
    bool account_mem;
    u32 * sq_array;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    unsigned int sq_mask;
    unsigned int sq_thread_idle;
    unsigned int cached_sq_dropped;
    struct io_uring_sqe * sq_sqes;
    struct list_head defer_list;
    struct list_head timeout_list;
    struct workqueue_struct *[2] sqo_wq;
    struct task_struct * sqo_thread;
    struct mm_struct * sqo_mm;
    wait_queue_head_t sqo_wait;
    struct completion sqo_thread_started;
    unsigned int cached_cq_tail;
    atomic_t cached_cq_overflow;
    unsigned int cq_entries;
    unsigned int cq_mask;
    struct wait_queue_head cq_wait;
    struct fasync_struct * cq_fasync;
    struct eventfd_ctx * cq_ev_fd;
    atomic_t cq_timeouts;
    struct io_rings * rings;
    struct file * * user_files;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * user_bufs;
    struct user_struct * user;
    const struct cred * creds;
    struct completion ctx_done;
    struct mutex uring_lock;
    wait_queue_head_t wait;
    spinlock_t completion_lock;
    bool poll_multi_file;
    struct list_head poll_list;
    struct list_head cancel_list;
    struct async_list[2] pending_async;
    struct socket * ring_sock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct io_ring_ctx {
    struct percpu_ref refs;
    unsigned int flags;
    bool compat;
    bool account_mem;
    u32 * sq_array;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    unsigned int sq_mask;
    unsigned int sq_thread_idle;
    unsigned int cached_sq_dropped;
    struct io_uring_sqe * sq_sqes;
    struct list_head defer_list;
    struct list_head timeout_list;
    struct workqueue_struct *[2] sqo_wq;
    struct task_struct * sqo_thread;
    struct mm_struct * sqo_mm;
    wait_queue_head_t sqo_wait;
    struct completion sqo_thread_started;
    unsigned int cached_cq_tail;
    atomic_t cached_cq_overflow;
    unsigned int cq_entries;
    unsigned int cq_mask;
    struct wait_queue_head cq_wait;
    struct fasync_struct * cq_fasync;
    struct eventfd_ctx * cq_ev_fd;
    atomic_t cq_timeouts;
    struct io_rings * rings;
    struct file * * user_files;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * user_bufs;
    struct user_struct * user;
    const struct cred * creds;
    struct completion ctx_done;
    struct mutex uring_lock;
    wait_queue_head_t wait;
    spinlock_t completion_lock;
    bool poll_multi_file;
    struct list_head poll_list;
    struct list_head cancel_list;
    struct async_list[2] pending_async;
    struct socket * ring_sock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct io_ring_ctx {
    struct percpu_ref refs;
    unsigned int flags;
    bool compat;
    bool account_mem;
    u32 * sq_array;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    unsigned int sq_mask;
    unsigned int sq_thread_idle;
    unsigned int cached_sq_dropped;
    struct io_uring_sqe * sq_sqes;
    struct list_head defer_list;
    struct list_head timeout_list;
    struct workqueue_struct *[2] sqo_wq;
    struct task_struct * sqo_thread;
    struct mm_struct * sqo_mm;
    wait_queue_head_t sqo_wait;
    struct completion sqo_thread_started;
    unsigned int cached_cq_tail;
    atomic_t cached_cq_overflow;
    unsigned int cq_entries;
    unsigned int cq_mask;
    struct wait_queue_head cq_wait;
    struct fasync_struct * cq_fasync;
    struct eventfd_ctx * cq_ev_fd;
    atomic_t cq_timeouts;
    struct io_rings * rings;
    struct file * * user_files;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * user_bufs;
    struct user_struct * user;
    const struct cred * creds;
    struct completion ctx_done;
    struct mutex uring_lock;
    wait_queue_head_t wait;
    spinlock_t completion_lock;
    bool poll_multi_file;
    struct list_head poll_list;
    struct list_head cancel_list;
    struct async_list[2] pending_async;
    struct socket * ring_sock;
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
struct io_ring_ctx {
    struct percpu_ref refs;
    unsigned int flags;
    bool compat;
    bool account_mem;
    struct io_sq_ring * sq_ring;
    unsigned int cached_sq_head;
    unsigned int sq_entries;
    unsigned int sq_mask;
    unsigned int sq_thread_idle;
    struct io_uring_sqe * sq_sqes;
    struct list_head defer_list;
    struct workqueue_struct * sqo_wq;
    struct task_struct * sqo_thread;
    struct mm_struct * sqo_mm;
    wait_queue_head_t sqo_wait;
    struct completion sqo_thread_started;
    struct io_cq_ring * cq_ring;
    unsigned int cached_cq_tail;
    unsigned int cq_entries;
    unsigned int cq_mask;
    struct wait_queue_head cq_wait;
    struct fasync_struct * cq_fasync;
    struct eventfd_ctx * cq_ev_fd;
    struct file * * user_files;
    unsigned int nr_user_files;
    unsigned int nr_user_bufs;
    struct io_mapped_ubuf * user_bufs;
    struct user_struct * user;
    struct completion ctx_done;
    struct mutex uring_lock;
    wait_queue_head_t wait;
    spinlock_t completion_lock;
    bool poll_multi_file;
    struct list_head poll_list;
    struct list_head cancel_list;
    struct async_list[2] pending_async;
    struct socket * ring_sock;
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
<code>u32 * sq_array</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int cached_sq_dropped</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head timeout_list</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t cached_cq_overflow</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t cq_timeouts</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_rings * rings</code>
</li>
<li>
<b>Field added. </b>
<code>const struct cred * creds</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_sq_ring * sq_ring</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_cq_ring * cq_ring</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct workqueue_struct * sqo_wq</code> ➡️ <code>struct workqueue_struct *[2] sqo_wq</code>
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
<code>unsigned int cq_overflow_flushed</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int drain_next</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int eventfd_async</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int sq_check_overflow</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head cq_overflow_list</code>
</li>
<li>
<b>Field added. </b>
<code>wait_queue_head_t inflight_wait</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_wq * io_wq</code>
</li>
<li>
<b>Field added. </b>
<code>struct fixed_file_data * file_data</code>
</li>
<li>
<b>Field added. </b>
<code>int ring_fd</code>
</li>
<li>
<b>Field added. </b>
<code>struct file * ring_file</code>
</li>
<li>
<b>Field added. </b>
<code>struct completion ref_comp</code>
</li>
<li>
<b>Field added. </b>
<code>struct completion sq_thread_comp</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_kiocb * fallback_req</code>
</li>
<li>
<b>Field added. </b>
<code>struct idr io_buffer_idr</code>
</li>
<li>
<b>Field added. </b>
<code>struct idr personality_idr</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int cq_check_overflow</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head * cancel_hash</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int cancel_hash_bits</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t inflight_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head inflight_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct delayed_work file_put_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct llist_head file_put_llist</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct exit_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct workqueue_struct *[2] sqo_wq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct completion sqo_thread_started</code>
</li>
<li>
<b>Field removed. </b>
<code>struct file * * user_files</code>
</li>
<li>
<b>Field removed. </b>
<code>struct completion ctx_done</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head cancel_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct async_list[2] pending_async</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool compat</code> ➡️ <code>unsigned int compat</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool account_mem</code> ➡️ <code>unsigned int account_mem</code>
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
<code>unsigned int limit_mem</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int restricted</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sqo_dead</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_struct * sqo_task</code>
</li>
<li>
<b>Field added. </b>
<code>struct mm_struct * mm_account</code>
</li>
<li>
<b>Field added. </b>
<code>struct cgroup_subsys_state * sqo_blkcg_css</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_sq_data * sq_data</code>
</li>
<li>
<b>Field added. </b>
<code>struct wait_queue_head sqo_sq_wait</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head sqd_list</code>
</li>
<li>
<b>Field added. </b>
<code>kuid_t loginuid</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sessionid</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int cq_last_tm_flush</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head iopoll_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_restriction restrictions</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int account_mem</code>
</li>
<li>
<b>Field removed. </b>
<code>wait_queue_head_t inflight_wait</code>
</li>
<li>
<b>Field removed. </b>
<code>struct task_struct * sqo_thread</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mm_struct * sqo_mm</code>
</li>
<li>
<b>Field removed. </b>
<code>wait_queue_head_t sqo_wait</code>
</li>
<li>
<b>Field removed. </b>
<code>int ring_fd</code>
</li>
<li>
<b>Field removed. </b>
<code>struct file * ring_file</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head poll_list</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t cached_cq_overflow</code> ➡️ <code>unsigned int cached_cq_overflow</code>
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
<code>struct io_submit_state submit_state</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head locked_free_list</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int locked_free_nr</code>
</li>
<li>
<b>Field added. </b>
<code>const struct cred * sq_creds</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_file_table file_table</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_rsrc_data * buf_data</code>
</li>
<li>
<b>Field added. </b>
<code>struct xarray io_buffers</code>
</li>
<li>
<b>Field added. </b>
<code>struct xarray personalities</code>
</li>
<li>
<b>Field added. </b>
<code>u32 pers_next</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int cq_extra</code>
</li>
<li>
<b>Field added. </b>
<code>struct delayed_work rsrc_put_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct llist_head rsrc_put_llist</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head rsrc_ref_list</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t rsrc_ref_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_rsrc_node * rsrc_node</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_rsrc_node * rsrc_backup_node</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_mapped_ubuf * dummy_ubuf</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_wq_hash * hash_map</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head * exit_task_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head tctx_list</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int limit_mem</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int cq_overflow_flushed</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int sqo_dead</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_wq * io_wq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct task_struct * sqo_task</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cgroup_subsys_state * sqo_blkcg_css</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct cred * creds</code>
</li>
<li>
<b>Field removed. </b>
<code>kuid_t loginuid</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int sessionid</code>
</li>
<li>
<b>Field removed. </b>
<code>struct completion sq_thread_comp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_kiocb * fallback_req</code>
</li>
<li>
<b>Field removed. </b>
<code>struct idr io_buffer_idr</code>
</li>
<li>
<b>Field removed. </b>
<code>struct idr personality_idr</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t inflight_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head inflight_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct delayed_work file_put_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct llist_head file_put_llist</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fixed_file_data * file_data</code> ➡️ <code>struct io_rsrc_data * file_data</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct io_mapped_ubuf * user_bufs</code> ➡️ <code>struct io_mapped_ubuf * * user_bufs</code>
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
<code>unsigned int off_timeout_used</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int drain_active</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head ltimeout_list</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int check_cq_overflow</code>
</li>
<li>
<b>Field added. </b>
<code>struct wait_queue_head poll_wait</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t timeout_lock</code>
</li>
<li>
<b>Field added. </b>
<code>bool poll_multi_queue</code>
</li>
<li>
<b>Field added. </b>
<code>struct llist_head fallback_llist</code>
</li>
<li>
<b>Field added. </b>
<code>struct delayed_work fallback_work</code>
</li>
<li>
<b>Field added. </b>
<code>u32[2] iowq_limits</code>
</li>
<li>
<b>Field added. </b>
<code>bool iowq_limits_set</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int sq_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int cached_sq_dropped</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int cached_cq_overflow</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int sq_check_overflow</code>
</li>
<li>
<b>Field removed. </b>
<code>wait_queue_head_t wait</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int cq_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int cq_check_overflow</code>
</li>
<li>
<b>Field removed. </b>
<code>struct fasync_struct * cq_fasync</code>
</li>
<li>
<b>Field removed. </b>
<code>bool poll_multi_file</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head * exit_task_work</code>
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
<code>enum task_work_notify_mode notify_method</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int drain_disabled</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int has_evfd</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int syscall_iopoll</code>
</li>
<li>
<b>Field added. </b>
<code>int rsrc_cached_refs</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t cancel_seq</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_buffer_list * io_bl</code>
</li>
<li>
<b>Field added. </b>
<code>struct xarray io_bl_xa</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head io_buffers_cache</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head apoll_cache</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int check_cq</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_uring_cqe * cqe_cached</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_uring_cqe * cqe_sentinel</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_ev_fd * io_ev_fd</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head io_buffers_comp</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head io_buffers_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int eventfd_async</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xarray io_buffers</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int check_cq_overflow</code>
</li>
<li>
<b>Field removed. </b>
<code>struct eventfd_ctx * cq_ev_fd</code>
</li>
<li>
<b>Field removed. </b>
<code>struct wait_queue_head poll_wait</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head locked_free_list</code> ➡️ <code>struct io_wq_work_list locked_free_list</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head iopoll_list</code> ➡️ <code>struct io_wq_work_list iopoll_list</code>
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
<code>unsigned int task_complete</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_hash_table cancel_table_locked</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_alloc_cache netmsg_cache</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int file_alloc_start</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int file_alloc_end</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_hash_table cancel_table</code>
</li>
<li>
<b>Field added. </b>
<code>struct llist_head work_llist</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_struct * submitter_task</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head rsrc_put_tw</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int evfd_last_cq_tail</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_head * cancel_hash</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int cancel_hash_bits</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head apoll_cache</code> ➡️ <code>struct io_alloc_cache apoll_cache</code>
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
<code>unsigned int poll_activated</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int n_ring_pages</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int n_sqe_pages</code>
</li>
<li>
<b>Field added. </b>
<code>struct page * * ring_pages</code>
</li>
<li>
<b>Field added. </b>
<code>struct page * * sqe_pages</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t cq_wait_nr</code>
</li>
<li>
<b>Field added. </b>
<code>struct wait_queue_head poll_wq</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_alloc_cache rsrc_node_cache</code>
</li>
<li>
<b>Field added. </b>
<code>struct wait_queue_head rsrc_quiesce_wq</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int rsrc_quiesce</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head poll_wq_task_work</code>
</li>
<li>
<b>Field removed. </b>
<code>int rsrc_cached_refs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_rsrc_node * rsrc_backup_node</code>
</li>
<li>
<b>Field removed. </b>
<code>struct delayed_work rsrc_put_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head rsrc_put_tw</code>
</li>
<li>
<b>Field removed. </b>
<code>struct llist_head rsrc_put_llist</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t rsrc_ref_lock</code>
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
<code>unsigned int lockless_cq</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head cancelable_uring_cmd</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_uring_cqe[16] completion_cqes</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head waitid_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head futex_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_alloc_cache futex_cache</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head io_buf_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head io_buffers_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>struct socket * ring_sock</code>
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
