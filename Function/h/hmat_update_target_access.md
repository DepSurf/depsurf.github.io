# Function: <code>hmat_update_target_access</code>

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
void hmat_update_target_access(struct memory_target * target, u8 type, u32 value)
```

```json
{
  "name": "hmat_update_target_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605008971,
      "name": "hmat_update_target_access",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:186",
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
      "addr": 18446744071605008971,
      "name": "hmat_update_target_access",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 82
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
  "name": "hmat_update_target_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585377999,
      "name": "hmat_update_target_access",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:196",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hmat_update_target_access(struct memory_target * target, u8 type, u32 value)
```

```json
{
  "name": "hmat_update_target_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586086722,
      "name": "hmat_update_target_access",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:217",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586087174,
      "name": "hmat_update_target_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hmat_update_target_access(struct memory_target * target, u8 type, u32 value, int access)
```

```json
{
  "name": "hmat_update_target_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586207269,
      "name": "hmat_update_target_access",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:226",
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
      "addr": 18446744071591440286,
      "name": "hmat_update_target_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hmat_update_target_access(struct memory_target * target, u8 type, u32 value, int access)
```

```json
{
  "name": "hmat_update_target_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586081987,
      "name": "hmat_update_target_access",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:226",
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
      "addr": 18446744071591381441,
      "name": "hmat_update_target_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hmat_update_target_access(struct memory_target * target, u8 type, u32 value, int access)
```

```json
{
  "name": "hmat_update_target_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586579100,
      "name": "hmat_update_target_access",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:226",
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
      "addr": 18446744071592418073,
      "name": "hmat_update_target_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
void hmat_update_target_access(struct memory_target * target, u8 type, u32 value, int access)
```

```json
{
  "name": "hmat_update_target_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587839138,
      "name": "hmat_update_target_access",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:226",
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
      "addr": 18446744071594285741,
      "name": "hmat_update_target_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
  "name": "hmat_update_target_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589181817,
      "name": "hmat_update_target_access",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:225",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hmat_update_target_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589475879,
      "name": "hmat_update_target_access",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:225",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hmat_update_target_access(struct memory_target * target, u8 type, u32 value, int access)
```

```json
{
  "name": "hmat_update_target_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589780864,
      "name": "hmat_update_target_access",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:299",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/numa/hmat.c:hmat_update_target_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589780864,
      "name": "hmat_update_target_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 575
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
  "name": "hmat_update_target_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497652048,
      "name": "hmat_update_target_access",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:196",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
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
  "name": "hmat_update_target_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585169967,
      "name": "hmat_update_target_access",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:196",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
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
  "name": "hmat_update_target_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585112959,
      "name": "hmat_update_target_access",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:196",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
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
  "name": "hmat_update_target_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585435727,
      "name": "hmat_update_target_access",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:196",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void hmat_update_target_access(struct memory_target * target, u8 type, u32 value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void hmat_update_target_access(struct memory_target * target, u8 type, u32 value)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void hmat_update_target_access(struct memory_target * target, u8 type, u32 value)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int access</code>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void hmat_update_target_access(struct memory_target * target, u8 type, u32 value, int access)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void hmat_update_target_access(struct memory_target * target, u8 type, u32 value, int access)
```
</details>
</li>
</ul>
