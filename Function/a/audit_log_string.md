# Function: <code>audit_log_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580033502,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:549",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580040699,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:549",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580051253,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:549",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_log_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580064439,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:549",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580067889,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:549",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_mark_handle_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580068776,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:549",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:kill_rules"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582476901,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:549",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582481274,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:549",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582546356,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:549",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582581946,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:549",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582606711,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:549",
      "file": "security/integrity/integrity_audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580066062,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:552",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580073435,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:552",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580097639,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:552",
      "file": "kernel/audit_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580101136,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:552",
      "file": "kernel/audit_fsnotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_fsnotify.c:audit_mark_handle_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580102048,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:552",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:kill_rules"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582709029,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:552",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582713978,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:552",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582786676,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:552",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582825066,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:552",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582851831,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:552",
      "file": "security/integrity/integrity_audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580106286,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:552",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582803621,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:552",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582808570,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:552",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582882068,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:552",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582920938,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:552",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582947863,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:552",
      "file": "security/integrity/integrity_audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580111614,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:582",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582893365,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:582",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582896656,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:582",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582952148,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:582",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582979466,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:582",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582998039,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:582",
      "file": "security/integrity/integrity_audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580164174,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:584",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583051685,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:584",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583055211,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:584",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583114244,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:584",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583143338,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:584",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583162135,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:584",
      "file": "security/integrity/integrity_audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580223998,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:595",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583252309,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:595",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583256176,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:595",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583319988,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:595",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583349210,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:595",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583367623,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:595",
      "file": "security/integrity/integrity_audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "security/integrity/integrity_audit.c:integrity_audit_msg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580276402,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:594",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583370325,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:594",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583373920,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:594",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583438473,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:594",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583467850,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:594",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580327389,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:664",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583557411,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:664",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583560816,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:664",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583623514,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:664",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583652233,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:664",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580376189,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583663139,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583666544,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583729690,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583758521,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void audit_log_string(struct audit_buffer * ab, const char * buf)
```

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580451869,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:693",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_d_path"
      ]
    },
    {
      "addr": 18446744071583935855,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:693",
      "file": "security/lsm_audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/lsm_audit.c:dump_common_audit_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584024019,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:693",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584029230,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:693",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/ipc.c:audit_signal_cb",
        "security/apparmor/ipc.c:audit_signal_cb",
        "security/apparmor/ipc.c:audit_signal_cb",
        "security/apparmor/ipc.c:audit_signal_cb",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584112122,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:693",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584148697,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:693",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451472,
      "name": "audit_log_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491641888,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495456112,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495459904,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495525944,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495558632,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225594000,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 3228823068,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 3228826788,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 3228892436,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 3228921788,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284637808,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289506128,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289511424,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289605336,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289649092,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272037240,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274644962,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274647906,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274703294,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274729158,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580344989,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583631875,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583635280,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583698426,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583727257,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580292157,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583568931,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583572336,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583635482,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583664313,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580336237,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583615651,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583619056,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583682202,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583711033,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_log_string",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580391469,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_d_path",
        "kernel/audit.c:audit_log_d_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583713507,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre",
        "security/apparmor/audit.c:audit_pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583717120,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_signal_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask",
        "security/apparmor/ipc.c:audit_ptrace_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583781946,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:audit_file_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583811529,
      "name": "audit_log_string",
      "external": false,
      "loc": "include/linux/audit.h:657",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:audit_net_cb",
        "security/apparmor/net.c:audit_net_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void audit_log_string(struct audit_buffer * ab, const char * buf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void audit_log_string(struct audit_buffer * ab, const char * buf)
```
</details>
</li>
</ul>
