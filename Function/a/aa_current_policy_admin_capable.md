# Function: <code>aa_current_policy_admin_capable</code>

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
bool aa_current_policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "aa_current_policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585248304,
      "name": "aa_current_policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:749",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585248304,
      "name": "aa_current_policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
bool aa_current_policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "aa_current_policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585981664,
      "name": "aa_current_policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:829",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_set_debug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585981664,
      "name": "aa_current_policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
bool aa_current_policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "aa_current_policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586214144,
      "name": "aa_current_policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:864",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:listener_poll",
        "security/apparmor/apparmorfs.c:listener_ioctl",
        "security/apparmor/apparmorfs.c:listener_open",
        "security/apparmor/apparmorfs.c:listener_release",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_set_debug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586214144,
      "name": "aa_current_policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
bool aa_current_policy_admin_capable(struct aa_ns * ns)
```

```json
{
  "name": "aa_current_policy_admin_capable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586466704,
      "name": "aa_current_policy_admin_capable",
      "external": true,
      "loc": "security/apparmor/policy.c:895",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:listener_poll",
        "security/apparmor/apparmorfs.c:listener_ioctl",
        "security/apparmor/apparmorfs.c:listener_open",
        "security/apparmor/apparmorfs.c:listener_release",
        "security/apparmor/lsm.c:userns_restrict_dointvec",
        "security/apparmor/lsm.c:apparmor_dointvec",
        "security/apparmor/lsm.c:param_set_mode",
        "security/apparmor/lsm.c:param_set_audit",
        "security/apparmor/lsm.c:param_set_debug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586466704,
      "name": "aa_current_policy_admin_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
bool aa_current_policy_admin_capable(struct aa_ns * ns)
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
