# Function: <code>rpm_put_suppliers</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584967606,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:288",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__rpm_callback"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585052094,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:288",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__rpm_callback"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585474980,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:289",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__rpm_callback"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void rpm_put_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585720976,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:289",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_drop_link",
        "drivers/base/power/runtime.c:__rpm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585720976,
      "name": "rpm_put_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void rpm_put_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585852864,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:280",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:pm_runtime_drop_link",
        "drivers/base/power/runtime.c:__rpm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585852864,
      "name": "rpm_put_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void rpm_put_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586090208,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:308",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586090208,
      "name": "rpm_put_suppliers",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void rpm_put_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586237760,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:309",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586237760,
      "name": "rpm_put_suppliers",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void rpm_put_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587005056,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:309",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587005056,
      "name": "rpm_put_suppliers",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587094887,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:323",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
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
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586981024,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:323",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
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
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587545442,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:344",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
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
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588879395,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:341",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
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
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590387699,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:338",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
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
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590707432,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:338",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
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
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591069288,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:339",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void rpm_put_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499052608,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:309",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499052608,
      "name": "rpm_put_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void rpm_put_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231611996,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:309",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231611996,
      "name": "rpm_put_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void rpm_put_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292225664,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:309",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292225664,
      "name": "rpm_put_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void rpm_put_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276410710,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:309",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276410710,
      "name": "rpm_put_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void rpm_put_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585997968,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:309",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585997968,
      "name": "rpm_put_suppliers",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void rpm_put_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585847184,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:309",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585847184,
      "name": "rpm_put_suppliers",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void rpm_put_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586187776,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:309",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586187776,
      "name": "rpm_put_suppliers",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void rpm_put_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_put_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586299168,
      "name": "rpm_put_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:309",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586299168,
      "name": "rpm_put_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void rpm_put_suppliers(struct device * dev)
```
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void rpm_put_suppliers(struct device * dev)
```
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
