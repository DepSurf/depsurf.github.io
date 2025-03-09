# Function: <code>__remove_memory</code>

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
void __remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__remove_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589470624,
      "name": "__remove_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1853",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:remove_memory",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589470624,
      "name": "__remove_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void __remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__remove_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581586480,
      "name": "__remove_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1812",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586480,
      "name": "__remove_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__remove_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581649920,
      "name": "__remove_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1802",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581649920,
      "name": "__remove_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__remove_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581867024,
      "name": "__remove_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1811",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581867024,
      "name": "__remove_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__remove_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911888,
      "name": "__remove_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1773",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911888,
      "name": "__remove_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__remove_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581759184,
      "name": "__remove_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:2057",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759184,
      "name": "__remove_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __remove_memory(u64 start, u64 size)
```

```json
{
  "name": "__remove_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582041232,
      "name": "__remove_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:2229",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041232,
      "name": "__remove_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __remove_memory(u64 start, u64 size)
```

```json
{
  "name": "__remove_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582470864,
      "name": "__remove_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:2151",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470864,
      "name": "__remove_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __remove_memory(u64 start, u64 size)
```

```json
{
  "name": "__remove_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582985472,
      "name": "__remove_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:2147",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582985472,
      "name": "__remove_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __remove_memory(u64 start, u64 size)
```

```json
{
  "name": "__remove_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583196992,
      "name": "__remove_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:2120",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583196992,
      "name": "__remove_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __remove_memory(u64 start, u64 size)
```

```json
{
  "name": "__remove_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583381760,
      "name": "__remove_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:2313",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583381760,
      "name": "__remove_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
  "name": "__remove_memory",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__remove_memory",
      "external": false,
      "loc": "include/linux/memory_hotplug.h:343",
      "file": "drivers/acpi/acpi_memhotplug.c",
      "inline": "declared, inlined",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__remove_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286550800,
      "name": "__remove_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1802",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime",
        "arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286550800,
      "name": "__remove_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__remove_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581618656,
      "name": "__remove_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1802",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581618656,
      "name": "__remove_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__remove_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581559984,
      "name": "__remove_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1802",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559984,
      "name": "__remove_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__remove_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581609968,
      "name": "__remove_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1802",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581609968,
      "name": "__remove_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __remove_memory(int nid, u64 start, u64 size)
```

```json
{
  "name": "__remove_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581676160,
      "name": "__remove_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1802",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581676160,
      "name": "__remove_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __remove_memory(int nid, u64 start, u64 size)
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nid</code>
</li>
<li>
<b>Param reordered. </b>
<code>nid, start, size</code> ➡️ <code>start, size</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __remove_memory(int nid, u64 start, u64 size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __remove_memory(int nid, u64 start, u64 size)
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
void __remove_memory(int nid, u64 start, u64 size)
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
