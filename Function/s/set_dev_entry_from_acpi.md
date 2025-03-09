# Function: <code>set_dev_entry_from_acpi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void set_dev_entry_from_acpi(struct amd_iommu * iommu, u16 devid, u32 flags, u32 ext_flags)
```

```json
{
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595264636,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:667",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595264636,
      "name": "set_dev_entry_from_acpi",
      "section": ".init.text",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595447161,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:721",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595447161,
      "name": "set_dev_entry_from_acpi.constprop.22",
      "section": ".init.text",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595701841,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:823",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595701841,
      "name": "set_dev_entry_from_acpi.constprop.14",
      "section": ".init.text",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596624458,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:832",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596624458,
      "name": "set_dev_entry_from_acpi.constprop.12",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602954506,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:967",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602954506,
      "name": "set_dev_entry_from_acpi.constprop.15",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 214
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
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071603127306,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:967",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603127306,
      "name": "set_dev_entry_from_acpi.constprop.14",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 150
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
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604930359,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:994",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604930359,
      "name": "set_dev_entry_from_acpi.constprop.16",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 150
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
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605039375,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:982",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605039375,
      "name": "set_dev_entry_from_acpi.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 150
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
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605075864,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:983",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605075864,
      "name": "set_dev_entry_from_acpi.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 150
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
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609366308,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:983",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609366308,
      "name": "set_dev_entry_from_acpi.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 217
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
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612437748,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1046",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612437748,
      "name": "set_dev_entry_from_acpi.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 217
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
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614578540,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1042",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614578540,
      "name": "set_dev_entry_from_acpi.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 214
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
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615533742,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1053",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615533742,
      "name": "set_dev_entry_from_acpi.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617339039,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1059",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617339039,
      "name": "set_dev_entry_from_acpi.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071628071040,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1157",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628071040,
      "name": "set_dev_entry_from_acpi.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619837104,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1192",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619837104,
      "name": "set_dev_entry_from_acpi.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622145904,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1207",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi",
        "drivers/iommu/amd/init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622145904,
      "name": "set_dev_entry_from_acpi.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 362
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604975487,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:983",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604975487,
      "name": "set_dev_entry_from_acpi.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 150
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
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604939788,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:983",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604939788,
      "name": "set_dev_entry_from_acpi.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 150
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
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605056187,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:983",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605056187,
      "name": "set_dev_entry_from_acpi.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 150
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
  "name": "set_dev_entry_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605080058,
      "name": "set_dev_entry_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:983",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi",
        "drivers/iommu/amd_iommu_init.c:init_iommu_from_acpi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605080058,
      "name": "set_dev_entry_from_acpi.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 150
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void set_dev_entry_from_acpi(struct amd_iommu * iommu, u16 devid, u32 flags, u32 ext_flags)
```
</details>
</li>
</ul>
