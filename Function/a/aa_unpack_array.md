# Function: <code>aa_unpack_array</code>

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
bool aa_unpack_array(struct aa_ext * e, const char * name, u16 * size)
```

```json
{
  "name": "aa_unpack_array",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585995513,
      "name": "aa_unpack_array",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:330",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_xattrs",
        "security/apparmor/policy_unpack.c:unpack_trans_table"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585989136,
      "name": "aa_unpack_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
bool aa_unpack_array(struct aa_ext * e, const char * name, u16 * size)
```

```json
{
  "name": "aa_unpack_array",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586228711,
      "name": "aa_unpack_array",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:341",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_xattrs",
        "security/apparmor/policy_unpack.c:unpack_trans_table"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586221664,
      "name": "aa_unpack_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
bool aa_unpack_array(struct aa_ext * e, const char * name, u16 * size)
```

```json
{
  "name": "aa_unpack_array",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586481354,
      "name": "aa_unpack_array",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:345",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/policy_unpack.c:unpack_rlimits",
        "security/apparmor/policy_unpack.c:unpack_secmark",
        "security/apparmor/policy_unpack.c:unpack_xattrs",
        "security/apparmor/policy_unpack.c:unpack_trans_table"
      ],
      "caller_func": [
        "security/apparmor/policy_unpack.c:unpack_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586474224,
      "name": "aa_unpack_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
bool aa_unpack_array(struct aa_ext * e, const char * name, u16 * size)
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
