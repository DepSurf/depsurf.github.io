# Function: <code>audit_log_lsm</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void audit_log_lsm(struct lsmblob * blob, bool exiting)
```

```json
{
  "name": "audit_log_lsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580481216,
      "name": "audit_log_lsm",
      "external": true,
      "loc": "kernel/auditsc.c:1428",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_log_exit",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580481216,
      "name": "audit_log_lsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
void audit_log_lsm(struct lsmblob * blob, bool exiting)
```

```json
{
  "name": "audit_log_lsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580469584,
      "name": "audit_log_lsm",
      "external": true,
      "loc": "kernel/auditsc.c:1446",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_log_exit",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469584,
      "name": "audit_log_lsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
void audit_log_lsm(struct lsmblob * blob, bool exiting)
```

```json
{
  "name": "audit_log_lsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580472960,
      "name": "audit_log_lsm",
      "external": true,
      "loc": "kernel/auditsc.c:1445",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_log_exit",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580472960,
      "name": "audit_log_lsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
void audit_log_lsm(struct lsmblob * blob, bool exiting)
```

```json
{
  "name": "audit_log_lsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580640112,
      "name": "audit_log_lsm",
      "external": true,
      "loc": "kernel/auditsc.c:1454",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_log_config_change",
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_log_exit",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete",
        "net/xfrm/xfrm_policy.c:xfrm_audit_policy_add",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_delete",
        "net/xfrm/xfrm_state.c:xfrm_audit_state_add",
        "net/netlabel/netlabel_user.c:netlbl_audit_start_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580640112,
      "name": "audit_log_lsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void audit_log_lsm(struct lsmblob * blob, bool exiting)
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void audit_log_lsm(struct lsmblob * blob, bool exiting)
```
</details>
</li>
</ul>
