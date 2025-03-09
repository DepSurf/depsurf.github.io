# Struct: <code>io_issue_def</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct io_issue_def {
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
    int (*)(struct io_kiocb *, unsigned int) issue;
    int (*)(struct io_kiocb *, const struct io_uring_sqe *) prep;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct io_issue_def {
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
    unsigned int vectored;
    int (*)(struct io_kiocb *, unsigned int) issue;
    int (*)(struct io_kiocb *, const struct io_uring_sqe *) prep;
}
```
</details>
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct io_issue_def {
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
    int (*)(struct io_kiocb *, unsigned int) issue;
    int (*)(struct io_kiocb *, const struct io_uring_sqe *) prep;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int vectored</code>
</li>
</ul>
</details>
</li>
</ul>
