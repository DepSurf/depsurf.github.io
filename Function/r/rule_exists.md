# Function: <code>rule_exists</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586867234,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:272",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_newrule"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587058412,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:310",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_newrule"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587187022,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:324",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_newrule"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587692864,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:387",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_newrule"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588026337,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:659",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_newrule"
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
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588193775,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:659",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_newrule"
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
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588520057,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:656",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_newrule"
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
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588728633,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:656",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_newrule"
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
int rule_exists(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule)
```

```json
{
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589590416,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:663",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_newrule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589590416,
      "name": "rule_exists",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int rule_exists(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule)
```

```json
{
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589601776,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:686",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_newrule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589601776,
      "name": "rule_exists",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int rule_exists(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule)
```

```json
{
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589490384,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:686",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_newrule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589490384,
      "name": "rule_exists",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int rule_exists(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule)
```

```json
{
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590231040,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:686",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_newrule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590231040,
      "name": "rule_exists",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int rule_exists(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule)
```

```json
{
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591808944,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:686",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_newrule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591808944,
      "name": "rule_exists",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
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
int rule_exists(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule)
```

```json
{
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593604864,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:686",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_newrule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593604864,
      "name": "rule_exists",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
int rule_exists(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule)
```

```json
{
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594078272,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:686",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_newrule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594078272,
      "name": "rule_exists",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
int rule_exists(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule)
```

```json
{
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594872912,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:684",
      "file": "net/core/fib_rules.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_newrule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594872912,
      "name": "rule_exists",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502294248,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:656",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_newrule"
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
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235032940,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:656",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_newrule"
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
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295797288,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:656",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_newrule"
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
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278523436,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:656",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_newrule"
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
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588335369,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:656",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_newrule"
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
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588048073,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:656",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_newrule"
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
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588667193,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:656",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_newrule"
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
  "name": "rule_exists",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588807049,
      "name": "rule_exists",
      "external": false,
      "loc": "net/core/fib_rules.c:656",
      "file": "net/core/fib_rules.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_nl_newrule"
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
int rule_exists(struct fib_rules_ops * ops, struct fib_rule_hdr * frh, struct nlattr * * tb, struct fib_rule * rule)
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
