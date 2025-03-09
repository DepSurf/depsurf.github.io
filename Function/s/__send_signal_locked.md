# Function: <code>__send_signal_locked</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __send_signal_locked(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__send_signal_locked",
      "external": false,
      "loc": "kernel/signal.c:1078",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765280,
      "name": "__send_signal_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1193
    },
    {
      "addr": 18446744071593869391,
      "name": "__send_signal_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __send_signal_locked(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__send_signal_locked",
      "external": false,
      "loc": "kernel/signal.c:1079",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896848,
      "name": "__send_signal_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1182
    },
    {
      "addr": 18446744071595974920,
      "name": "__send_signal_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __send_signal_locked(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__send_signal_locked",
      "external": false,
      "loc": "kernel/signal.c:1083",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946256,
      "name": "__send_signal_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1274
    },
    {
      "addr": 18446744071596492440,
      "name": "__send_signal_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __send_signal_locked(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
```

```json
{
  "name": "__send_signal_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__send_signal_locked",
      "external": false,
      "loc": "kernel/signal.c:1073",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kdb_send_sig",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:kill_pid_usb_asyncio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579985648,
      "name": "__send_signal_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1274
    },
    {
      "addr": 18446744071597389201,
      "name": "__send_signal_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int __send_signal_locked(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type, bool force)
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
