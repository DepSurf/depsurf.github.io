# Function: <code>aa_pdb_free_kref</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void aa_pdb_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_pdb_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586209689,
      "name": "aa_pdb_free_kref",
      "external": true,
      "loc": "security/apparmor/policy.c:120",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/notify.c:aa_free_ruleset",
        "security/apparmor/notify.c:aa_free_ruleset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586209904,
      "name": "aa_pdb_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void aa_pdb_free_kref(struct kref * kref)
```

```json
{
  "name": "aa_pdb_free_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586461865,
      "name": "aa_pdb_free_kref",
      "external": true,
      "loc": "security/apparmor/policy.c:121",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/lsm.c:apparmor_init",
        "security/apparmor/lsm.c:aa_setup_dfa_engine",
        "security/apparmor/notify.c:aa_free_ruleset",
        "security/apparmor/notify.c:aa_free_ruleset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586462080,
      "name": "aa_pdb_free_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void aa_pdb_free_kref(struct kref * kref)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
