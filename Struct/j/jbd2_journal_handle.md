# Struct: <code>jbd2_journal_handle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_total_credits;
    int h_revoke_credits;
    int h_revoke_credits_requested;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_total_credits;
    int h_revoke_credits;
    int h_revoke_credits_requested;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_total_credits;
    int h_revoke_credits;
    int h_revoke_credits_requested;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_total_credits;
    int h_revoke_credits;
    int h_revoke_credits_requested;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_total_credits;
    int h_revoke_credits;
    int h_revoke_credits_requested;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_total_credits;
    int h_revoke_credits;
    int h_revoke_credits_requested;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_total_credits;
    int h_revoke_credits;
    int h_revoke_credits_requested;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_total_credits;
    int h_revoke_credits;
    int h_revoke_credits_requested;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
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
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
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
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct jbd2_journal_handle {
    transaction_t * h_transaction;
    journal_t * h_journal;
    handle_t * h_rsv_handle;
    int h_buffer_credits;
    int h_ref;
    int h_err;
    unsigned int h_sync;
    unsigned int h_jdata;
    unsigned int h_reserved;
    unsigned int h_aborted;
    unsigned int h_type;
    unsigned int h_line_no;
    long unsigned int h_start_jiffies;
    unsigned int h_requested_credits;
    unsigned int saved_alloc_context;
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
<code>unsigned int saved_alloc_context</code>
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
<code>int h_total_credits</code>
</li>
<li>
<b>Field added. </b>
<code>int h_revoke_credits</code>
</li>
<li>
<b>Field added. </b>
<code>int h_revoke_credits_requested</code>
</li>
<li>
<b>Field removed. </b>
<code>int h_buffer_credits</code>
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
