# Function: <code>audit_stamp_context</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_stamp_context(struct audit_context * ctx)
```

```json
{
  "name": "audit_stamp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580488440,
      "name": "audit_stamp_context",
      "external": true,
      "loc": "kernel/auditsc.c:2196",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_core_dumps"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446744071580485456,
      "name": "audit_stamp_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_stamp_context(struct audit_context * ctx)
```

```json
{
  "name": "audit_stamp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580476696,
      "name": "audit_stamp_context",
      "external": true,
      "loc": "kernel/auditsc.c:2213",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_core_dumps"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446744071580473712,
      "name": "audit_stamp_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_stamp_context(struct audit_context * ctx)
```

```json
{
  "name": "audit_stamp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580480664,
      "name": "audit_stamp_context",
      "external": true,
      "loc": "kernel/auditsc.c:2210",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_core_dumps"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446744071580477664,
      "name": "audit_stamp_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_stamp_context(struct audit_context * ctx)
```

```json
{
  "name": "audit_stamp_context",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580648312,
      "name": "audit_stamp_context",
      "external": true,
      "loc": "kernel/auditsc.c:2223",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_core_dumps",
        "kernel/auditsc.c:audit_core_dumps"
      ],
      "caller_func": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_receive_msg",
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
      "addr": 18446744071580645104,
      "name": "audit_stamp_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void audit_stamp_context(struct audit_context * ctx)
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
void audit_stamp_context(struct audit_context * ctx)
```
</details>
</li>
</ul>
