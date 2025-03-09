# Function: <code>ima_lsm_free_rule</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry * entry)
```

```json
{
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583688544,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:249",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688544,
      "name": "ima_lsm_free_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry * entry)
```

```json
{
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583796240,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:252",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583796240,
      "name": "ima_lsm_free_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584196034,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:272",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_delete_rules",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_lsm_update_rules",
        "security/integrity/ima/ima_policy.c:ima_lsm_copy_rule"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584315016,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:342",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_delete_rules",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584349560,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:351",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_delete_rules",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
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
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584732369,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:363",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_delete_rules",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
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
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585408839,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:380",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_delete_rules",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:404",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_delete_rules",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule"
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
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:404",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_delete_rules",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule"
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
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:399",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_delete_rules",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry * entry)
```

```json
{
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495599416,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:252",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495599416,
      "name": "ima_lsm_free_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry * entry)
```

```json
{
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228960216,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:252",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228960216,
      "name": "ima_lsm_free_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry * entry)
```

```json
{
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289703936,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:252",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289703936,
      "name": "ima_lsm_free_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry * entry)
```

```json
{
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274762192,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:252",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274762192,
      "name": "ima_lsm_free_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry * entry)
```

```json
{
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583764976,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:252",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583764976,
      "name": "ima_lsm_free_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry * entry)
```

```json
{
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583702032,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:252",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583702032,
      "name": "ima_lsm_free_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry * entry)
```

```json
{
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583748736,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:252",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748736,
      "name": "ima_lsm_free_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry * entry)
```

```json
{
  "name": "ima_lsm_free_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583849680,
      "name": "ima_lsm_free_rule",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:252",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849680,
      "name": "ima_lsm_free_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry * entry)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void ima_lsm_free_rule(struct ima_rule_entry * entry)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
