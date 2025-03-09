# Function: <code>alloc_memory_target</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_memory_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605009082,
      "name": "alloc_memory_target",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:95",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity"
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
  "name": "alloc_memory_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605046279,
      "name": "alloc_memory_target",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:107",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void alloc_memory_target(unsigned int mem_pxm, resource_size_t start, resource_size_t len)
```

```json
{
  "name": "alloc_memory_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609335211,
      "name": "alloc_memory_target",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:114",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609335211,
      "name": "alloc_memory_target",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 239
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
void alloc_memory_target(unsigned int mem_pxm, resource_size_t start, resource_size_t len)
```

```json
{
  "name": "alloc_memory_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612406180,
      "name": "alloc_memory_target",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:123",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612406180,
      "name": "alloc_memory_target",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 242
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
  "name": "alloc_memory_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614548101,
      "name": "alloc_memory_target",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:123",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity"
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
  "name": "alloc_memory_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615500350,
      "name": "alloc_memory_target",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:123",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity"
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
  "name": "alloc_memory_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617304981,
      "name": "alloc_memory_target",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:123",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity"
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
  "name": "alloc_memory_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071628022789,
      "name": "alloc_memory_target",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:122",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity"
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
  "name": "alloc_memory_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619788245,
      "name": "alloc_memory_target",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:122",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity"
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
  "name": "alloc_memory_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622095355,
      "name": "alloc_memory_target",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:196",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity"
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
  "name": "alloc_memory_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336511125608,
      "name": "alloc_memory_target",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:107",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity"
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
  "name": "alloc_memory_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604949066,
      "name": "alloc_memory_target",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:107",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity"
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
  "name": "alloc_memory_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604916814,
      "name": "alloc_memory_target",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:107",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity"
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_memory_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605050459,
      "name": "alloc_memory_target",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:107",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity"
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void alloc_memory_target(unsigned int mem_pxm, resource_size_t start, resource_size_t len)
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
void alloc_memory_target(unsigned int mem_pxm, resource_size_t start, resource_size_t len)
```
</details>
</li>
</ul>
