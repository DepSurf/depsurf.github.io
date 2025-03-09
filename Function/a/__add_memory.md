# Function: <code>__add_memory</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589470336,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1164",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589470336,
      "name": "__add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int __add_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589928672,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1147",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589928672,
      "name": "__add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int __add_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590155888,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1122",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590155888,
      "name": "__add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int __add_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591173616,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1108",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591173616,
      "name": "__add_memory",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size, mhp_t mhp_flags)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591669424,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1119",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591669424,
      "name": "__add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int __add_memory(int nid, u64 start, u64 size, mhp_t mhp_flags)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591613680,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1300",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591613680,
      "name": "__add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int __add_memory(int nid, u64 start, u64 size, mhp_t mhp_flags)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592787392,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1466",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592787392,
      "name": "__add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int __add_memory(int nid, u64 start, u64 size, mhp_t mhp_flags)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594686064,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1434",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594686064,
      "name": "__add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int __add_memory(int nid, u64 start, u64 size, mhp_t mhp_flags)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596422640,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1432",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596422640,
      "name": "__add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int __add_memory(int nid, u64 start, u64 size, mhp_t mhp_flags)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596962768,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1407",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596962768,
      "name": "__add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int __add_memory(int nid, u64 start, u64 size, mhp_t mhp_flags)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597890544,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1589",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597890544,
      "name": "__add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int __add_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503907424,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1122",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503907424,
      "name": "__add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286555744,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1122",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286555744,
      "name": "__add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
    }
  ]
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589758176,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1122",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589758176,
      "name": "__add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int __add_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589482400,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1122",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589482400,
      "name": "__add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int __add_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590201584,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1122",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590201584,
      "name": "__add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int __add_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__add_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590251984,
      "name": "__add_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1122",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add",
        "drivers/base/memory.c:probe_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590251984,
      "name": "__add_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __add_memory(int nid, u64 start, u64 size)
```
</details>
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
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>mhp_t mhp_flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __add_memory(int nid, u64 start, u64 size)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __add_memory(int nid, u64 start, u64 size)
```
</details>
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
