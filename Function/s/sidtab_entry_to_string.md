# Function: <code>sidtab_entry_to_string</code>

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
int sidtab_entry_to_string(struct policydb * p, struct sidtab * sidtab, struct sidtab_entry * entry, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "sidtab_entry_to_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583858176,
      "name": "sidtab_entry_to_string",
      "external": false,
      "loc": "security/selinux/ss/services.c:1265",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_validtrans_handle_fail",
        "security/selinux/ss/services.c:security_validtrans_handle_fail",
        "security/selinux/ss/services.c:security_validtrans_handle_fail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583858176,
      "name": "sidtab_entry_to_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int sidtab_entry_to_string(struct policydb * p, struct sidtab * sidtab, struct sidtab_entry * entry, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "sidtab_entry_to_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583980576,
      "name": "sidtab_entry_to_string",
      "external": false,
      "loc": "security/selinux/ss/services.c:1278",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_validtrans_handle_fail",
        "security/selinux/ss/services.c:security_validtrans_handle_fail",
        "security/selinux/ss/services.c:security_validtrans_handle_fail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980576,
      "name": "sidtab_entry_to_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int sidtab_entry_to_string(struct policydb * p, struct sidtab * sidtab, struct sidtab_entry * entry, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "sidtab_entry_to_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584007408,
      "name": "sidtab_entry_to_string",
      "external": false,
      "loc": "security/selinux/ss/services.c:1280",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584007408,
      "name": "sidtab_entry_to_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int sidtab_entry_to_string(struct policydb * p, struct sidtab * sidtab, struct sidtab_entry * entry, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "sidtab_entry_to_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584375104,
      "name": "sidtab_entry_to_string",
      "external": false,
      "loc": "security/selinux/ss/services.c:1282",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584375104,
      "name": "sidtab_entry_to_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sidtab_entry_to_string(struct policydb * p, struct sidtab * sidtab, struct sidtab_entry * entry, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "sidtab_entry_to_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585000048,
      "name": "sidtab_entry_to_string",
      "external": false,
      "loc": "security/selinux/ss/services.c:1280",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585000048,
      "name": "sidtab_entry_to_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sidtab_entry_to_string(struct policydb * p, struct sidtab * sidtab, struct sidtab_entry * entry, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "sidtab_entry_to_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585716144,
      "name": "sidtab_entry_to_string",
      "external": false,
      "loc": "security/selinux/ss/services.c:1274",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585716144,
      "name": "sidtab_entry_to_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sidtab_entry_to_string(struct policydb * p, struct sidtab * sidtab, struct sidtab_entry * entry, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "sidtab_entry_to_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585946240,
      "name": "sidtab_entry_to_string",
      "external": false,
      "loc": "security/selinux/ss/services.c:1263",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585946240,
      "name": "sidtab_entry_to_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sidtab_entry_to_string(struct policydb * p, struct sidtab * sidtab, struct sidtab_entry * entry, char * * scontext, u32 * scontext_len)
```

```json
{
  "name": "sidtab_entry_to_string",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586195152,
      "name": "sidtab_entry_to_string",
      "external": false,
      "loc": "security/selinux/ss/services.c:1263",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_bounded_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586195152,
      "name": "sidtab_entry_to_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int sidtab_entry_to_string(struct policydb * p, struct sidtab * sidtab, struct sidtab_entry * entry, char * * scontext, u32 * scontext_len)
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
