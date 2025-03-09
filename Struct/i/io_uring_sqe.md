# Struct: <code>io_uring_sqe</code>

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
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u64 user_data;
    __u16 buf_index;
    __u64[3] __pad2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u64 user_data;
    __u16 buf_index;
    __u64[3] __pad2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr2;
    __u64 addr;
    __u64 splice_off_in;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u32 accept_flags;
    __u32 cancel_flags;
    __u32 open_flags;
    __u32 statx_flags;
    __u32 fadvise_advice;
    __u32 splice_flags;
    __u64 user_data;
    __u16 buf_index;
    __u16 buf_group;
    __u16 personality;
    __s32 splice_fd_in;
    __u64[3] __pad2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr2;
    __u64 addr;
    __u64 splice_off_in;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 poll32_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u32 accept_flags;
    __u32 cancel_flags;
    __u32 open_flags;
    __u32 statx_flags;
    __u32 fadvise_advice;
    __u32 splice_flags;
    __u32 rename_flags;
    __u32 unlink_flags;
    __u64 user_data;
    __u16 buf_index;
    __u16 buf_group;
    __u16 personality;
    __s32 splice_fd_in;
    __u64[3] __pad2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr2;
    __u64 addr;
    __u64 splice_off_in;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 poll32_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u32 accept_flags;
    __u32 cancel_flags;
    __u32 open_flags;
    __u32 statx_flags;
    __u32 fadvise_advice;
    __u32 splice_flags;
    __u32 rename_flags;
    __u32 unlink_flags;
    __u64 user_data;
    __u16 buf_index;
    __u16 buf_group;
    __u16 personality;
    __s32 splice_fd_in;
    __u64[3] __pad2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr2;
    __u64 addr;
    __u64 splice_off_in;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 poll32_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u32 accept_flags;
    __u32 cancel_flags;
    __u32 open_flags;
    __u32 statx_flags;
    __u32 fadvise_advice;
    __u32 splice_flags;
    __u32 rename_flags;
    __u32 unlink_flags;
    __u32 hardlink_flags;
    __u64 user_data;
    __u16 buf_index;
    __u16 buf_group;
    __u16 personality;
    __s32 splice_fd_in;
    __u32 file_index;
    __u64[2] __pad2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr2;
    __u32 cmd_op;
    __u32 __pad1;
    __u64 addr;
    __u64 splice_off_in;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 poll32_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u32 accept_flags;
    __u32 cancel_flags;
    __u32 open_flags;
    __u32 statx_flags;
    __u32 fadvise_advice;
    __u32 splice_flags;
    __u32 rename_flags;
    __u32 unlink_flags;
    __u32 hardlink_flags;
    __u32 xattr_flags;
    __u64 user_data;
    __u16 buf_index;
    __u16 buf_group;
    __u16 personality;
    __s32 splice_fd_in;
    __u32 file_index;
    __u64 addr3;
    __u64[1] __pad2;
    __u8[0] cmd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr2;
    __u32 cmd_op;
    __u32 __pad1;
    __u64 addr;
    __u64 splice_off_in;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 poll32_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u32 accept_flags;
    __u32 cancel_flags;
    __u32 open_flags;
    __u32 statx_flags;
    __u32 fadvise_advice;
    __u32 splice_flags;
    __u32 rename_flags;
    __u32 unlink_flags;
    __u32 hardlink_flags;
    __u32 xattr_flags;
    __u32 msg_ring_flags;
    __u32 uring_cmd_flags;
    __u64 user_data;
    __u16 buf_index;
    __u16 buf_group;
    __u16 personality;
    __s32 splice_fd_in;
    __u32 file_index;
    __u16 addr_len;
    __u16[1] __pad3;
    __u64 addr3;
    __u64[1] __pad2;
    __u8[0] cmd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr2;
    __u32 cmd_op;
    __u32 __pad1;
    __u64 addr;
    __u64 splice_off_in;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 poll32_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u32 accept_flags;
    __u32 cancel_flags;
    __u32 open_flags;
    __u32 statx_flags;
    __u32 fadvise_advice;
    __u32 splice_flags;
    __u32 rename_flags;
    __u32 unlink_flags;
    __u32 hardlink_flags;
    __u32 xattr_flags;
    __u32 msg_ring_flags;
    __u32 uring_cmd_flags;
    __u64 user_data;
    __u16 buf_index;
    __u16 buf_group;
    __u16 personality;
    __s32 splice_fd_in;
    __u32 file_index;
    __u16 addr_len;
    __u16[1] __pad3;
    __u64 addr3;
    __u64[1] __pad2;
    __u8[0] cmd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr2;
    __u32 cmd_op;
    __u32 __pad1;
    __u64 addr;
    __u64 splice_off_in;
    __u32 level;
    __u32 optname;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 poll32_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u32 accept_flags;
    __u32 cancel_flags;
    __u32 open_flags;
    __u32 statx_flags;
    __u32 fadvise_advice;
    __u32 splice_flags;
    __u32 rename_flags;
    __u32 unlink_flags;
    __u32 hardlink_flags;
    __u32 xattr_flags;
    __u32 msg_ring_flags;
    __u32 uring_cmd_flags;
    __u32 waitid_flags;
    __u32 futex_flags;
    __u32 install_fd_flags;
    __u64 user_data;
    __u16 buf_index;
    __u16 buf_group;
    __u16 personality;
    __s32 splice_fd_in;
    __u32 file_index;
    __u32 optlen;
    __u16 addr_len;
    __u16[1] __pad3;
    __u64 addr3;
    __u64[1] __pad2;
    __u64 optval;
    __u8[0] cmd;
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
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u64 user_data;
    __u16 buf_index;
    __u64[3] __pad2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u64 user_data;
    __u16 buf_index;
    __u64[3] __pad2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u64 user_data;
    __u16 buf_index;
    __u64[3] __pad2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u64 user_data;
    __u16 buf_index;
    __u64[3] __pad2;
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
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u64 user_data;
    __u16 buf_index;
    __u64[3] __pad2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u64 user_data;
    __u16 buf_index;
    __u64[3] __pad2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u64 user_data;
    __u16 buf_index;
    __u64[3] __pad2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u32 timeout_flags;
    __u64 user_data;
    __u16 buf_index;
    __u64[3] __pad2;
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
struct io_uring_sqe {
    __u8 opcode;
    __u8 flags;
    __u16 ioprio;
    __s32 fd;
    __u64 off;
    __u64 addr;
    __u32 len;
    __kernel_rwf_t rw_flags;
    __u32 fsync_flags;
    __u16 poll_events;
    __u32 sync_range_flags;
    __u32 msg_flags;
    __u64 user_data;
    __u16 buf_index;
    __u64[3] __pad2;
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
<code>__u32 timeout_flags</code>
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
<code>__u64 addr2</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 splice_off_in</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 accept_flags</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 cancel_flags</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 open_flags</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 statx_flags</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 fadvise_advice</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 splice_flags</code>
</li>
<li>
<b>Field added. </b>
<code>__u16 buf_group</code>
</li>
<li>
<b>Field added. </b>
<code>__u16 personality</code>
</li>
<li>
<b>Field added. </b>
<code>__s32 splice_fd_in</code>
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
<code>__u32 poll32_events</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 rename_flags</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 unlink_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 hardlink_flags</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 file_index</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u64[3] __pad2</code> ➡️ <code>__u64[2] __pad2</code>
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
<code>__u32 cmd_op</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 __pad1</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 xattr_flags</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 addr3</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] cmd</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u64[2] __pad2</code> ➡️ <code>__u64[1] __pad2</code>
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
<code>__u32 msg_ring_flags</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 uring_cmd_flags</code>
</li>
<li>
<b>Field added. </b>
<code>__u16 addr_len</code>
</li>
<li>
<b>Field added. </b>
<code>__u16[1] __pad3</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 level</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 optname</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 waitid_flags</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 futex_flags</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 install_fd_flags</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 optlen</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 optval</code>
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
