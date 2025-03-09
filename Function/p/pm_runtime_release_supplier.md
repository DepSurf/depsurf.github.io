# Function: <code>pm_runtime_release_supplier</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void pm_runtime_release_supplier(struct device_link * link, bool check_idle)
```

```json
{
  "name": "pm_runtime_release_supplier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587539440,
      "name": "pm_runtime_release_supplier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:317",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_link_release_fn",
        "drivers/base/power/runtime.c:pm_runtime_drop_link",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__rpm_callback",
        "drivers/base/power/runtime.c:__rpm_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587539440,
      "name": "pm_runtime_release_supplier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void pm_runtime_release_supplier(struct device_link * link)
```

```json
{
  "name": "pm_runtime_release_supplier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588874048,
      "name": "pm_runtime_release_supplier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:314",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__rpm_put_suppliers"
      ],
      "caller_func": [
        "drivers/base/core.c:device_link_release_fn",
        "drivers/base/power/runtime.c:pm_runtime_drop_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588880928,
      "name": "pm_runtime_release_supplier",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pm_runtime_release_supplier(struct device_link * link)
```

```json
{
  "name": "pm_runtime_release_supplier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590382176,
      "name": "pm_runtime_release_supplier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:311",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__rpm_put_suppliers"
      ],
      "caller_func": [
        "drivers/base/core.c:device_link_release_fn",
        "drivers/base/power/runtime.c:pm_runtime_drop_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590389328,
      "name": "pm_runtime_release_supplier",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pm_runtime_release_supplier(struct device_link * link)
```

```json
{
  "name": "pm_runtime_release_supplier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590702080,
      "name": "pm_runtime_release_supplier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:311",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__rpm_put_suppliers"
      ],
      "caller_func": [
        "drivers/base/core.c:device_link_release_fn",
        "drivers/base/power/runtime.c:pm_runtime_drop_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590708992,
      "name": "pm_runtime_release_supplier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void pm_runtime_release_supplier(struct device_link * link)
```

```json
{
  "name": "pm_runtime_release_supplier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591063936,
      "name": "pm_runtime_release_supplier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:312",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:__rpm_put_suppliers"
      ],
      "caller_func": [
        "drivers/base/core.c:device_link_release_fn",
        "drivers/base/power/runtime.c:pm_runtime_drop_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591070848,
      "name": "pm_runtime_release_supplier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void pm_runtime_release_supplier(struct device_link * link, bool check_idle)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool check_idle</code>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
