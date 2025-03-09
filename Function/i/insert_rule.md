# Function: <code>insert_rule</code>

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
  "name": "insert_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583667889,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:79",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write",
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
  "name": "insert_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583774161,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:79",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "insert_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584164475,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:79",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:verify_ruleset"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void insert_rule(struct setid_ruleset * pol, struct setid_rule * rule)
```

```json
{
  "name": "insert_rule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584283088,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:88",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:verify_ruleset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584283088,
      "name": "insert_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void insert_rule(struct setid_ruleset * pol, struct setid_rule * rule)
```

```json
{
  "name": "insert_rule",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584307936,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:88",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update"
      ]
    },
    {
      "addr": 18446744071584316384,
      "name": "insert_rule",
      "external": false,
      "loc": "security/landlock/ruleset.c:144",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/ruleset.c:inherit_ruleset",
        "security/landlock/ruleset.c:merge_ruleset",
        "security/landlock/ruleset.c:landlock_insert_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584307936,
      "name": "insert_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584316384,
      "name": "insert_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void insert_rule(struct setid_ruleset * pol, struct setid_rule * rule)
```

```json
{
  "name": "insert_rule",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584694496,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:88",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update"
      ]
    },
    {
      "addr": 18446744071584703456,
      "name": "insert_rule",
      "external": false,
      "loc": "security/landlock/ruleset.c:144",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/ruleset.c:landlock_merge_ruleset",
        "security/landlock/ruleset.c:merge_ruleset",
        "security/landlock/ruleset.c:landlock_insert_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584694496,
      "name": "insert_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584703456,
      "name": "insert_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void insert_rule(struct setid_ruleset * pol, struct setid_rule * rule)
```

```json
{
  "name": "insert_rule",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585358112,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:88",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update"
      ]
    },
    {
      "addr": 18446744071585367904,
      "name": "insert_rule",
      "external": false,
      "loc": "security/landlock/ruleset.c:145",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/ruleset.c:inherit_ruleset",
        "security/landlock/ruleset.c:merge_ruleset",
        "security/landlock/ruleset.c:landlock_insert_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585358112,
      "name": "insert_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071585367904,
      "name": "insert_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void insert_rule(struct setid_ruleset * pol, struct setid_rule * rule)
```

```json
{
  "name": "insert_rule",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586107664,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:88",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update"
      ]
    },
    {
      "addr": 18446744071586118672,
      "name": "insert_rule",
      "external": false,
      "loc": "security/landlock/ruleset.c:145",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/ruleset.c:inherit_ruleset",
        "security/landlock/ruleset.c:merge_ruleset",
        "security/landlock/ruleset.c:landlock_insert_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586107664,
      "name": "insert_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071586118672,
      "name": "insert_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void insert_rule(struct setid_ruleset * pol, struct setid_rule * rule)
```

```json
{
  "name": "insert_rule",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586346288,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:88",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update"
      ]
    },
    {
      "addr": 18446744071586357552,
      "name": "insert_rule",
      "external": false,
      "loc": "security/landlock/ruleset.c:145",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/ruleset.c:landlock_merge_ruleset",
        "security/landlock/ruleset.c:inherit_ruleset",
        "security/landlock/ruleset.c:landlock_insert_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586346288,
      "name": "insert_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071586357552,
      "name": "insert_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void insert_rule(struct setid_ruleset * pol, struct setid_rule * rule)
```

```json
{
  "name": "insert_rule",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586613200,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:88",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/safesetid/securityfs.c:handle_policy_update"
      ]
    },
    {
      "addr": 18446744071586624816,
      "name": "insert_rule",
      "external": false,
      "loc": "security/landlock/ruleset.c:199",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/ruleset.c:inherit_tree",
        "security/landlock/ruleset.c:merge_tree",
        "security/landlock/ruleset.c:landlock_insert_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586613200,
      "name": "insert_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071586624816,
      "name": "insert_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
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
  "name": "insert_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495575720,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:79",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write",
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
  "name": "insert_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228937812,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:79",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write",
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
  "name": "insert_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289671692,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:79",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write",
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
  "name": "insert_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274742654,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:79",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write",
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
  "name": "insert_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583742897,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:79",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write",
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
  "name": "insert_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583679953,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:79",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write",
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
  "name": "insert_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583726673,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:79",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write",
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
  "name": "insert_rule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583827425,
      "name": "insert_rule",
      "external": false,
      "loc": "security/safesetid/securityfs.c:79",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write",
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void insert_rule(struct setid_ruleset * pol, struct setid_rule * rule)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
