# Function: <code>hmat_normalize</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
u32 hmat_normalize(u16 entry, u64 base, u8 type)
```

```json
{
  "name": "hmat_normalize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605008860,
      "name": "hmat_normalize",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:151",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605008860,
      "name": "hmat_normalize",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 111
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
  "name": "hmat_normalize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585377878,
      "name": "hmat_normalize",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:161",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
      ],
      "caller_func": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585377456,
      "name": "hmat_normalize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
  "name": "hmat_normalize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586086343,
      "name": "hmat_normalize",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:182",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586087256,
      "name": "hmat_normalize.part.0",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hmat_normalize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586206822,
      "name": "hmat_normalize",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:191",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_initiator_perf",
        "drivers/acpi/numa/hmat.c:hmat_initiator_perf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591440428,
      "name": "hmat_normalize.part.0",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hmat_normalize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586081544,
      "name": "hmat_normalize",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:191",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_initiator_perf",
        "drivers/acpi/numa/hmat.c:hmat_initiator_perf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591381583,
      "name": "hmat_normalize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "hmat_normalize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586578648,
      "name": "hmat_normalize",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:191",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_initiator_perf",
        "drivers/acpi/numa/hmat.c:hmat_initiator_perf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592418459,
      "name": "hmat_normalize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "hmat_normalize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587838647,
      "name": "hmat_normalize",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:191",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_initiator_perf",
        "drivers/acpi/numa/hmat.c:hmat_initiator_perf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594286156,
      "name": "hmat_normalize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
  "name": "hmat_normalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589180855,
      "name": "hmat_normalize",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:190",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_initiator_perf",
        "drivers/acpi/numa/hmat.c:hmat_initiator_perf"
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
  "name": "hmat_normalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589474919,
      "name": "hmat_normalize",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:190",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_initiator_perf",
        "drivers/acpi/numa/hmat.c:hmat_initiator_perf"
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
  "name": "hmat_normalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589782052,
      "name": "hmat_normalize",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:264",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_update_target_attrs",
        "drivers/acpi/numa/hmat.c:hmat_update_target_attrs"
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
  "name": "hmat_normalize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497651936,
      "name": "hmat_normalize",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:161",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
      ],
      "caller_func": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497651408,
      "name": "hmat_normalize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
  "name": "hmat_normalize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585169846,
      "name": "hmat_normalize",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:161",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
      ],
      "caller_func": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585169424,
      "name": "hmat_normalize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
  "name": "hmat_normalize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585112838,
      "name": "hmat_normalize",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:161",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
      ],
      "caller_func": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585112416,
      "name": "hmat_normalize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
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
  "name": "hmat_normalize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585435606,
      "name": "hmat_normalize",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:161",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
      ],
      "caller_func": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585435184,
      "name": "hmat_normalize.part.0",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
u32 hmat_normalize(u16 entry, u64 base, u8 type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
u32 hmat_normalize(u16 entry, u64 base, u8 type)
```
</details>
</li>
</ul>
