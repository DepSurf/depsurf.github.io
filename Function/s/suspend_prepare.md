# Function: <code>suspend_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int suspend_prepare(suspend_state_t state)
```

```json
{
  "name": "suspend_prepare",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579691994,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:267",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583924304,
      "name": "suspend_prepare",
      "external": false,
      "loc": "drivers/regulator/core.c:809",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_suspend_prepare",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583924304,
      "name": "suspend_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int suspend_prepare(suspend_state_t state)
```

```json
{
  "name": "suspend_prepare",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579711131,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:267",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584255888,
      "name": "suspend_prepare",
      "external": false,
      "loc": "drivers/regulator/core.c:784",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_suspend_prepare",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584255888,
      "name": "suspend_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int suspend_prepare(suspend_state_t state)
```

```json
{
  "name": "suspend_prepare",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579738667,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:290",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584437312,
      "name": "suspend_prepare",
      "external": false,
      "loc": "drivers/regulator/core.c:785",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_suspend_prepare",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584437312,
      "name": "suspend_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int suspend_prepare(suspend_state_t state)
```

```json
{
  "name": "suspend_prepare",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579734806,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:315",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:pm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584520656,
      "name": "suspend_prepare",
      "external": false,
      "loc": "drivers/regulator/core.c:785",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_suspend_prepare",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584520656,
      "name": "suspend_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int suspend_prepare(suspend_state_t state)
```

```json
{
  "name": "suspend_prepare",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579767888,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:342",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584930736,
      "name": "suspend_prepare",
      "external": false,
      "loc": "drivers/regulator/core.c:785",
      "file": "drivers/regulator/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/regulator/core.c:_regulator_suspend_prepare",
        "drivers/regulator/core.c:set_machine_constraints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930736,
      "name": "suspend_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579802300,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:343",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579848924,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:349",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579882979,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:353",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579933231,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:343",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int suspend_prepare(suspend_state_t state)
```

```json
{
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579976712,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:343",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579976712,
      "name": "suspend_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
int suspend_prepare(suspend_state_t state)
```

```json
{
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591292112,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:345",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591292112,
      "name": "suspend_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591235591,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:345",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:enter_state"
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
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580095835,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:343",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:enter_state"
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
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580233594,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:344",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:enter_state"
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
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580427113,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:351",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:enter_state"
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
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580496445,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:351",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:enter_state"
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
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580556333,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:351",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:enter_state"
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
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491143636,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:343",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225140476,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:343",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284037364,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:343",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579840284,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:343",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579893503,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:343",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "suspend_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579939487,
      "name": "suspend_prepare",
      "external": false,
      "loc": "kernel/power/suspend.c:343",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
int suspend_prepare(suspend_state_t state)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int suspend_prepare(suspend_state_t state)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int suspend_prepare(suspend_state_t state)
```
</details>
</li>
</ul>
