# Struct: <code>signalfd_siginfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u8[46] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u8[46] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u8[46] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u8[46] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u8[46] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
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
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
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
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct signalfd_siginfo {
    __u32 ssi_signo;
    __s32 ssi_errno;
    __s32 ssi_code;
    __u32 ssi_pid;
    __u32 ssi_uid;
    __s32 ssi_fd;
    __u32 ssi_tid;
    __u32 ssi_band;
    __u32 ssi_overrun;
    __u32 ssi_trapno;
    __s32 ssi_status;
    __s32 ssi_int;
    __u64 ssi_ptr;
    __u64 ssi_utime;
    __u64 ssi_stime;
    __u64 ssi_addr;
    __u16 ssi_addr_lsb;
    __u16 __pad2;
    __s32 ssi_syscall;
    __u64 ssi_call_addr;
    __u32 ssi_arch;
    __u8[28] __pad;
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
<code>__u16 __pad2</code>
</li>
<li>
<b>Field added. </b>
<code>__s32 ssi_syscall</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 ssi_call_addr</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 ssi_arch</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u8[46] __pad</code> ➡️ <code>__u8[28] __pad</code>
</li>
</ul>
</details>
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
