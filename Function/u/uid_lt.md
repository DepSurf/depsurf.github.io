# Function: <code>uid_lt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:90",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:90",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:90",
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
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580079458,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:90",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:90",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:90",
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
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580119698,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:90",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:90",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:90",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:90",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580125170,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:90",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:90",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:90",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583011280,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:90",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:90",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011280,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580177649,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583176288,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583176288,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580237457,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583382416,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583382416,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580290097,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583501664,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583501664,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580340885,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583688528,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688528,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580389685,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583796224,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583796224,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579727294,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580467573,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583656511,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_user_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584188512,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589591208,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
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
      "addr": 18446744071584188512,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579706302,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580455829,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583777967,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_user_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584307232,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589602580,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
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
      "addr": 18446744071584307232,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579713438,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580459525,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583802063,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_user_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584341584,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589491236,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
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
      "addr": 18446744071584341584,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579791646,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580626117,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584164607,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_user_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584730400,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590231988,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
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
      "addr": 18446744071584730400,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579898008,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:cred_fscmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580831877,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584763622,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_user_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585406704,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591809759,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
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
      "addr": 18446744071585406704,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580049816,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:cred_fscmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581118661,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585459398,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_user_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585929745,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586160576,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593605775,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
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
      "addr": 18446744071586160576,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580104264,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:cred_fscmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581210413,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585690918,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_user_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586160641,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586398448,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594079183,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
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
      "addr": 18446744071586398448,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580149176,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:83",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:cred_fscmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581316445,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:83",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:83",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585937926,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:83",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_user_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586409889,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:83",
      "file": "security/apparmor/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586663392,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:83",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594873823,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:83",
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
      "addr": 18446744071586663392,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491655992,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495599400,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495599400,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225609268,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228960188,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228960188,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284658000,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289703904,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289703904,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272049458,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274762172,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274762172,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580358485,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583764960,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583764960,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580305653,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583702016,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583702016,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580349733,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583748720,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748720,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
```

```json
{
  "name": "uid_lt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580405013,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "kernel/auditfilter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditfilter.c:audit_uid_comparator"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "fs/quota/kqid.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583849664,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uid_lt",
      "external": false,
      "loc": "include/linux/uidgid.h:91",
      "file": "net/core/fib_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849664,
      "name": "uid_lt",
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
bool uid_lt(kuid_t left, kuid_t right)
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
