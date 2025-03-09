# Struct: <code>tpacket_kbdq_core</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    rwlock_t blk_fill_in_prog_lock;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    rwlock_t blk_fill_in_prog_lock;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    rwlock_t blk_fill_in_prog_lock;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    rwlock_t blk_fill_in_prog_lock;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    rwlock_t blk_fill_in_prog_lock;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    rwlock_t blk_fill_in_prog_lock;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    rwlock_t blk_fill_in_prog_lock;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
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
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
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
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tpacket_kbdq_core {
    struct pgv * pkbdq;
    unsigned int feature_req_word;
    unsigned int hdrlen;
    unsigned char reset_pending_on_curr_blk;
    unsigned char delete_blk_timer;
    short unsigned int kactive_blk_num;
    short unsigned int blk_sizeof_priv;
    short unsigned int last_kactive_blk_num;
    char * pkblk_start;
    char * pkblk_end;
    int kblk_size;
    unsigned int max_frame_len;
    unsigned int knum_blocks;
    uint64_t knxt_seq_num;
    char * prev;
    char * nxt_offset;
    struct sk_buff * skb;
    atomic_t blk_fill_in_prog;
    short unsigned int retire_blk_tov;
    short unsigned int version;
    long unsigned int tov_in_jiffies;
    struct timer_list retire_blk_timer;
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>rwlock_t blk_fill_in_prog_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t blk_fill_in_prog</code>
</li>
</ul>
</details>
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
