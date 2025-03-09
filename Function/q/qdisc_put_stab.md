# Function: <code>qdisc_put_stab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586458096,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:509",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:tc_modify_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586458096,
      "name": "qdisc_put_stab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586904224,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:507",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586904224,
      "name": "qdisc_put_stab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587098512,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:512",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587098512,
      "name": "qdisc_put_stab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587238969,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:512",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587229504,
      "name": "qdisc_put_stab.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071587229568,
      "name": "qdisc_put_stab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587754354,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:507",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587744720,
      "name": "qdisc_put_stab.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071587744784,
      "name": "qdisc_put_stab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588093247,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:519",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588082752,
      "name": "qdisc_put_stab.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071588082816,
      "name": "qdisc_put_stab",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588270275,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:534",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588260368,
      "name": "qdisc_put_stab.part.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071588260432,
      "name": "qdisc_put_stab",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588661868,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:526",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588651712,
      "name": "qdisc_put_stab.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071588651776,
      "name": "qdisc_put_stab",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588884412,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:526",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588874080,
      "name": "qdisc_put_stab.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071588874144,
      "name": "qdisc_put_stab",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589763959,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:528",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_change",
        "net/sched/sch_api.c:qdisc_change",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589756976,
      "name": "qdisc_put_stab",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589797255,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:530",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_change",
        "net/sched/sch_api.c:qdisc_change",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589791552,
      "name": "qdisc_put_stab",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589708047,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:530",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589695568,
      "name": "qdisc_put_stab",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590466239,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:536",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590453744,
      "name": "qdisc_put_stab",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592069401,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:537",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592055984,
      "name": "qdisc_put_stab",
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
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593889245,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:539",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593875264,
      "name": "qdisc_put_stab",
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
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594263842,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:540",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:__qdisc_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594250192,
      "name": "qdisc_put_stab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595061746,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:540",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:__qdisc_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595047536,
      "name": "qdisc_put_stab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502473604,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:526",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502462280,
      "name": "qdisc_put_stab.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446603336502462360,
      "name": "qdisc_put_stab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235188364,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:526",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235178064,
      "name": "qdisc_put_stab.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 3235178128,
      "name": "qdisc_put_stab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296031216,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:526",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296017632,
      "name": "qdisc_put_stab.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 13835058055296017760,
      "name": "qdisc_put_stab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278655448,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:526",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278646704,
      "name": "qdisc_put_stab.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446743936278646768,
      "name": "qdisc_put_stab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588490796,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:526",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588480464,
      "name": "qdisc_put_stab.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071588480528,
      "name": "qdisc_put_stab",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588202796,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:526",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588192464,
      "name": "qdisc_put_stab.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071588192528,
      "name": "qdisc_put_stab",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588822972,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:526",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588812640,
      "name": "qdisc_put_stab.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071588812704,
      "name": "qdisc_put_stab",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void qdisc_put_stab(struct qdisc_size_table * tab)
```

```json
{
  "name": "qdisc_put_stab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588963580,
      "name": "qdisc_put_stab",
      "external": true,
      "loc": "net/sched/sch_api.c:526",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588953312,
      "name": "qdisc_put_stab.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071588953376,
      "name": "qdisc_put_stab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
