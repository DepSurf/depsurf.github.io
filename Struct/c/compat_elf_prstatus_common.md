# Struct: <code>compat_elf_prstatus_common</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct compat_elf_prstatus_common {
    struct compat_elf_siginfo pr_info;
    short int pr_cursig;
    compat_ulong_t pr_sigpend;
    compat_ulong_t pr_sighold;
    compat_pid_t pr_pid;
    compat_pid_t pr_ppid;
    compat_pid_t pr_pgrp;
    compat_pid_t pr_sid;
    struct old_timeval32 pr_utime;
    struct old_timeval32 pr_stime;
    struct old_timeval32 pr_cutime;
    struct old_timeval32 pr_cstime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct compat_elf_prstatus_common {
    struct compat_elf_siginfo pr_info;
    short int pr_cursig;
    compat_ulong_t pr_sigpend;
    compat_ulong_t pr_sighold;
    compat_pid_t pr_pid;
    compat_pid_t pr_ppid;
    compat_pid_t pr_pgrp;
    compat_pid_t pr_sid;
    struct old_timeval32 pr_utime;
    struct old_timeval32 pr_stime;
    struct old_timeval32 pr_cutime;
    struct old_timeval32 pr_cstime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct compat_elf_prstatus_common {
    struct compat_elf_siginfo pr_info;
    short int pr_cursig;
    compat_ulong_t pr_sigpend;
    compat_ulong_t pr_sighold;
    compat_pid_t pr_pid;
    compat_pid_t pr_ppid;
    compat_pid_t pr_pgrp;
    compat_pid_t pr_sid;
    struct old_timeval32 pr_utime;
    struct old_timeval32 pr_stime;
    struct old_timeval32 pr_cutime;
    struct old_timeval32 pr_cstime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct compat_elf_prstatus_common {
    struct compat_elf_siginfo pr_info;
    short int pr_cursig;
    compat_ulong_t pr_sigpend;
    compat_ulong_t pr_sighold;
    compat_pid_t pr_pid;
    compat_pid_t pr_ppid;
    compat_pid_t pr_pgrp;
    compat_pid_t pr_sid;
    struct old_timeval32 pr_utime;
    struct old_timeval32 pr_stime;
    struct old_timeval32 pr_cutime;
    struct old_timeval32 pr_cstime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct compat_elf_prstatus_common {
    struct compat_elf_siginfo pr_info;
    short int pr_cursig;
    compat_ulong_t pr_sigpend;
    compat_ulong_t pr_sighold;
    compat_pid_t pr_pid;
    compat_pid_t pr_ppid;
    compat_pid_t pr_pgrp;
    compat_pid_t pr_sid;
    struct old_timeval32 pr_utime;
    struct old_timeval32 pr_stime;
    struct old_timeval32 pr_cutime;
    struct old_timeval32 pr_cstime;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct compat_elf_prstatus_common {
    struct compat_elf_siginfo pr_info;
    short int pr_cursig;
    compat_ulong_t pr_sigpend;
    compat_ulong_t pr_sighold;
    compat_pid_t pr_pid;
    compat_pid_t pr_ppid;
    compat_pid_t pr_pgrp;
    compat_pid_t pr_sid;
    struct old_timeval32 pr_utime;
    struct old_timeval32 pr_stime;
    struct old_timeval32 pr_cutime;
    struct old_timeval32 pr_cstime;
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct compat_elf_prstatus_common {
    struct compat_elf_siginfo pr_info;
    short int pr_cursig;
    compat_ulong_t pr_sigpend;
    compat_ulong_t pr_sighold;
    compat_pid_t pr_pid;
    compat_pid_t pr_ppid;
    compat_pid_t pr_pgrp;
    compat_pid_t pr_sid;
    struct old_timeval32 pr_utime;
    struct old_timeval32 pr_stime;
    struct old_timeval32 pr_cutime;
    struct old_timeval32 pr_cstime;
}
```
</details>
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
