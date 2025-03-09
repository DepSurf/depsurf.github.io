# Function: <code>audit_get_watch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580064640,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:111",
      "file": "kernel/audit_watch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_update_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch"
      ],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064640,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580100010,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:112",
      "file": "kernel/audit_watch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097840,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580140302,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:112",
      "file": "kernel/audit_watch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138128,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580146088,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:113",
      "file": "kernel/audit_watch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143936,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580196608,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:113",
      "file": "kernel/audit_watch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580196608,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580256512,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:113",
      "file": "kernel/audit_watch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256512,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309680,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:113",
      "file": "kernel/audit_watch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309680,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580361776,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361776,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580410592,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580410592,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580491762,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_to_parent",
        "kernel/audit_watch.c:audit_add_to_parent",
        "kernel/audit_watch.c:audit_update_watch"
      ],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580489136,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580479874,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_to_parent",
        "kernel/audit_watch.c:audit_add_to_parent",
        "kernel/audit_watch.c:audit_update_watch"
      ],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477280,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580483507,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580481248,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580651155,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580648896,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580860104,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857520,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581147944,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145232,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581241272,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581238560,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581347400,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344832,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491678120,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491676016,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225632284,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225630316,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284688392,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284685744,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272067998,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272066234,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580379392,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379392,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580326560,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580326560,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580370640,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580370640,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void audit_get_watch(struct audit_watch * watch)
```

```json
{
  "name": "audit_get_watch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580426160,
      "name": "audit_get_watch",
      "external": true,
      "loc": "kernel/audit_watch.c:100",
      "file": "kernel/audit_watch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditfilter.c:audit_dupe_rule",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_add_watch",
        "kernel/audit_watch.c:audit_update_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580426160,
      "name": "audit_get_watch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
