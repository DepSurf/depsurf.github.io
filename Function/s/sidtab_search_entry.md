# Function: <code>sidtab_search_entry</code>

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
struct sidtab_entry * sidtab_search_entry(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583827296,
      "name": "sidtab_search_entry",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:253",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583827296,
      "name": "sidtab_search_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct sidtab_entry * sidtab_search_entry(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583948768,
      "name": "sidtab_search_entry",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:253",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583948768,
      "name": "sidtab_search_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct sidtab_entry * sidtab_search_entry(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583975760,
      "name": "sidtab_search_entry",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:254",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583975760,
      "name": "sidtab_search_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct sidtab_entry * sidtab_search_entry(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584341792,
      "name": "sidtab_search_entry",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:254",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584341792,
      "name": "sidtab_search_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct sidtab_entry * sidtab_search_entry(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584962816,
      "name": "sidtab_search_entry",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:254",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584962816,
      "name": "sidtab_search_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
struct sidtab_entry * sidtab_search_entry(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585676096,
      "name": "sidtab_search_entry",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:255",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585676096,
      "name": "sidtab_search_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
struct sidtab_entry * sidtab_search_entry(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585906336,
      "name": "sidtab_search_entry",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:255",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585906336,
      "name": "sidtab_search_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
struct sidtab_entry * sidtab_search_entry(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586154960,
      "name": "sidtab_search_entry",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:255",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586154960,
      "name": "sidtab_search_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct sidtab_entry * sidtab_search_entry(struct sidtab * s, u32 sid)
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
