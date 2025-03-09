# Function: <code>__do_sys_futex_waitv</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_futex_waitv(struct futex_waitv * waiters, unsigned int nr_futexes, unsigned int flags, struct __kernel_timespec * timeout, clockid_t clockid)
```

```json
{
  "name": "__do_sys_futex_waitv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580629088,
      "name": "__do_sys_futex_waitv",
      "external": false,
      "loc": "kernel/futex/syscalls.c:246",
      "file": "kernel/futex/syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/syscalls.c:__ia32_sys_futex_waitv",
        "kernel/futex/syscalls.c:__x64_sys_futex_waitv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580629088,
      "name": "__do_sys_futex_waitv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 956
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_futex_waitv(struct futex_waitv * waiters, unsigned int nr_futexes, unsigned int flags, struct __kernel_timespec * timeout, clockid_t clockid)
```

```json
{
  "name": "__do_sys_futex_waitv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580895344,
      "name": "__do_sys_futex_waitv",
      "external": false,
      "loc": "kernel/futex/syscalls.c:246",
      "file": "kernel/futex/syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/syscalls.c:__ia32_sys_futex_waitv",
        "kernel/futex/syscalls.c:__x64_sys_futex_waitv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580895344,
      "name": "__do_sys_futex_waitv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 956
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_futex_waitv(struct futex_waitv * waiters, unsigned int nr_futexes, unsigned int flags, struct __kernel_timespec * timeout, clockid_t clockid)
```

```json
{
  "name": "__do_sys_futex_waitv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580979200,
      "name": "__do_sys_futex_waitv",
      "external": false,
      "loc": "kernel/futex/syscalls.c:246",
      "file": "kernel/futex/syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/syscalls.c:__ia32_sys_futex_waitv",
        "kernel/futex/syscalls.c:__x64_sys_futex_waitv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580979200,
      "name": "__do_sys_futex_waitv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 956
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_futex_waitv(struct futex_waitv * waiters, unsigned int nr_futexes, unsigned int flags, struct __kernel_timespec * timeout, clockid_t clockid)
```

```json
{
  "name": "__do_sys_futex_waitv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581077696,
      "name": "__do_sys_futex_waitv",
      "external": false,
      "loc": "kernel/futex/syscalls.c:290",
      "file": "kernel/futex/syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/syscalls.c:__ia32_sys_futex_waitv",
        "kernel/futex/syscalls.c:__x64_sys_futex_waitv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077696,
      "name": "__do_sys_futex_waitv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
    }
  ]
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
long int __do_sys_futex_waitv(struct futex_waitv * waiters, unsigned int nr_futexes, unsigned int flags, struct __kernel_timespec * timeout, clockid_t clockid)
```
</details>
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
