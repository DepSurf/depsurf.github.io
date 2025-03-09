# Function: <code>aa_lookup_fperms</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct aa_perms * aa_lookup_fperms(struct aa_policydb * file_rules, unsigned int state, struct path_cond * cond)
```

```json
{
  "name": "aa_lookup_fperms",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585300840,
      "name": "aa_lookup_fperms",
      "external": true,
      "loc": "security/apparmor/file.c:190",
      "file": "security/apparmor/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_str_perms"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585300656,
      "name": "aa_lookup_fperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct aa_perms * aa_lookup_fperms(struct aa_policydb * file_rules, unsigned int state, struct path_cond * cond)
```

```json
{
  "name": "aa_lookup_fperms",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586039928,
      "name": "aa_lookup_fperms",
      "external": true,
      "loc": "security/apparmor/file.c:313",
      "file": "security/apparmor/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_str_perms"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586039728,
      "name": "aa_lookup_fperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct aa_perms * aa_lookup_fperms(struct aa_policydb * file_rules, unsigned int state, struct path_cond * cond)
```

```json
{
  "name": "aa_lookup_fperms",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586274954,
      "name": "aa_lookup_fperms",
      "external": true,
      "loc": "security/apparmor/file.c:333",
      "file": "security/apparmor/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/file.c:aa_str_perms"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_query_cb",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586274752,
      "name": "aa_lookup_fperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
struct aa_perms * aa_lookup_fperms(struct aa_policydb * file_rules, unsigned int state, struct path_cond * cond)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct aa_perms * aa_lookup_fperms(struct aa_policydb * file_rules, unsigned int state, struct path_cond * cond)
```
</details>
</li>
</ul>
