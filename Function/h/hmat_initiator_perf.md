# Function: <code>hmat_initiator_perf</code>

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
  "name": "hmat_initiator_perf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605010636,
      "name": "hmat_initiator_perf",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:438",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
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
  "name": "hmat_initiator_perf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585377767,
      "name": "hmat_initiator_perf",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:459",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
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
  "name": "hmat_initiator_perf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586086233,
      "name": "hmat_initiator_perf",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:480",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
u32 hmat_initiator_perf(struct memory_target * target, struct memory_initiator * initiator, struct acpi_hmat_locality * hmat_loc)
```

```json
{
  "name": "hmat_initiator_perf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586206704,
      "name": "hmat_initiator_perf",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:494",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586206704,
      "name": "hmat_initiator_perf",
      "section": ".text",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
u32 hmat_initiator_perf(struct memory_target * target, struct memory_initiator * initiator, struct acpi_hmat_locality * hmat_loc)
```

```json
{
  "name": "hmat_initiator_perf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586081424,
      "name": "hmat_initiator_perf",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:494",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586081424,
      "name": "hmat_initiator_perf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
u32 hmat_initiator_perf(struct memory_target * target, struct memory_initiator * initiator, struct acpi_hmat_locality * hmat_loc)
```

```json
{
  "name": "hmat_initiator_perf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586578528,
      "name": "hmat_initiator_perf",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:494",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586578528,
      "name": "hmat_initiator_perf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
u32 hmat_initiator_perf(struct memory_target * target, struct memory_initiator * initiator, struct acpi_hmat_locality * hmat_loc)
```

```json
{
  "name": "hmat_initiator_perf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587838512,
      "name": "hmat_initiator_perf",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:494",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587838512,
      "name": "hmat_initiator_perf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
u32 hmat_initiator_perf(struct memory_target * target, struct memory_initiator * initiator, struct acpi_hmat_locality * hmat_loc)
```

```json
{
  "name": "hmat_initiator_perf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589180720,
      "name": "hmat_initiator_perf",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:493",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589180720,
      "name": "hmat_initiator_perf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
u32 hmat_initiator_perf(struct memory_target * target, struct memory_initiator * initiator, struct acpi_hmat_locality * hmat_loc)
```

```json
{
  "name": "hmat_initiator_perf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589474784,
      "name": "hmat_initiator_perf",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:493",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589474784,
      "name": "hmat_initiator_perf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
  "name": "hmat_initiator_perf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589781920,
      "name": "hmat_initiator_perf",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:598",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "hmat_initiator_perf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497651812,
      "name": "hmat_initiator_perf",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:459",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
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
  "name": "hmat_initiator_perf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585169735,
      "name": "hmat_initiator_perf",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:459",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
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
  "name": "hmat_initiator_perf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585112727,
      "name": "hmat_initiator_perf",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:459",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
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
  "name": "hmat_initiator_perf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585435495,
      "name": "hmat_initiator_perf",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:459",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
u32 hmat_initiator_perf(struct memory_target * target, struct memory_initiator * initiator, struct acpi_hmat_locality * hmat_loc)
```
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
u32 hmat_initiator_perf(struct memory_target * target, struct memory_initiator * initiator, struct acpi_hmat_locality * hmat_loc)
```
</details>
</li>
</ul>
