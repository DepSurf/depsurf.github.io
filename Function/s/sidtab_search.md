# Function: <code>sidtab_search</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582313104,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:115",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_validate_transition",
        "security/selinux/ss/services.c:security_validate_transition",
        "security/selinux/ss/services.c:security_validate_transition",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313104,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582534272,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:115",
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
      "addr": 18446744071582534272,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582627088,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:115",
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
      "addr": 18446744071582627088,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582719024,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:108",
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
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582719024,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582874992,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:109",
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
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582874992,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583073184,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:109",
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
      "addr": 18446744071583073184,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583188080,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:165",
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
      "addr": 18446744071583188080,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583375328,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:165",
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
      "addr": 18446744071583375328,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583481264,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:163",
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
      "addr": 18446744071583481264,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sidtab_search",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583881956,
      "name": "sidtab_search",
      "external": false,
      "loc": "security/selinux/ss/sidtab.h:110",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583887291,
      "name": "sidtab_search",
      "external": false,
      "loc": "security/selinux/ss/sidtab.h:110",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sidtab_search",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584002341,
      "name": "sidtab_search",
      "external": false,
      "loc": "security/selinux/ss/sidtab.h:110",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584007419,
      "name": "sidtab_search",
      "external": false,
      "loc": "security/selinux/ss/sidtab.h:110",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sidtab_search",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584030197,
      "name": "sidtab_search",
      "external": false,
      "loc": "security/selinux/ss/sidtab.h:111",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584035451,
      "name": "sidtab_search",
      "external": false,
      "loc": "security/selinux/ss/sidtab.h:111",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sidtab_search",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584400613,
      "name": "sidtab_search",
      "external": false,
      "loc": "security/selinux/ss/sidtab.h:111",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584406395,
      "name": "sidtab_search",
      "external": false,
      "loc": "security/selinux/ss/sidtab.h:111",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sidtab_search",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585026965,
      "name": "sidtab_search",
      "external": false,
      "loc": "security/selinux/ss/sidtab.h:111",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585035136,
      "name": "sidtab_search",
      "external": false,
      "loc": "security/selinux/ss/sidtab.h:111",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_context_to_sid"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sidtab_search",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585744885,
      "name": "sidtab_search",
      "external": false,
      "loc": "security/selinux/ss/sidtab.h:110",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585753648,
      "name": "sidtab_search",
      "external": false,
      "loc": "security/selinux/ss/sidtab.h:110",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_context_to_sid"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sidtab_search",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585975543,
      "name": "sidtab_search",
      "external": false,
      "loc": "security/selinux/ss/sidtab.h:110",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585984304,
      "name": "sidtab_search",
      "external": false,
      "loc": "security/selinux/ss/sidtab.h:110",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_context_to_sid"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sidtab_search",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586222839,
      "name": "sidtab_search",
      "external": false,
      "loc": "security/selinux/ss/sidtab.h:110",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_compute_xperms_decision"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586231632,
      "name": "sidtab_search",
      "external": false,
      "loc": "security/selinux/ss/sidtab.h:110",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_context_to_sid"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495246344,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:163",
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
      "addr": 18446603336495246344,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228627972,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:163",
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
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228627972,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289215424,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:163",
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
      "addr": 13835058055289215424,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274471728,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:163",
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
      "addr": 18446743936274471728,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583450000,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:163",
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
      "addr": 18446744071583450000,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583387072,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:163",
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
      "addr": 18446744071583387072,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583433776,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:163",
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
      "addr": 18446744071583433776,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct context * sidtab_search(struct sidtab * s, u32 sid)
```

```json
{
  "name": "sidtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583530032,
      "name": "sidtab_search",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:163",
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
      "addr": 18446744071583530032,
      "name": "sidtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct context * sidtab_search(struct sidtab * s, u32 sid)
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
