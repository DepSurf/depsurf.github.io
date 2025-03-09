# Function: <code>ima_lsm_copy_rule</code>

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
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583692155,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:260",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
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
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583800139,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:263",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
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
struct ima_rule_entry * ima_lsm_copy_rule(struct ima_rule_entry * entry)
```

```json
{
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:300",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_lsm_update_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188528,
      "name": "ima_lsm_copy_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071584196223,
      "name": "ima_lsm_copy_rule.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry * ima_lsm_copy_rule(struct ima_rule_entry * entry)
```

```json
{
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584307248,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:370",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_lsm_update_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584307248,
      "name": "ima_lsm_copy_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584342620,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:379",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_lsm_update_rules"
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
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584732021,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:391",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_lsm_update_rules"
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
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585408518,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:407",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_lsm_update_rules"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry * ima_lsm_copy_rule(struct ima_rule_entry * entry)
```

```json
{
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586161776,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:431",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_match_rules",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161776,
      "name": "ima_lsm_copy_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
struct ima_rule_entry * ima_lsm_copy_rule(struct ima_rule_entry * entry)
```

```json
{
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586399600,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:431",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_match_rules",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586399600,
      "name": "ima_lsm_copy_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
struct ima_rule_entry * ima_lsm_copy_rule(struct ima_rule_entry * entry)
```

```json
{
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586664576,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:426",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586664576,
      "name": "ima_lsm_copy_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495603452,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:263",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
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
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228964252,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:263",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
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
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289712928,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:263",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
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
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274765818,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:263",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
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
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583768875,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:263",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
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
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583705931,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:263",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
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
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583752635,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:263",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
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
  "name": "ima_lsm_copy_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583853579,
      "name": "ima_lsm_copy_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:263",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
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
struct ima_rule_entry * ima_lsm_copy_rule(struct ima_rule_entry * entry)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct ima_rule_entry * ima_lsm_copy_rule(struct ima_rule_entry * entry)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct ima_rule_entry * ima_lsm_copy_rule(struct ima_rule_entry * entry)
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
