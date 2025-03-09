# Function: <code>sched_core_share_pid</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int sched_core_share_pid(unsigned int cmd, pid_t pid, enum pid_type type, long unsigned int uaddr)
```

```json
{
  "name": "sched_core_share_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580074960,
      "name": "sched_core_share_pid",
      "external": true,
      "loc": "kernel/sched/core_sched.c:126",
      "file": "kernel/sched/core_sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580074960,
      "name": "sched_core_share_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int sched_core_share_pid(unsigned int cmd, pid_t pid, enum pid_type type, long unsigned int uaddr)
```

```json
{
  "name": "sched_core_share_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580202512,
      "name": "sched_core_share_pid",
      "external": true,
      "loc": "kernel/sched/core_sched.c:128",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580202512,
      "name": "sched_core_share_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1235
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
int sched_core_share_pid(unsigned int cmd, pid_t pid, enum pid_type type, long unsigned int uaddr)
```

```json
{
  "name": "sched_core_share_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580393632,
      "name": "sched_core_share_pid",
      "external": true,
      "loc": "kernel/sched/core_sched.c:129",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580393632,
      "name": "sched_core_share_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1250
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
int sched_core_share_pid(unsigned int cmd, pid_t pid, enum pid_type type, long unsigned int uaddr)
```

```json
{
  "name": "sched_core_share_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580462080,
      "name": "sched_core_share_pid",
      "external": true,
      "loc": "kernel/sched/core_sched.c:129",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580462080,
      "name": "sched_core_share_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1261
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
int sched_core_share_pid(unsigned int cmd, pid_t pid, enum pid_type type, long unsigned int uaddr)
```

```json
{
  "name": "sched_core_share_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580521744,
      "name": "sched_core_share_pid",
      "external": true,
      "loc": "kernel/sched/core_sched.c:129",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521744,
      "name": "sched_core_share_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1290
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int sched_core_share_pid(unsigned int cmd, pid_t pid, enum pid_type type, long unsigned int uaddr)
```
</details>
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
