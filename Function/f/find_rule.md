# Function: <code>find_rule</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585372285,
      "name": "find_rule",
      "external": false,
      "loc": "security/landlock/fs.c:193",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:collect_domain_accesses",
        "security/landlock/fs.c:check_access_path_dual",
        "security/landlock/fs.c:check_access_path_dual",
        "security/landlock/fs.c:check_access_path_dual"
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
  "name": "find_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586123578,
      "name": "find_rule",
      "external": false,
      "loc": "security/landlock/fs.c:206",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:collect_domain_accesses",
        "security/landlock/fs.c:is_access_to_paths_allowed",
        "security/landlock/fs.c:is_access_to_paths_allowed",
        "security/landlock/fs.c:is_access_to_paths_allowed"
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
  "name": "find_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586362272,
      "name": "find_rule",
      "external": false,
      "loc": "security/landlock/fs.c:206",
      "file": "security/landlock/fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/fs.c:collect_domain_accesses",
        "security/landlock/fs.c:is_access_to_paths_allowed",
        "security/landlock/fs.c:is_access_to_paths_allowed",
        "security/landlock/fs.c:is_access_to_paths_allowed"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
const struct landlock_rule * find_rule(const const struct landlock_ruleset * domain, const const struct dentry * dentry)
```

```json
{
  "name": "find_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586629824,
      "name": "find_rule",
      "external": false,
      "loc": "security/landlock/fs.c:197",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:collect_domain_accesses",
        "security/landlock/fs.c:is_access_to_paths_allowed",
        "security/landlock/fs.c:is_access_to_paths_allowed",
        "security/landlock/fs.c:is_access_to_paths_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586629824,
      "name": "find_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
const struct landlock_rule * find_rule(const const struct landlock_ruleset * domain, const const struct dentry * dentry)
```
</details>
</li>
</ul>
