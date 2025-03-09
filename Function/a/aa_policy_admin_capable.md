# Function: <code>aa_policy_admin_capable</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool aa_policy_admin_capable(struct aa_label * label, struct aa_ns * ns)
```

```json
{
  "name": "aa_policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:725",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/policy.c:aa_current_policy_admin_capable",
        "security/apparmor/policy.c:aa_current_policy_admin_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594087158,
      "name": "aa_policy_admin_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071585247600,
      "name": "aa_policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool aa_policy_admin_capable(const struct cred * subj_cred, struct aa_label * label, struct aa_ns * ns)
```

```json
{
  "name": "aa_policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:803",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/policy.c:aa_current_policy_admin_capable",
        "security/apparmor/policy.c:aa_current_policy_admin_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596100394,
      "name": "aa_policy_admin_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585980944,
      "name": "aa_policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool aa_policy_admin_capable(const struct cred * subj_cred, struct aa_label * label, struct aa_ns * ns)
```

```json
{
  "name": "aa_policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:838",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/policy.c:aa_current_policy_admin_capable",
        "security/apparmor/policy.c:aa_current_policy_admin_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596623663,
      "name": "aa_policy_admin_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071586213504,
      "name": "aa_policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
bool aa_policy_admin_capable(const struct cred * subj_cred, struct aa_label * label, struct aa_ns * ns)
```

```json
{
  "name": "aa_policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:869",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_may_manage_policy",
        "security/apparmor/policy.c:aa_current_policy_admin_capable",
        "security/apparmor/policy.c:aa_current_policy_admin_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597529961,
      "name": "aa_policy_admin_capable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071586466080,
      "name": "aa_policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
bool aa_policy_admin_capable(struct aa_label * label, struct aa_ns * ns)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred * subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>label, ns</code> ➡️ <code>subj_cred, label, ns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
