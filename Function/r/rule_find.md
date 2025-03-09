# Function: <code>rule_find</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588026942,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:390",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_delrule"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588194478,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:390",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_delrule"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588520727,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:387",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_delrule"
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
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588729303,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:387",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_delrule"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fib_rule * rule_find(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule, bool user_priority)
```

```json
{
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589589824,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:394",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589589824,
      "name": "rule_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
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
struct fib_rule * rule_find(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule, bool user_priority)
```

```json
{
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589601184,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:417",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589601184,
      "name": "rule_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fib_rule * rule_find(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule, bool user_priority)
```

```json
{
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589489792,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:417",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589489792,
      "name": "rule_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fib_rule * rule_find(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule, bool user_priority)
```

```json
{
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590230448,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:417",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590230448,
      "name": "rule_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
struct fib_rule * rule_find(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule, bool user_priority)
```

```json
{
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591808352,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:417",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591808352,
      "name": "rule_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fib_rule * rule_find(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule, bool user_priority)
```

```json
{
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593604256,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:417",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593604256,
      "name": "rule_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
struct fib_rule * rule_find(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule, bool user_priority)
```

```json
{
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594077664,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:417",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594077664,
      "name": "rule_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
struct fib_rule * rule_find(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule, bool user_priority)
```

```json
{
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594872304,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:416",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594872304,
      "name": "rule_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502294768,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:387",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_delrule"
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
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235033812,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:387",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_delrule"
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
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295798592,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:387",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_delrule"
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
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278524166,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:387",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_delrule"
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
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588336039,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:387",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_delrule"
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
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588048743,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:387",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_delrule"
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
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588667863,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:387",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_delrule"
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
  "name": "rule_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588807719,
      "name": "rule_find",
      "external": false,
      "loc": "net/core/fib_rules.c:387",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_delrule"
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
struct fib_rule * rule_find(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule, bool user_priority)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
