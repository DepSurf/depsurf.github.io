# Function: <code>aa_ns_visible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582599072,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:41",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599072,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582842833,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:41",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582842752,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582938833,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:41",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582938752,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582958081,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:41",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582958000,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583120273,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:41",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583120192,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583325537,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:41",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583325456,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583444097,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:41",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444016,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583629525,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:37",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629456,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583735701,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:37",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583735632,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584119397,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:37",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584119328,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584238341,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:37",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584238272,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584263349,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:37",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584263280,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584649301,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:37",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584649232,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585306789,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:40",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/policy.c:aa_policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585306688,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586045893,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:41",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/policy.c:aa_policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586045776,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586280901,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:41",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/policy.c:aa_policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/notify.c:notification_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586280784,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586537813,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:41",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/policy.c:aa_policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/notify.c:notification_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586537696,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495532644,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:37",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495532464,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228898792,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:37",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228898676,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289614248,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:37",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289614112,
      "name": "aa_ns_visible",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274708774,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:37",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274708642,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583704437,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:37",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583704368,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583641493,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:37",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583641424,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583688213,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:37",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688144,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool aa_ns_visible(struct aa_ns * curr, struct aa_ns * view, bool subns)
```

```json
{
  "name": "aa_ns_visible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583788037,
      "name": "aa_ns_visible",
      "external": true,
      "loc": "security/apparmor/policy_ns.c:37",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_ns_name",
        "security/apparmor/policy_ns.c:aa_ns_name"
      ],
      "caller_func": [
        "security/apparmor/policy.c:policy_view_capable",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/procattr.c:aa_getprocattr",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:aa_label_snxprint",
        "security/apparmor/label.c:label_modename",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583787968,
      "name": "aa_ns_visible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
