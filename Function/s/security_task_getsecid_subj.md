# Function: <code>security_task_getsecid_subj</code>

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
void security_task_getsecid_subj(struct task_struct * p, struct lsmblob * blob)
```

```json
{
  "name": "security_task_getsecid_subj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583874496,
      "name": "security_task_getsecid_subj",
      "external": true,
      "loc": "security/security.c:2015",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_signal_info",
        "kernel/auditfilter.c:audit_filter",
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
      "addr": 18446744071583874496,
      "name": "security_task_getsecid_subj",
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void security_task_getsecid_subj(struct task_struct * p, struct lsmblob * blob)
```

```json
{
  "name": "security_task_getsecid_subj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584238912,
      "name": "security_task_getsecid_subj",
      "external": true,
      "loc": "security/security.c:2023",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_signal_info",
        "kernel/auditfilter.c:audit_filter",
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
      "addr": 18446744071584238912,
      "name": "security_task_getsecid_subj",
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
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void security_task_getsecid_subj(struct task_struct * p, struct lsmblob * blob)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void security_task_getsecid_subj(struct task_struct * p, struct lsmblob * blob)
```
</details>
</li>
</ul>
