# Function: <code>security_audit_rule_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule, struct audit_context * actx)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582251968,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:1543",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter_user",
        "kernel/auditsc.c:audit_filter_rules",
        "kernel/auditsc.c:audit_filter_rules",
        "kernel/auditsc.c:audit_filter_rules",
        "kernel/auditsc.c:audit_filter_rules",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582251968,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule, struct audit_context * actx)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582470624,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:1573",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470624,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule, struct audit_context * actx)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582563088,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:1594",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582563088,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule, struct audit_context * actx)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582652320,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:2576",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582652320,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule, struct audit_context * actx)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582806864,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:2440",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582806864,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule, struct audit_context * actx)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583001120,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:1753",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583001120,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule, struct audit_context * actx)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583114448,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:2513",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583114448,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301264,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:2532",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301264,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583405856,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:2571",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583405856,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int security_audit_rule_match(struct lsmblob * blob, u32 field, u32 op, void * * lsmrule)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583746048,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:2925",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583746048,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int security_audit_rule_match(struct lsmblob * blob, u32 field, u32 op, void * * lsmrule)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583866368,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:2943",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583866368,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int security_audit_rule_match(struct lsmblob * blob, u32 field, u32 op, void * * lsmrule)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583892528,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:3006",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583892528,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int security_audit_rule_match(struct lsmblob * blob, u32 field, u32 op, void * * lsmrule)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584256352,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:3014",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584256352,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int security_audit_rule_match(struct lsmblob * blob, u32 field, u32 op, struct audit_lsm_rules * lsmrules)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584867872,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:3050",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584867872,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int security_audit_rule_match(struct lsmblob * blob, u32 field, u32 op, struct audit_lsm_rules * lsmrules)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585572960,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:3030",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585572960,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int security_audit_rule_match(struct lsmblob * blob, u32 field, u32 op, struct audit_lsm_rules * lsmrules)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585804064,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:5419",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585804064,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int security_audit_rule_match(struct lsmblob * blob, u32 field, u32 op, void * lsmrule)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586052624,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:5593",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586052624,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495159520,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:2571",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495159520,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228546892,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:2571",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228546892,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289093856,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:2571",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289093856,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274404708,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:2571",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274404708,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583374592,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:2571",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583374592,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583311696,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:2571",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583311696,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583358368,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:2571",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583358368,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int security_audit_rule_match(u32 secid, u32 field, u32 op, void * lsmrule)
```

```json
{
  "name": "security_audit_rule_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583453552,
      "name": "security_audit_rule_match",
      "external": true,
      "loc": "security/security.c:2571",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_filter",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583453552,
      "name": "security_audit_rule_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct audit_context * actx</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmblob * blob</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 secid</code>
</li>
<li>
<b>Param type changed. </b>
<code>void * lsmrule</code> ➡️ <code>void * * lsmrule</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct audit_lsm_rules * lsmrules</code>
</li>
<li>
<b>Param removed. </b>
<code>void * * lsmrule</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * lsmrule</code>
</li>
<li>
<b>Param removed. </b>
<code>struct audit_lsm_rules * lsmrules</code>
</li>
</ul>
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
