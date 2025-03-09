# Function: <code>aa_unpack_nameX</code>

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
bool aa_unpack_nameX(struct aa_ext * e, enum aa_code code, const char * name)
```

```json
{
  "name": "aa_unpack_nameX",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585994124,
      "name": "aa_unpack_nameX",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:230",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_perm"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_perm",
        "security/apparmor/policy_unpack.c:unpack_perm",
        "security/apparmor/policy_unpack.c:unpack_perm",
        "security/apparmor/policy_unpack.c:unpack_perm",
        "security/apparmor/policy_unpack.c:unpack_perm",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_xattrs",
        "security/apparmor/policy_unpack.c:unpack_xattrs",
        "security/apparmor/policy_unpack.c:unpack_xattrs",
        "security/apparmor/policy_unpack.c:unpack_xattrs",
        "security/apparmor/policy_unpack.c:unpack_trans_table",
        "security/apparmor/policy_unpack.c:unpack_trans_table",
        "security/apparmor/policy_unpack.c:unpack_trans_table",
        "security/apparmor/policy_unpack.c:unpack_trans_table",
        "security/apparmor/policy_unpack.c:aa_unpack_str",
        "security/apparmor/policy_unpack.c:aa_unpack_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585988736,
      "name": "aa_unpack_nameX",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
bool aa_unpack_nameX(struct aa_ext * e, enum aa_code code, const char * name)
```

```json
{
  "name": "aa_unpack_nameX",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586227340,
      "name": "aa_unpack_nameX",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:221",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_perm"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_perm",
        "security/apparmor/policy_unpack.c:unpack_perm",
        "security/apparmor/policy_unpack.c:unpack_perm",
        "security/apparmor/policy_unpack.c:unpack_perm",
        "security/apparmor/policy_unpack.c:unpack_perm",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_xattrs",
        "security/apparmor/policy_unpack.c:unpack_xattrs",
        "security/apparmor/policy_unpack.c:unpack_xattrs",
        "security/apparmor/policy_unpack.c:unpack_xattrs",
        "security/apparmor/policy_unpack.c:unpack_trans_table",
        "security/apparmor/policy_unpack.c:unpack_trans_table",
        "security/apparmor/policy_unpack.c:unpack_trans_table",
        "security/apparmor/policy_unpack.c:unpack_trans_table",
        "security/apparmor/policy_unpack.c:aa_unpack_str",
        "security/apparmor/policy_unpack.c:aa_unpack_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586221264,
      "name": "aa_unpack_nameX",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
bool aa_unpack_nameX(struct aa_ext * e, enum aa_code code, const char * name)
```

```json
{
  "name": "aa_unpack_nameX",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586480012,
      "name": "aa_unpack_nameX",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:225",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_perm"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:aa_unpack",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_perm",
        "security/apparmor/policy_unpack.c:unpack_perm",
        "security/apparmor/policy_unpack.c:unpack_perm",
        "security/apparmor/policy_unpack.c:unpack_perm",
        "security/apparmor/policy_unpack.c:unpack_perm",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_xattrs",
        "security/apparmor/policy_unpack.c:unpack_xattrs",
        "security/apparmor/policy_unpack.c:unpack_xattrs",
        "security/apparmor/policy_unpack.c:unpack_xattrs",
        "security/apparmor/policy_unpack.c:unpack_trans_table",
        "security/apparmor/policy_unpack.c:unpack_trans_table",
        "security/apparmor/policy_unpack.c:unpack_trans_table",
        "security/apparmor/policy_unpack.c:unpack_trans_table",
        "security/apparmor/policy_unpack.c:aa_unpack_str",
        "security/apparmor/policy_unpack.c:aa_unpack_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586473824,
      "name": "aa_unpack_nameX",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
bool aa_unpack_nameX(struct aa_ext * e, enum aa_code code, const char * name)
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
