# Function: <code>security_compute_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int security_compute_sid(u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char * objname, u32 * out_sid, bool kern)
```

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582341744,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1568",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_transition_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_change_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582341744,
      "name": "security_compute_sid.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1434
    },
    {
      "addr": 18446744071582343184,
      "name": "security_compute_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int security_compute_sid(u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char * objname, u32 * out_sid, bool kern)
```

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582562192,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1562",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582562192,
      "name": "security_compute_sid.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1426
    },
    {
      "addr": 18446744071582563632,
      "name": "security_compute_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int security_compute_sid(u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char * objname, u32 * out_sid, bool kern)
```

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582655392,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1562",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655392,
      "name": "security_compute_sid.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1426
    },
    {
      "addr": 18446744071582656832,
      "name": "security_compute_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int security_compute_sid(u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char * objname, u32 * out_sid, bool kern)
```

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582750832,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1574",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582750832,
      "name": "security_compute_sid.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1416
    },
    {
      "addr": 18446744071582752256,
      "name": "security_compute_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int security_compute_sid(u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char * objname, u32 * out_sid, bool kern)
```

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582907440,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1577",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582907440,
      "name": "security_compute_sid.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1427
    },
    {
      "addr": 18446744071582908880,
      "name": "security_compute_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583113925,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1630",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583104448,
      "name": "security_compute_sid.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1409
    },
    {
      "addr": 18446744071583124077,
      "name": "security_compute_sid.part.17.cold.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583229925,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1623",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583221216,
      "name": "security_compute_sid.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1744
    },
    {
      "addr": 18446744071583240272,
      "name": "security_compute_sid.part.17.cold.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583416677,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1636",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407488,
      "name": "security_compute_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1589
    },
    {
      "addr": 18446744071583427202,
      "name": "security_compute_sid.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583522581,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1636",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583513376,
      "name": "security_compute_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1589
    },
    {
      "addr": 18446744071583533106,
      "name": "security_compute_sid.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583872709,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1684",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583864240,
      "name": "security_compute_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1711
    },
    {
      "addr": 18446744071583882592,
      "name": "security_compute_sid.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583993557,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1704",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983920,
      "name": "security_compute_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1659
    },
    {
      "addr": 18446744071591366004,
      "name": "security_compute_sid.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584020485,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1716",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584011152,
      "name": "security_compute_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2139
    },
    {
      "addr": 18446744071591309035,
      "name": "security_compute_sid.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584390142,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1724",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584380880,
      "name": "security_compute_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1870
    },
    {
      "addr": 18446744071592299343,
      "name": "security_compute_sid.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
int security_compute_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char * objname, u32 * out_sid, bool kern)
```

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1723",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585003648,
      "name": "security_compute_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1974
    },
    {
      "addr": 18446744071594080825,
      "name": "security_compute_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int security_compute_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char * objname, u32 * out_sid, bool kern)
```

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1717",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585718480,
      "name": "security_compute_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2043
    },
    {
      "addr": 18446744071596096479,
      "name": "security_compute_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int security_compute_sid(u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char * objname, u32 * out_sid, bool kern)
```

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1694",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585953104,
      "name": "security_compute_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1924
    },
    {
      "addr": 18446744071596619728,
      "name": "security_compute_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int security_compute_sid(u32 ssid, u32 tsid, u16 orig_tclass, u16 specified, const char * objname, u32 * out_sid, bool kern)
```

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1705",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586201952,
      "name": "security_compute_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1936
    },
    {
      "addr": 18446744071597525398,
      "name": "security_compute_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495290632,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1636",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495281136,
      "name": "security_compute_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1456
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
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228672224,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1636",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228661624,
      "name": "security_compute_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289274496,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1636",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289261536,
      "name": "security_compute_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2304
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
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274513164,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1636",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274503544,
      "name": "security_compute_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1158
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583491317,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1636",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583482112,
      "name": "security_compute_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1589
    },
    {
      "addr": 18446744071583501842,
      "name": "security_compute_sid.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583428389,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1636",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583419184,
      "name": "security_compute_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1589
    },
    {
      "addr": 18446744071583438898,
      "name": "security_compute_sid.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583475093,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1636",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583465888,
      "name": "security_compute_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1589
    },
    {
      "addr": 18446744071583485618,
      "name": "security_compute_sid.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "security_compute_sid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583571253,
      "name": "security_compute_sid",
      "external": false,
      "loc": "security/selinux/ss/services.c:1636",
      "file": "security/selinux/ss/services.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_change_sid",
        "security/selinux/ss/services.c:security_member_sid",
        "security/selinux/ss/services.c:security_transition_sid_user",
        "security/selinux/ss/services.c:security_transition_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583562080,
      "name": "security_compute_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1588
    },
    {
      "addr": 18446744071583581982,
      "name": "security_compute_sid.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int security_compute_sid(u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char * objname, u32 * out_sid, bool kern)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int security_compute_sid(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char * objname, u32 * out_sid, bool kern)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state * state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, ssid, tsid, orig_tclass, specified, objname, out_sid, kern</code> ➡️ <code>ssid, tsid, orig_tclass, specified, objname, out_sid, kern</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 specified</code> ➡️ <code>u16 specified</code>
</li>
</ul>
</details>
</li>
</ul>
