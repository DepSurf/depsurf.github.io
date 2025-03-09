# Function: <code>rpm_get_suppliers</code>

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
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584967697,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:264",
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
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585052193,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:264",
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
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585475079,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:264",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585724318,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:264",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585856302,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:255",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586092352,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:286",
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
      "addr": 18446744071586092352,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586239904,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:286",
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
      "addr": 18446744071586239904,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587007344,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:286",
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
      "addr": 18446744071587007344,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587092816,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:286",
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
      "addr": 18446744071587092816,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586979040,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:286",
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
      "addr": 18446744071586979040,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587543136,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:286",
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
      "addr": 18446744071587543136,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588876960,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:286",
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
      "addr": 18446744071588876960,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590385184,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:283",
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
      "addr": 18446744071590385184,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590704976,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:283",
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
      "addr": 18446744071590704976,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591066832,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:284",
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
      "addr": 18446744071591066832,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499055136,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:286",
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
      "addr": 18446603336499055136,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231608740,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:286",
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
      "addr": 3231608740,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292228608,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:286",
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
      "addr": 13835058055292228608,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276412836,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:286",
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
      "addr": 18446743936276412836,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586000112,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:286",
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
      "addr": 18446744071586000112,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585849312,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:286",
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
      "addr": 18446744071585849312,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586189920,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:286",
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
      "addr": 18446744071586189920,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int rpm_get_suppliers(struct device * dev)
```

```json
{
  "name": "rpm_get_suppliers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586296064,
      "name": "rpm_get_suppliers",
      "external": false,
      "loc": "drivers/base/power/runtime.c:286",
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
      "addr": 18446744071586296064,
      "name": "rpm_get_suppliers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int rpm_get_suppliers(struct device * dev)
```
</details>
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
