# Struct: <code>compat_semid_ds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    compat_time_t sem_otime;
    compat_time_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    compat_time_t sem_otime;
    compat_time_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    compat_time_t sem_otime;
    compat_time_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    compat_time_t sem_otime;
    compat_time_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    compat_time_t sem_otime;
    compat_time_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    compat_time_t sem_otime;
    compat_time_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
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
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>compat_time_t sem_otime</code> ➡️ <code>old_time32_t sem_otime</code>
</li>
<li>
<b>Field type changed. </b>
<code>compat_time_t sem_ctime</code> ➡️ <code>old_time32_t sem_ctime</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct compat_semid_ds {
    struct compat_ipc_perm sem_perm;
    old_time32_t sem_otime;
    old_time32_t sem_ctime;
    compat_uptr_t sem_base;
    compat_uptr_t sem_pending;
    compat_uptr_t sem_pending_last;
    compat_uptr_t undo;
    short unsigned int sem_nsems;
}
```
</details>
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
