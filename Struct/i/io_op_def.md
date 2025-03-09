# Struct: <code>io_op_def</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_op_def {
    unsigned int async_ctx;
    unsigned int needs_mm;
    unsigned int needs_file;
    unsigned int needs_file_no_error;
    unsigned int hash_reg_file;
    unsigned int unbound_nonreg_file;
    unsigned int not_supported;
    unsigned int file_table;
    unsigned int needs_fs;
    unsigned int pollin;
    unsigned int pollout;
    unsigned int buffer_select;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct io_op_def {
    unsigned int needs_file;
    unsigned int needs_file_no_error;
    unsigned int hash_reg_file;
    unsigned int unbound_nonreg_file;
    unsigned int not_supported;
    unsigned int pollin;
    unsigned int pollout;
    unsigned int buffer_select;
    unsigned int needs_async_data;
    unsigned int plug;
    short unsigned int async_size;
    unsigned int work_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct io_op_def {
    unsigned int needs_file;
    unsigned int hash_reg_file;
    unsigned int unbound_nonreg_file;
    unsigned int not_supported;
    unsigned int pollin;
    unsigned int pollout;
    unsigned int buffer_select;
    unsigned int needs_async_setup;
    unsigned int plug;
    short unsigned int async_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_op_def {
    unsigned int needs_file;
    unsigned int hash_reg_file;
    unsigned int unbound_nonreg_file;
    unsigned int not_supported;
    unsigned int pollin;
    unsigned int pollout;
    unsigned int buffer_select;
    unsigned int needs_async_setup;
    unsigned int plug;
    short unsigned int async_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_op_def {
    unsigned int needs_file;
    unsigned int plug;
    unsigned int hash_reg_file;
    unsigned int unbound_nonreg_file;
    unsigned int pollin;
    unsigned int pollout;
    unsigned int poll_exclusive;
    unsigned int buffer_select;
    unsigned int needs_async_setup;
    unsigned int not_supported;
    unsigned int audit_skip;
    unsigned int ioprio;
    unsigned int iopoll;
    short unsigned int async_size;
    int (*)(struct io_kiocb *, const struct io_uring_sqe *) prep;
    int (*)(struct io_kiocb *, unsigned int) issue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct io_op_def {
    unsigned int needs_file;
    unsigned int plug;
    unsigned int hash_reg_file;
    unsigned int unbound_nonreg_file;
    unsigned int pollin;
    unsigned int pollout;
    unsigned int poll_exclusive;
    unsigned int buffer_select;
    unsigned int not_supported;
    unsigned int audit_skip;
    unsigned int ioprio;
    unsigned int iopoll;
    unsigned int iopoll_queue;
    unsigned int manual_alloc;
    short unsigned int async_size;
    const char * name;
    int (*)(struct io_kiocb *, const struct io_uring_sqe *) prep;
    int (*)(struct io_kiocb *, unsigned int) issue;
    int (*)(struct io_kiocb *) prep_async;
    void (*)(struct io_kiocb *) cleanup;
    void (*)(struct io_kiocb *) fail;
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct io_op_def {
    unsigned int async_ctx;
    unsigned int needs_mm;
    unsigned int needs_file;
    unsigned int needs_file_no_error;
    unsigned int hash_reg_file;
    unsigned int unbound_nonreg_file;
    unsigned int not_supported;
    unsigned int file_table;
    unsigned int needs_fs;
    unsigned int pollin;
    unsigned int pollout;
    unsigned int buffer_select;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int needs_async_data</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int plug</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int async_size</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int work_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int async_ctx</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int needs_mm</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int file_table</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int needs_fs</code>
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
<code>unsigned int needs_async_setup</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int needs_file_no_error</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int needs_async_data</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int work_flags</code>
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
<code>unsigned int poll_exclusive</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int audit_skip</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int ioprio</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int iopoll</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct io_kiocb *, const struct io_uring_sqe *) prep</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct io_kiocb *, unsigned int) issue</code>
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
<code>unsigned int iopoll_queue</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int manual_alloc</code>
</li>
<li>
<b>Field added. </b>
<code>const char * name</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct io_kiocb *) prep_async</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct io_kiocb *) cleanup</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct io_kiocb *) fail</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int needs_async_setup</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct io_op_def {
    unsigned int needs_file;
    unsigned int plug;
    unsigned int hash_reg_file;
    unsigned int unbound_nonreg_file;
    unsigned int pollin;
    unsigned int pollout;
    unsigned int poll_exclusive;
    unsigned int buffer_select;
    unsigned int not_supported;
    unsigned int audit_skip;
    unsigned int ioprio;
    unsigned int iopoll;
    unsigned int iopoll_queue;
    unsigned int manual_alloc;
    short unsigned int async_size;
    const char * name;
    int (*)(struct io_kiocb *, const struct io_uring_sqe *) prep;
    int (*)(struct io_kiocb *, unsigned int) issue;
    int (*)(struct io_kiocb *) prep_async;
    void (*)(struct io_kiocb *) cleanup;
    void (*)(struct io_kiocb *) fail;
}
```
</details>
</li>
</ul>
