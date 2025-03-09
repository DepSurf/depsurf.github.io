# Function: <code>mhp_supports_memmap_on_memory</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mhp_supports_memmap_on_memory(long unsigned int size)
```

```json
{
  "name": "mhp_supports_memmap_on_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591613142,
      "name": "mhp_supports_memmap_on_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1155",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource"
      ],
      "caller_func": [
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758000,
      "name": "mhp_supports_memmap_on_memory",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool mhp_supports_memmap_on_memory(long unsigned int size)
```

```json
{
  "name": "mhp_supports_memmap_on_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mhp_supports_memmap_on_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1311",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592208170,
      "name": "mhp_supports_memmap_on_memory.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582039952,
      "name": "mhp_supports_memmap_on_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool mhp_supports_memmap_on_memory(long unsigned int size)
```

```json
{
  "name": "mhp_supports_memmap_on_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mhp_supports_memmap_on_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1277",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593985839,
      "name": "mhp_supports_memmap_on_memory.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582470000,
      "name": "mhp_supports_memmap_on_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool mhp_supports_memmap_on_memory(long unsigned int size)
```

```json
{
  "name": "mhp_supports_memmap_on_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mhp_supports_memmap_on_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1275",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596038077,
      "name": "mhp_supports_memmap_on_memory.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582984464,
      "name": "mhp_supports_memmap_on_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool mhp_supports_memmap_on_memory(long unsigned int size)
```

```json
{
  "name": "mhp_supports_memmap_on_memory",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mhp_supports_memmap_on_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:1250",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596560302,
      "name": "mhp_supports_memmap_on_memory.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583195984,
      "name": "mhp_supports_memmap_on_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
  "name": "mhp_supports_memmap_on_memory",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597889848,
      "name": "mhp_supports_memmap_on_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:1340",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource"
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
bool mhp_supports_memmap_on_memory(long unsigned int size)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
bool mhp_supports_memmap_on_memory(long unsigned int size)
```
</details>
</li>
</ul>
