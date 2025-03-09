# Function: <code>audit_data_to_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580043097,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:419",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_rule_change"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580076118,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:419",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_rule_change"
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
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580116326,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:420",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_rule_change"
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
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580121174,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:420",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_rule_change"
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
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580173654,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:439",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_rule_change"
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
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580233510,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:439",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_rule_change"
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
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580285910,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:437",
      "file": "kernel/auditfilter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_rule_change"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:441",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580335424,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2263
    },
    {
      "addr": 18446744071580342510,
      "name": "audit_data_to_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:441",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580384288,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2164
    },
    {
      "addr": 18446744071580391310,
      "name": "audit_data_to_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:441",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580463248,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1776
    },
    {
      "addr": 18446744071580468830,
      "name": "audit_data_to_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:441",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451552,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1742
    },
    {
      "addr": 18446744071591315773,
      "name": "audit_data_to_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:441",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580455520,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1739
    },
    {
      "addr": 18446744071591258014,
      "name": "audit_data_to_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:441",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580621552,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2027
    },
    {
      "addr": 18446744071592162566,
      "name": "audit_data_to_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:449",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580827088,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2036
    },
    {
      "addr": 18446744071593935675,
      "name": "audit_data_to_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581113680,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:449",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113680,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2088
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
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581205264,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:449",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581205264,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2116
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
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581311360,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:449",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581311360,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2047
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491650528,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:441",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491650528,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2060
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
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225602552,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:441",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225602552,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3224
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
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284649696,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:441",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284649696,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3852
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
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272045270,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:441",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272045270,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1688
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:441",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580353088,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2164
    },
    {
      "addr": 18446744071580360110,
      "name": "audit_data_to_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:441",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580300256,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2164
    },
    {
      "addr": 18446744071580307278,
      "name": "audit_data_to_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:441",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580344336,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2164
    },
    {
      "addr": 18446744071580351358,
      "name": "audit_data_to_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```

```json
{
  "name": "audit_data_to_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_data_to_entry",
      "external": false,
      "loc": "kernel/auditfilter.c:441",
      "file": "kernel/auditfilter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_rule_change",
        "kernel/auditfilter.c:audit_rule_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580399616,
      "name": "audit_data_to_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2164
    },
    {
      "addr": 18446744071580406654,
      "name": "audit_data_to_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct audit_entry * audit_data_to_entry(struct audit_rule_data * data, size_t datasz)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
