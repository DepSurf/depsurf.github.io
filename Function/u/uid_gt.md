# Function: <code>uid_gt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:70",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:70",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580079467,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:70",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:70",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580119707,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:70",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:70",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:70",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580125179,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:70",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:70",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583011264,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:70",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:70",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011264,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580177657,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583176272,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583176272,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580237465,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583382400,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583382400,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580290113,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583501648,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583501648,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580340937,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583688512,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688512,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580389737,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583796208,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583796208,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580467625,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584188496,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589591213,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_rules_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188496,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580455881,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584307216,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589602585,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_rules_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584307216,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580459574,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584341568,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589491241,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_rules_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584341568,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580626166,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584730384,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590231993,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_rules_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584730384,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580831956,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585406672,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591809764,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_rules_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585406672,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581118740,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586160512,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593605780,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_rules_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586160512,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581210375,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586398384,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594079188,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_rules_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586398384,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:63",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581316407,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:63",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:63",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:63",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586663328,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:63",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594873828,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:63",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/fib_rules.c:fib_rules_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586663328,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491656084,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495599384,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495599384,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225609284,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228960160,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228960160,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284658032,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289703872,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289703872,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272049476,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274762152,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274762152,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580358537,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583764944,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583764944,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580305705,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583702000,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583702000,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580349785,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583748704,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748704,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_gt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580405065,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583849648,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_gt",
      "external": false,
      "loc": "include/linux/uidgid.h:71",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849648,
      "name": "uid_gt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
bool uid_gt(kuid_t left, kuid_t right)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
