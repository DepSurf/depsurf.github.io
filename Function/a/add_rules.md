# Function: <code>add_rules</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```

```json
{
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583506745,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:484",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583506745,
      "name": "add_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```

```json
{
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583694360,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:567",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694360,
      "name": "add_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```

```json
{
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583802312,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:574",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583802312,
      "name": "add_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584196317,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:680",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584196317,
      "name": "add_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591370052,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:726",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591370052,
      "name": "add_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591312740,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:760",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591312740,
      "name": "add_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592308743,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:813",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592308743,
      "name": "add_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```

```json
{
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594091037,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:847",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594091037,
      "name": "add_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```

```json
{
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627959621,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:894",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161408,
      "name": "add_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```

```json
{
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586399232,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:896",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586399232,
      "name": "add_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```

```json
{
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586664208,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:889",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586664208,
      "name": "add_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495605728,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:574",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495605728,
      "name": "add_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228966572,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:574",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228966572,
      "name": "add_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```

```json
{
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289719080,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:574",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289719080,
      "name": "add_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274767886,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:574",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274767886,
      "name": "add_rules.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```

```json
{
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583771048,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:574",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583771048,
      "name": "add_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```

```json
{
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583708104,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:574",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708104,
      "name": "add_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```

```json
{
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583754808,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:574",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583754808,
      "name": "add_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```

```json
{
  "name": "add_rules",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583855780,
      "name": "add_rules",
      "external": false,
      "loc": "security/integrity/ima/ima_policy.c:574",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy",
        "security/integrity/ima/ima_policy.c:ima_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583855780,
      "name": "add_rules",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void add_rules(struct ima_rule_entry * entries, int count, enum policy_rule_list policy_rule)
```
</details>
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
