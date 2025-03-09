# Function: <code>audit_log_subject_context</code>

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
int audit_log_subject_context(struct audit_buffer * ab, struct lsmblob * blob)
```

```json
{
  "name": "audit_log_subject_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580808976,
      "name": "audit_log_subject_context",
      "external": true,
      "loc": "kernel/audit.c:2228",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808976,
      "name": "audit_log_subject_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
int audit_log_subject_context(struct audit_buffer * ab, struct lsmblob * blob)
```

```json
{
  "name": "audit_log_subject_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581094912,
      "name": "audit_log_subject_context",
      "external": true,
      "loc": "kernel/audit.c:2226",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094912,
      "name": "audit_log_subject_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
int audit_log_subject_context(struct audit_buffer * ab, struct lsmblob * blob)
```

```json
{
  "name": "audit_log_subject_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581186512,
      "name": "audit_log_subject_context",
      "external": true,
      "loc": "kernel/audit.c:2226",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581186512,
      "name": "audit_log_subject_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
int audit_log_subject_context(struct audit_buffer * ab, struct lsmblob * blob)
```

```json
{
  "name": "audit_log_subject_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_log_subject_context",
      "external": true,
      "loc": "kernel/audit.c:2244",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit.c:audit_log_common_recv_msg",
        "kernel/audit.c:audit_log_config_change",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597419542,
      "name": "audit_log_subject_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581292688,
      "name": "audit_log_subject_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 601
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
int audit_log_subject_context(struct audit_buffer * ab, struct lsmblob * blob)
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
