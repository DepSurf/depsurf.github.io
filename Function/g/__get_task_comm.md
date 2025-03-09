# Function: <code>__get_task_comm</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581442560,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1231",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:SyS_prctl",
        "kernel/futex.c:futex_wake_op",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581442560,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581604144,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1235",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/futex.c:do_futex",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581604144,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581691552,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1239",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/futex.c:futex_wake_op",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:compat_tty_tiocsserial",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581691552,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581809664,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1240",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/futex.c:futex_wake_op",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:compat_tty_tiocsserial",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581809664,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581882256,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1241",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/futex.c:futex_wake_op",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:compat_tty_tiocsserial",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882256,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582110032,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1306",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/audit.c:audit_log_multicast",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:compat_tty_tiocsserial",
        "drivers/tty/tty_io.c:tty_tiocsserial",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582110032,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582156448,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1218",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/audit.c:audit_log_multicast",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "drivers/tty/tty_io.c:compat_tty_tiocsserial",
        "drivers/tty/tty_io.c:tty_tiocsserial",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582156448,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582180816,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1210",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/audit.c:audit_log_multicast",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "drivers/tty/tty_io.c:tty_set_serial",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582180816,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582498272,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1210",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/audit.c:audit_log_multicast",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "drivers/tty/tty_io.c:tty_set_serial",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582498272,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583014096,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1217",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/kthread.c:get_kthread_comm",
        "kernel/futex/waitwake.c:futex_atomic_op_inuser",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "drivers/tty/tty_io.c:tty_set_serial",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014096,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583577520,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1212",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/kthread.c:get_kthread_comm",
        "kernel/futex/waitwake.c:futex_atomic_op_inuser",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "drivers/tty/tty_io.c:tty_set_serial",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583577520,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583793616,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1215",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/kthread.c:get_kthread_comm",
        "kernel/futex/waitwake.c:futex_atomic_op_inuser",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "drivers/tty/tty_io.c:tty_set_serial",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open",
        "net/wireless/wext-core.c:wireless_warn_cfg80211_wext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583793616,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583999712,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1230",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/kthread.c:get_kthread_comm",
        "kernel/futex/waitwake.c:futex_atomic_op_inuser",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "kernel/auditsc.c:audit_log_task",
        "kernel/auditsc.c:__audit_log_nfcfg",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_message",
        "drivers/tty/tty_io.c:tty_set_serial",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open",
        "net/wireless/wext-core.c:wireless_warn_cfg80211_wext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583999712,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493352288,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1241",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__arm64_sys_prctl",
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:compat_tty_tiocsserial",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493352288,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226943024,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1241",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__se_sys_prctl",
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226943024,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286903904,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1241",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__se_sys_prctl",
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:compat_tty_tiocsserial",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286903904,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273080478,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1241",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__se_sys_prctl",
        "kernel/futex.c:futex_wake_op",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273080478,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
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
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581850992,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1241",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/futex.c:futex_wake_op",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:compat_tty_tiocsserial",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581850992,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581788656,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1241",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/futex.c:futex_wake_op",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:compat_tty_tiocsserial",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581788656,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581842304,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1241",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/futex.c:futex_wake_op",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:compat_tty_tiocsserial",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842304,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```

```json
{
  "name": "__get_task_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581907248,
      "name": "__get_task_comm",
      "external": true,
      "loc": "fs/exec.c:1241",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:cap_validate_magic",
        "kernel/capability.c:cap_validate_magic",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/futex.c:futex_wake_op",
        "kernel/auditsc.c:audit_log_task",
        "fs/proc/array.c:proc_task_name",
        "security/yama/yama_lsm.c:report_access",
        "security/integrity/integrity_audit.c:integrity_audit_msg",
        "drivers/tty/tty_io.c:compat_tty_tiocsserial",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_audit.c:tty_audit_log",
        "drivers/connector/cn_proc.c:proc_comm_connector",
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581907248,
      "name": "__get_task_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
char * __get_task_comm(char * buf, size_t buf_size, struct task_struct * tsk)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
