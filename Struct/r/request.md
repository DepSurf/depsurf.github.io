# Struct: <code>request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct list_head queuelist;
    struct call_single_data csd;
    long unsigned int fifo_time;
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    u64 cmd_flags;
    unsigned int cmd_type;
    long unsigned int atomic_flags;
    int cpu;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    void * completion_data;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    long unsigned int start_time;
    struct request_list * rl;
    long long unsigned int start_time_ns;
    long long unsigned int io_start_time_ns;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int ioprio;
    void * special;
    int tag;
    int errors;
    unsigned char[16] __cmd;
    unsigned char * cmd;
    short unsigned int cmd_len;
    unsigned int extra_len;
    unsigned int sense_len;
    unsigned int resid_len;
    void * sense;
    long unsigned int deadline;
    struct list_head timeout_list;
    unsigned int timeout;
    int retries;
    rq_end_io_fn * end_io;
    void * end_io_data;
    struct request * next_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct list_head queuelist;
    struct call_single_data csd;
    u64 fifo_time;
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    int cpu;
    unsigned int cmd_type;
    u64 cmd_flags;
    long unsigned int atomic_flags;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    void * completion_data;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    long unsigned int start_time;
    struct request_list * rl;
    long long unsigned int start_time_ns;
    long long unsigned int io_start_time_ns;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int ioprio;
    void * special;
    int tag;
    int errors;
    unsigned char[16] __cmd;
    unsigned char * cmd;
    short unsigned int cmd_len;
    unsigned int extra_len;
    unsigned int sense_len;
    unsigned int resid_len;
    void * sense;
    long unsigned int deadline;
    struct list_head timeout_list;
    unsigned int timeout;
    int retries;
    rq_end_io_fn * end_io;
    void * end_io_data;
    struct request * next_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct list_head queuelist;
    struct call_single_data csd;
    u64 fifo_time;
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    int cpu;
    unsigned int cmd_type;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    long unsigned int atomic_flags;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    long unsigned int start_time;
    struct blk_issue_stat issue_stat;
    struct request_list * rl;
    long long unsigned int start_time_ns;
    long long unsigned int io_start_time_ns;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int ioprio;
    void * special;
    int tag;
    int errors;
    unsigned char[16] __cmd;
    unsigned char * cmd;
    short unsigned int cmd_len;
    unsigned int extra_len;
    unsigned int sense_len;
    unsigned int resid_len;
    void * sense;
    long unsigned int deadline;
    struct list_head timeout_list;
    unsigned int timeout;
    int retries;
    rq_end_io_fn * end_io;
    void * end_io_data;
    struct request * next_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct list_head queuelist;
    struct call_single_data csd;
    u64 fifo_time;
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    int cpu;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int internal_tag;
    long unsigned int atomic_flags;
    unsigned int __data_len;
    int tag;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    long unsigned int start_time;
    struct blk_issue_stat issue_stat;
    struct request_list * rl;
    long long unsigned int start_time_ns;
    long long unsigned int io_start_time_ns;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int ioprio;
    unsigned int timeout;
    void * special;
    unsigned int extra_len;
    short unsigned int write_hint;
    long unsigned int deadline;
    struct list_head timeout_list;
    rq_end_io_fn * end_io;
    void * end_io_data;
    struct request * next_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct list_head queuelist;
    struct __call_single_data csd;
    u64 fifo_time;
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    int cpu;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int internal_tag;
    long unsigned int atomic_flags;
    unsigned int __data_len;
    int tag;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    long unsigned int start_time;
    struct blk_issue_stat issue_stat;
    struct request_list * rl;
    long long unsigned int start_time_ns;
    long long unsigned int io_start_time_ns;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int ioprio;
    unsigned int timeout;
    void * special;
    unsigned int extra_len;
    short unsigned int write_hint;
    long unsigned int deadline;
    struct list_head timeout_list;
    rq_end_io_fn * end_io;
    void * end_io_data;
    struct request * next_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    int cpu;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int internal_tag;
    unsigned int __data_len;
    int tag;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int write_hint;
    short unsigned int ioprio;
    void * special;
    unsigned int extra_len;
    enum mq_rq_state state;
    refcount_t ref;
    unsigned int timeout;
    long unsigned int __deadline;
    struct list_head timeout_list;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
    struct request * next_rq;
    struct request_list * rl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int internal_tag;
    unsigned int __data_len;
    int tag;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int write_hint;
    short unsigned int ioprio;
    void * special;
    unsigned int extra_len;
    enum mq_rq_state state;
    refcount_t ref;
    unsigned int timeout;
    long unsigned int deadline;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
    struct request * next_rq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int write_hint;
    short unsigned int ioprio;
    unsigned int extra_len;
    enum mq_rq_state state;
    refcount_t ref;
    unsigned int timeout;
    long unsigned int deadline;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int write_hint;
    short unsigned int ioprio;
    unsigned int extra_len;
    enum mq_rq_state state;
    refcount_t ref;
    unsigned int timeout;
    long unsigned int deadline;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    struct bio_crypt_ctx * crypt_ctx;
    struct blk_ksm_keyslot * crypt_keyslot;
    short unsigned int write_hint;
    short unsigned int ioprio;
    enum mq_rq_state state;
    refcount_t ref;
    unsigned int timeout;
    long unsigned int deadline;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct block_device * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    struct bio_crypt_ctx * crypt_ctx;
    struct blk_ksm_keyslot * crypt_keyslot;
    short unsigned int write_hint;
    short unsigned int ioprio;
    enum mq_rq_state state;
    refcount_t ref;
    unsigned int timeout;
    long unsigned int deadline;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct hlist_node hash;
    struct llist_node ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct block_device * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    struct bio_crypt_ctx * crypt_ctx;
    struct blk_ksm_keyslot * crypt_keyslot;
    short unsigned int write_hint;
    short unsigned int ioprio;
    enum mq_rq_state state;
    refcount_t ref;
    unsigned int timeout;
    long unsigned int deadline;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct hlist_node hash;
    struct llist_node ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct block_device * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    struct bio_crypt_ctx * crypt_ctx;
    struct blk_ksm_keyslot * crypt_keyslot;
    short unsigned int write_hint;
    short unsigned int ioprio;
    enum mq_rq_state state;
    refcount_t ref;
    unsigned int timeout;
    long unsigned int deadline;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int timeout;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct request * rq_next;
    struct block_device * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    struct bio_crypt_ctx * crypt_ctx;
    struct blk_crypto_keyslot * crypt_keyslot;
    short unsigned int write_hint;
    short unsigned int ioprio;
    enum mq_rq_state state;
    atomic_t ref;
    long unsigned int deadline;
    struct hlist_node hash;
    struct llist_node ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    struct (anon) elv;
    struct (anon) flush;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    blk_opf_t cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int timeout;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct request * rq_next;
    struct block_device * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    struct bio_crypt_ctx * crypt_ctx;
    struct blk_crypto_keyslot * crypt_keyslot;
    short unsigned int ioprio;
    enum mq_rq_state state;
    atomic_t ref;
    long unsigned int deadline;
    struct hlist_node hash;
    struct llist_node ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    struct (anon) elv;
    struct (anon) flush;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    blk_opf_t cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int timeout;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct request * rq_next;
    struct block_device * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    struct bio_crypt_ctx * crypt_ctx;
    struct blk_crypto_keyslot * crypt_keyslot;
    short unsigned int ioprio;
    enum mq_rq_state state;
    atomic_t ref;
    long unsigned int deadline;
    struct hlist_node hash;
    struct llist_node ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    struct (anon) elv;
    struct (anon) flush;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    blk_opf_t cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int timeout;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct request * rq_next;
    struct block_device * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    struct bio_crypt_ctx * crypt_ctx;
    struct blk_crypto_keyslot * crypt_keyslot;
    short unsigned int ioprio;
    enum mq_rq_state state;
    atomic_t ref;
    long unsigned int deadline;
    struct hlist_node hash;
    struct llist_node ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    struct (anon) elv;
    struct (anon) flush;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
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
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int write_hint;
    short unsigned int ioprio;
    unsigned int extra_len;
    enum mq_rq_state state;
    refcount_t ref;
    unsigned int timeout;
    long unsigned int deadline;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int write_hint;
    short unsigned int ioprio;
    unsigned int extra_len;
    enum mq_rq_state state;
    refcount_t ref;
    unsigned int timeout;
    long unsigned int deadline;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int write_hint;
    short unsigned int ioprio;
    unsigned int extra_len;
    enum mq_rq_state state;
    refcount_t ref;
    unsigned int timeout;
    long unsigned int deadline;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int write_hint;
    short unsigned int ioprio;
    unsigned int extra_len;
    enum mq_rq_state state;
    refcount_t ref;
    unsigned int timeout;
    long unsigned int deadline;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
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
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int write_hint;
    short unsigned int ioprio;
    unsigned int extra_len;
    enum mq_rq_state state;
    refcount_t ref;
    unsigned int timeout;
    long unsigned int deadline;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int write_hint;
    short unsigned int ioprio;
    unsigned int extra_len;
    enum mq_rq_state state;
    refcount_t ref;
    unsigned int timeout;
    long unsigned int deadline;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int write_hint;
    short unsigned int ioprio;
    unsigned int extra_len;
    enum mq_rq_state state;
    refcount_t ref;
    unsigned int timeout;
    long unsigned int deadline;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct request {
    struct request_queue * q;
    struct blk_mq_ctx * mq_ctx;
    struct blk_mq_hw_ctx * mq_hctx;
    unsigned int cmd_flags;
    req_flags_t rq_flags;
    int tag;
    int internal_tag;
    unsigned int __data_len;
    sector_t __sector;
    struct bio * bio;
    struct bio * biotail;
    struct list_head queuelist;
    struct hlist_node hash;
    struct list_head ipi_list;
    struct rb_node rb_node;
    struct bio_vec special_vec;
    void * completion_data;
    int error_count;
    struct (anon) elv;
    struct (anon) flush;
    struct gendisk * rq_disk;
    struct hd_struct * part;
    u64 alloc_time_ns;
    u64 start_time_ns;
    u64 io_start_time_ns;
    short unsigned int wbt_flags;
    short unsigned int stats_sectors;
    short unsigned int nr_phys_segments;
    short unsigned int nr_integrity_segments;
    short unsigned int write_hint;
    short unsigned int ioprio;
    unsigned int extra_len;
    enum mq_rq_state state;
    refcount_t ref;
    unsigned int timeout;
    long unsigned int deadline;
    struct __call_single_data csd;
    u64 fifo_time;
    rq_end_io_fn * end_io;
    void * end_io_data;
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
<b>Field type changed. </b>
<code>long unsigned int fifo_time</code> ➡️ <code>u64 fifo_time</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>req_flags_t rq_flags</code>
</li>
<li>
<b>Field added. </b>
<code>struct bio_vec special_vec</code>
</li>
<li>
<b>Field added. </b>
<code>struct blk_issue_stat issue_stat</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 cmd_flags</code> ➡️ <code>unsigned int cmd_flags</code>
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
<code>int internal_tag</code>
</li>
<li>
<b>Field added. </b>
<code>int error_count</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int write_hint</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int cmd_type</code>
</li>
<li>
<b>Field removed. </b>
<code>int errors</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char[16] __cmd</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char * cmd</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int cmd_len</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int sense_len</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int resid_len</code>
</li>
<li>
<b>Field removed. </b>
<code>void * sense</code>
</li>
<li>
<b>Field removed. </b>
<code>int retries</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct call_single_data csd</code> ➡️ <code>struct __call_single_data csd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>short unsigned int wbt_flags</code>
</li>
<li>
<b>Field added. </b>
<code>enum mq_rq_state state</code>
</li>
<li>
<b>Field added. </b>
<code>refcount_t ref</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int __deadline</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int atomic_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int start_time</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blk_issue_stat issue_stat</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int deadline</code>
</li>
<li>
<b>Field type changed. </b>
<code>long long unsigned int start_time_ns</code> ➡️ <code>u64 start_time_ns</code>
</li>
<li>
<b>Field type changed. </b>
<code>long long unsigned int io_start_time_ns</code> ➡️ <code>u64 io_start_time_ns</code>
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
<code>struct blk_mq_hw_ctx * mq_hctx</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int deadline</code>
</li>
<li>
<b>Field removed. </b>
<code>int cpu</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int __deadline</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head timeout_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct request_list * rl</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void * special</code>
</li>
<li>
<b>Field removed. </b>
<code>struct request * next_rq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 alloc_time_ns</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int stats_sectors</code>
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
<code>struct bio_crypt_ctx * crypt_ctx</code>
</li>
<li>
<b>Field added. </b>
<code>struct blk_ksm_keyslot * crypt_keyslot</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int extra_len</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct hd_struct * part</code> ➡️ <code>struct block_device * part</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct list_head ipi_list</code> ➡️ <code>struct llist_node ipi_list</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct request * rq_next</code>
</li>
<li>
<b>Field removed. </b>
<code>int error_count</code>
</li>
<li>
<b>Field removed. </b>
<code>struct gendisk * rq_disk</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct blk_ksm_keyslot * crypt_keyslot</code> ➡️ <code>struct blk_crypto_keyslot * crypt_keyslot</code>
</li>
<li>
<b>Field type changed. </b>
<code>refcount_t ref</code> ➡️ <code>atomic_t ref</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>short unsigned int write_hint</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int cmd_flags</code> ➡️ <code>blk_opf_t cmd_flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void * completion_data</code>
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
<code>struct __call_single_data csd</code>
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
