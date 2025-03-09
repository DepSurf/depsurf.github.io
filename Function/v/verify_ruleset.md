# Function: <code>verify_ruleset</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:84",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:84",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int verify_ruleset(struct setuid_ruleset * pol)
```

```json
{
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:84",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:handle_policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584163808,
      "name": "verify_ruleset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071584164870,
      "name": "verify_ruleset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int verify_ruleset(struct setid_ruleset * pol)
```

```json
{
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:98",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:handle_policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584283152,
      "name": "verify_ruleset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071591368873,
      "name": "verify_ruleset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:98",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:handle_policy_update"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:98",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:handle_policy_update"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:98",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:handle_policy_update"
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
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:98",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:handle_policy_update"
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
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:98",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:handle_policy_update"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:98",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:handle_policy_update"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:84",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:84",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:84",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274742992,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:84",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:84",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:84",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:84",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "verify_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "verify_ruleset",
      "external": false,
      "loc": "security/safesetid/securityfs.c:84",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int verify_ruleset(struct setuid_ruleset * pol)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct setuid_ruleset * pol</code> ➡️ <code>struct setid_ruleset * pol</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int verify_ruleset(struct setid_ruleset * pol)
```
</details>
</li>
</ul>
