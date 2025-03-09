# Function: <code>mls_context_cpy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582312854,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:40",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582345872,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:40",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582367668,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:40",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582534022,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:40",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582579440,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:40",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582590888,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:40",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582626838,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:40",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582672656,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:40",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582684120,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:40",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int mls_context_cpy(struct context * dst, struct context * src)
```

```json
{
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582718782,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:40",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582765406,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:40",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582776943,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:40",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ],
      "caller_func": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582772640,
      "name": "mls_context_cpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int mls_context_cpy(struct context * dst, struct context * src)
```

```json
{
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582874750,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582921422,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582933007,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ],
      "caller_func": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582928704,
      "name": "mls_context_cpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583072941,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583120022,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583132612,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
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
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583189177,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583236060,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583248564,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583376463,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583422820,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583435411,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583482362,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583528724,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583541315,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583827816,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583877994,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583890982,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583949288,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583998879,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584011088,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583976287,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584026422,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584039150,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584342443,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584396578,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584410270,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584963516,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585022750,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585037290,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585676822,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585740339,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585755866,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585907062,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585971008,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585986651,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586155686,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586220032,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586233979,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495247548,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495297640,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495312448,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228629240,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 3228678496,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 3228690860,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289217780,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289284652,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289301868,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274472712,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274518330,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274529284,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583451098,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583497460,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583510051,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583388170,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583434516,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583447107,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583434874,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481236,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583493827,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583531130,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583577412,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583590195,
      "name": "mls_context_cpy",
      "external": false,
      "loc": "security/selinux/ss/context.h:41",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int mls_context_cpy(struct context * dst, struct context * src)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int mls_context_cpy(struct context * dst, struct context * src)
```
</details>
</li>
</ul>
