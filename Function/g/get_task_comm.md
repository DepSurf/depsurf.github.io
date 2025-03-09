# Function: <code>get_task_comm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * get_task_comm(char * buf, struct task_struct * tsk)
```

```json
{
  "name": "get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581017856,
      "name": "get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1070",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:SyS_prctl",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581017856,
      "name": "get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
char * get_task_comm(char * buf, struct task_struct * tsk)
```

```json
{
  "name": "get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581176288,
      "name": "get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1217",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:SyS_prctl",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "net/core/ethtool.c:ethtool_get_settings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176288,
      "name": "get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
char * get_task_comm(char * buf, struct task_struct * tsk)
```

```json
{
  "name": "get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581253264,
      "name": "get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1224",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:SyS_prctl",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open",
        "net/core/ethtool.c:ethtool_get_settings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581253264,
      "name": "get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
char * get_task_comm(char * buf, struct task_struct * tsk)
```

```json
{
  "name": "get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581302704,
      "name": "get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1250",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:SyS_prctl",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open",
        "net/core/ethtool.c:ethtool_get_settings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302704,
      "name": "get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
char * get_task_comm(char * buf, struct task_struct * tsk)
```
</details>
</li>
</ul>
