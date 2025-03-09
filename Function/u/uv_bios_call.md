# Function: <code>uv_bios_call</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
s64 uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```

```json
{
  "name": "uv_bios_call",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579467792,
      "name": "uv_bios_call",
      "external": true,
      "loc": "arch/x86/platform/uv/bios_uv.c:45",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579467792,
      "name": "uv_bios_call",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
  "name": "uv_bios_call",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579490777,
      "name": "uv_bios_call",
      "external": false,
      "loc": "arch/x86/platform/uv/bios_uv.c:48",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base"
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
  "name": "uv_bios_call",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579471930,
      "name": "uv_bios_call",
      "external": false,
      "loc": "arch/x86/platform/uv/bios_uv.c:40",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base"
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
  "name": "uv_bios_call",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579474010,
      "name": "uv_bios_call",
      "external": false,
      "loc": "arch/x86/platform/uv/bios_uv.c:40",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base"
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
  "name": "uv_bios_call",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579539578,
      "name": "uv_bios_call",
      "external": false,
      "loc": "arch/x86/platform/uv/bios_uv.c:40",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base"
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
  "name": "uv_bios_call",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579627897,
      "name": "uv_bios_call",
      "external": false,
      "loc": "arch/x86/platform/uv/bios_uv.c:40",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base"
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
  "name": "uv_bios_call",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579741881,
      "name": "uv_bios_call",
      "external": false,
      "loc": "arch/x86/platform/uv/bios_uv.c:40",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base"
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
  "name": "uv_bios_call",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579788361,
      "name": "uv_bios_call",
      "external": false,
      "loc": "arch/x86/platform/uv/bios_uv.c:40",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base"
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
  "name": "uv_bios_call",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579822025,
      "name": "uv_bios_call",
      "external": false,
      "loc": "arch/x86/platform/uv/bios_uv.c:40",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base"
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
s64 uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```

```json
{
  "name": "uv_bios_call",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579473120,
      "name": "uv_bios_call",
      "external": true,
      "loc": "arch/x86/platform/uv/bios_uv.c:45",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579473120,
      "name": "uv_bios_call",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
s64 uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
s64 uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
s64 uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
s64 uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
s64 uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
s64 uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
s64 uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
s64 uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
s64 uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
