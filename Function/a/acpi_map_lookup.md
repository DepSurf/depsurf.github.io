# Function: <code>acpi_map_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_ioremap * acpi_map_lookup(acpi_physical_address phys, acpi_size size)
```

```json
{
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583537332,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:282",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_write_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583537332,
      "name": "acpi_map_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct acpi_ioremap * acpi_map_lookup(acpi_physical_address phys, acpi_size size)
```

```json
{
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583858465,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:214",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583858465,
      "name": "acpi_map_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_ioremap * acpi_map_lookup(acpi_physical_address phys, acpi_size size)
```

```json
{
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583997489,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:215",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583997489,
      "name": "acpi_map_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584048328,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:214",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584312440,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:214",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584532637,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:219",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584629965,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:219",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584829647,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:205",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584965375,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:219",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585660927,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:219",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585786582,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:222",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585666950,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:225",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586146422,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:225",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587378885,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:224",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_unmap_generic_address",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588628773,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:224",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588916517,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:224",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_unmap_generic_address",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589212581,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:224",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_unmap_generic_address",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497380624,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:219",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584915551,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:219",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584821471,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:219",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584916959,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:219",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
  "name": "acpi_map_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585023077,
      "name": "acpi_map_lookup",
      "external": false,
      "loc": "drivers/acpi/osl.c:219",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_get_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct acpi_ioremap * acpi_map_lookup(acpi_physical_address phys, acpi_size size)
```
</details>
</li>
</ul>
