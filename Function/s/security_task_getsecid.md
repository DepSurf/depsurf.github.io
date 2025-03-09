# Function: <code>security_task_getsecid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582233968,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:944",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter_user",
        "kernel/auditsc.c:audit_filter_rules",
        "kernel/auditsc.c:__audit_ptrace",
        "kernel/auditsc.c:__audit_signal_info",
        "kernel/auditsc.c:__audit_signal_info",
        "kernel/auditsc.c:__audit_signal_info",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582233968,
      "name": "security_task_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582452464,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:968",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:__audit_signal_info",
        "kernel/auditsc.c:__audit_signal_info",
        "kernel/auditsc.c:__audit_signal_info",
        "kernel/auditsc.c:__audit_ptrace",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582452464,
      "name": "security_task_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582544928,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:989",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:__audit_signal_info",
        "kernel/auditsc.c:__audit_signal_info",
        "kernel/auditsc.c:__audit_signal_info",
        "kernel/auditsc.c:__audit_ptrace",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582544928,
      "name": "security_task_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582630144,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:1626",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:audit_signal_info",
        "kernel/auditsc.c:audit_signal_info",
        "kernel/auditsc.c:audit_signal_info",
        "kernel/auditsc.c:__audit_ptrace",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582630144,
      "name": "security_task_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582783536,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:1588",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:audit_signal_info",
        "kernel/auditsc.c:audit_signal_info",
        "kernel/auditsc.c:audit_signal_info",
        "kernel/auditsc.c:__audit_ptrace",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbdev_open",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582783536,
      "name": "security_task_getsecid",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582985664,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:1092",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:audit_signal_info",
        "kernel/auditsc.c:audit_signal_info",
        "kernel/auditsc.c:audit_signal_info",
        "kernel/auditsc.c:__audit_ptrace",
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582985664,
      "name": "security_task_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583097440,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:1700",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:audit_signal_info",
        "kernel/auditsc.c:audit_signal_info",
        "kernel/auditsc.c:audit_signal_info",
        "kernel/auditsc.c:__audit_ptrace",
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583097440,
      "name": "security_task_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583280656,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:1719",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_signal_info",
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:__audit_ptrace",
        "security/integrity/ima/ima_main.c:ima_kexec_cmdline",
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583280656,
      "name": "security_task_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583386624,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:1758",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_signal_info",
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:__audit_ptrace",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583386624,
      "name": "security_task_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void security_task_getsecid(struct task_struct * p, struct lsmblob * blob)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583729088,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:1948",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_signal_info",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:__audit_ptrace",
        "kernel/auditsc.c:audit_log_lsm",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mprotect",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583729088,
      "name": "security_task_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void security_task_getsecid(struct task_struct * p, struct lsmblob * blob)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583849296,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:1965",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_signal_info",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:__audit_ptrace",
        "kernel/auditsc.c:audit_log_lsm",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mprotect",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849296,
      "name": "security_task_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495136312,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:1758",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_signal_info",
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:__audit_ptrace",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495136312,
      "name": "security_task_getsecid",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228524280,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:1758",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_signal_info",
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:__audit_ptrace",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228524280,
      "name": "security_task_getsecid",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289049776,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:1758",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_signal_info",
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:__audit_ptrace",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289049776,
      "name": "security_task_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274387250,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:1758",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_signal_info",
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:__audit_ptrace",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274387250,
      "name": "security_task_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583355360,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:1758",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_signal_info",
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:__audit_ptrace",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583355360,
      "name": "security_task_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583292464,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:1758",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_signal_info",
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:__audit_ptrace",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583292464,
      "name": "security_task_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583339136,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:1758",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_signal_info",
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:__audit_ptrace",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583339136,
      "name": "security_task_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void security_task_getsecid(struct task_struct * p, u32 * secid)
```

```json
{
  "name": "security_task_getsecid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583434320,
      "name": "security_task_getsecid",
      "external": true,
      "loc": "security/security.c:1758",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_signal_info",
        "kernel/audit.c:audit_log_task_context",
        "kernel/auditfilter.c:audit_filter",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:audit_signal_info_syscall",
        "kernel/auditsc.c:__audit_ptrace",
        "security/integrity/ima/ima_main.c:process_buffer_measurement",
        "security/integrity/ima/ima_main.c:ima_post_read_file",
        "security/integrity/ima/ima_main.c:ima_file_check",
        "security/integrity/ima/ima_main.c:ima_bprm_check",
        "security/integrity/ima/ima_main.c:ima_file_mmap",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_remove",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583434320,
      "name": "security_task_getsecid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmblob * blob</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 * secid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void security_task_getsecid(struct task_struct * p, struct lsmblob * blob)
```
</details>
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
