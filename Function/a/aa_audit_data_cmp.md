# Function: <code>aa_audit_data_cmp</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int aa_audit_data_cmp(struct apparmor_audit_data * lhs, struct apparmor_audit_data * rhs)
```

```json
{
  "name": "aa_audit_data_cmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585929616,
      "name": "aa_audit_data_cmp",
      "external": true,
      "loc": "security/apparmor/audit.c:305",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/audit.c:aa_audit_cache_insert",
        "security/apparmor/audit.c:aa_audit_cache_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585929616,
      "name": "aa_audit_data_cmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int aa_audit_data_cmp(struct apparmor_audit_data * lhs, struct apparmor_audit_data * rhs)
```

```json
{
  "name": "aa_audit_data_cmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586163147,
      "name": "aa_audit_data_cmp",
      "external": true,
      "loc": "security/apparmor/audit.c:307",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit_cache_insert",
        "security/apparmor/audit.c:aa_audit_cache_find"
      ],
      "caller_func": [
        "security/apparmor/audit.c:aa_audit_cache_insert",
        "security/apparmor/audit.c:aa_audit_cache_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586160480,
      "name": "aa_audit_data_cmp.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071586162096,
      "name": "aa_audit_data_cmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int aa_audit_data_cmp(struct apparmor_audit_data * lhs, struct apparmor_audit_data * rhs)
```

```json
{
  "name": "aa_audit_data_cmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586411995,
      "name": "aa_audit_data_cmp",
      "external": true,
      "loc": "security/apparmor/audit.c:316",
      "file": "security/apparmor/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/audit.c:aa_audit_cache_insert",
        "security/apparmor/audit.c:aa_audit_cache_find"
      ],
      "caller_func": [
        "security/apparmor/audit.c:aa_audit_cache_insert",
        "security/apparmor/audit.c:aa_audit_cache_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586409728,
      "name": "aa_audit_data_cmp.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071586410944,
      "name": "aa_audit_data_cmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
long int aa_audit_data_cmp(struct apparmor_audit_data * lhs, struct apparmor_audit_data * rhs)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
