# Function: <code>compute_perms</code>

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
struct aa_perms * compute_perms(struct aa_dfa * dfa, u32 version)
```

```json
{
  "name": "compute_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585341808,
      "name": "compute_perms",
      "external": false,
      "loc": "security/apparmor/policy_compat.c:242",
      "file": "security/apparmor/policy_compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_compat.c:aa_compat_map_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585341808,
      "name": "compute_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
struct aa_perms * compute_perms(struct aa_dfa * dfa, u32 version)
```

```json
{
  "name": "compute_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586082608,
      "name": "compute_perms",
      "external": false,
      "loc": "security/apparmor/policy_compat.c:242",
      "file": "security/apparmor/policy_compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_compat.c:aa_compat_map_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586082608,
      "name": "compute_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
struct aa_perms * compute_perms(struct aa_dfa * dfa, u32 version, u32 * size)
```

```json
{
  "name": "compute_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586317936,
      "name": "compute_perms",
      "external": false,
      "loc": "security/apparmor/policy_compat.c:248",
      "file": "security/apparmor/policy_compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_compat.c:aa_compat_map_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586317936,
      "name": "compute_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compute_perms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586576299,
      "name": "compute_perms",
      "external": false,
      "loc": "security/apparmor/policy_compat.c:253",
      "file": "security/apparmor/policy_compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_compat.c:aa_compat_map_policy"
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
struct aa_perms * compute_perms(struct aa_dfa * dfa, u32 version)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 * size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct aa_perms * compute_perms(struct aa_dfa * dfa, u32 version, u32 * size)
```
</details>
</li>
</ul>
