# Function: <code>freq_qos_apply</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579921760,
      "name": "freq_qos_apply",
      "external": false,
      "loc": "kernel/power/qos.c:718",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_add_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579921760,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579965944,
      "name": "freq_qos_apply",
      "external": true,
      "loc": "kernel/power/qos.c:493",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_remove_request"
      ],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_update_request",
        "kernel/power/qos.c:freq_qos_add_request",
        "drivers/base/power/qos.c:apply_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966736,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579953880,
      "name": "freq_qos_apply",
      "external": true,
      "loc": "kernel/power/qos.c:493",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_remove_request"
      ],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_update_request",
        "kernel/power/qos.c:freq_qos_add_request",
        "drivers/base/power/qos.c:apply_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954656,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579956600,
      "name": "freq_qos_apply",
      "external": true,
      "loc": "kernel/power/qos.c:493",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_remove_request"
      ],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_update_request",
        "kernel/power/qos.c:freq_qos_add_request",
        "drivers/base/power/qos.c:apply_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957376,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580085960,
      "name": "freq_qos_apply",
      "external": true,
      "loc": "kernel/power/qos.c:493",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_remove_request"
      ],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_update_request",
        "kernel/power/qos.c:freq_qos_add_request",
        "drivers/base/power/qos.c:apply_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086736,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580222504,
      "name": "freq_qos_apply",
      "external": true,
      "loc": "kernel/power/qos.c:493",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_remove_request"
      ],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_update_request",
        "kernel/power/qos.c:freq_qos_add_request",
        "drivers/base/power/qos.c:apply_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580223424,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580413320,
      "name": "freq_qos_apply",
      "external": true,
      "loc": "kernel/power/qos.c:493",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_remove_request"
      ],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_update_request",
        "kernel/power/qos.c:freq_qos_add_request",
        "drivers/base/power/qos.c:apply_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580414320,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580482008,
      "name": "freq_qos_apply",
      "external": true,
      "loc": "kernel/power/qos.c:498",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_remove_request"
      ],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_update_request",
        "kernel/power/qos.c:freq_qos_add_request",
        "drivers/base/power/qos.c:apply_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483008,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580541848,
      "name": "freq_qos_apply",
      "external": true,
      "loc": "kernel/power/qos.c:503",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_remove_request"
      ],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_update_request",
        "kernel/power/qos.c:freq_qos_add_request",
        "drivers/base/power/qos.c:apply_constraint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580542848,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491129432,
      "name": "freq_qos_apply",
      "external": false,
      "loc": "kernel/power/qos.c:718",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_add_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491129432,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225127336,
      "name": "freq_qos_apply",
      "external": false,
      "loc": "kernel/power/qos.c:718",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_add_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225127336,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284019696,
      "name": "freq_qos_apply",
      "external": false,
      "loc": "kernel/power/qos.c:718",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_add_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284019696,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271700208,
      "name": "freq_qos_apply",
      "external": false,
      "loc": "kernel/power/qos.c:718",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_add_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271700208,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579893872,
      "name": "freq_qos_apply",
      "external": false,
      "loc": "kernel/power/qos.c:718",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_add_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893872,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579828832,
      "name": "freq_qos_apply",
      "external": false,
      "loc": "kernel/power/qos.c:718",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_add_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828832,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579882032,
      "name": "freq_qos_apply",
      "external": false,
      "loc": "kernel/power/qos.c:718",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_add_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882032,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```

```json
{
  "name": "freq_qos_apply",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579927712,
      "name": "freq_qos_apply",
      "external": false,
      "loc": "kernel/power/qos.c:718",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:freq_qos_remove_request",
        "kernel/power/qos.c:freq_qos_add_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927712,
      "name": "freq_qos_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int freq_qos_apply(struct freq_qos_request * req, enum pm_qos_req_action action, s32 value)
```
</details>
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
