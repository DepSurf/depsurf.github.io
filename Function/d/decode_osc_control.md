# Function: <code>decode_osc_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void decode_osc_control(struct acpi_pci_root * root, char * msg, u32 word)
```

```json
{
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583586631,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:179",
      "file": "drivers/acpi/pci_root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583586631,
      "name": "decode_osc_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void decode_osc_control(struct acpi_pci_root * root, char * msg, u32 word)
```

```json
{
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583909077,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:179",
      "file": "drivers/acpi/pci_root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583909077,
      "name": "decode_osc_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void decode_osc_control(struct acpi_pci_root * root, char * msg, u32 word)
```

```json
{
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584049956,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:179",
      "file": "drivers/acpi/pci_root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049956,
      "name": "decode_osc_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584111225,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:179",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584381919,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:180",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584604258,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:181",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584701770,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:181",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584902486,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:169",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585038195,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:168",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585741071,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:170",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591434568,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:168",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591375737,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:166",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592411078,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:168",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594278048,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:176",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588721210,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:176",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589009518,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:176",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589313870,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:176",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497451280,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:168",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584977491,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:168",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584886339,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:168",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584989779,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:168",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
  "name": "decode_osc_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585095955,
      "name": "decode_osc_control",
      "external": false,
      "loc": "drivers/acpi/pci_root.c:168",
      "file": "drivers/acpi/pci_root.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:negotiate_os_control",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set",
        "drivers/acpi/pci_root.c:acpi_pci_osc_control_set"
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
void decode_osc_control(struct acpi_pci_root * root, char * msg, u32 word)
```
</details>
</li>
</ul>
