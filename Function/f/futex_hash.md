# Function: <code>futex_hash</code>

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
struct futex_hash_bucket * futex_hash(union futex_key * key)
```

```json
{
  "name": "futex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580623440,
      "name": "futex_hash",
      "external": true,
      "loc": "kernel/futex/core.c:115",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:exit_pi_state_list",
        "kernel/futex/core.c:futex_q_lock",
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/waitwake.c:futex_wake_op",
        "kernel/futex/waitwake.c:futex_wake_op",
        "kernel/futex/waitwake.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580623440,
      "name": "futex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct futex_hash_bucket * futex_hash(union futex_key * key)
```

```json
{
  "name": "futex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889280,
      "name": "futex_hash",
      "external": true,
      "loc": "kernel/futex/core.c:115",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:exit_pi_state_list",
        "kernel/futex/core.c:futex_q_lock",
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/waitwake.c:futex_wake_op",
        "kernel/futex/waitwake.c:futex_wake_op",
        "kernel/futex/waitwake.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889280,
      "name": "futex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct futex_hash_bucket * futex_hash(union futex_key * key)
```

```json
{
  "name": "futex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580973120,
      "name": "futex_hash",
      "external": true,
      "loc": "kernel/futex/core.c:115",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:exit_pi_state_list",
        "kernel/futex/core.c:futex_q_lock",
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/waitwake.c:futex_wake_op",
        "kernel/futex/waitwake.c:futex_wake_op",
        "kernel/futex/waitwake.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580973120,
      "name": "futex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct futex_hash_bucket * futex_hash(union futex_key * key)
```

```json
{
  "name": "futex_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581067856,
      "name": "futex_hash",
      "external": true,
      "loc": "kernel/futex/core.c:116",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:exit_pi_state_list",
        "kernel/futex/core.c:futex_q_lock",
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/waitwake.c:futex_wake_op",
        "kernel/futex/waitwake.c:futex_wake_op",
        "kernel/futex/waitwake.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581067856,
      "name": "futex_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct futex_hash_bucket * futex_hash(union futex_key * key)
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
