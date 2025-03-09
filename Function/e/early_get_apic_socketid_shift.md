# Function: <code>early_get_apic_socketid_shift</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "early_get_apic_socketid_shift",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604776084,
      "name": "early_get_apic_socketid_shift",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:225",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check"
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
  "name": "early_get_apic_socketid_shift",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609127785,
      "name": "early_get_apic_socketid_shift",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:215",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check"
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
  "name": "early_get_apic_socketid_shift",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612198168,
      "name": "early_get_apic_socketid_shift",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:278",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void early_get_apic_socketid_shift()
```

```json
{
  "name": "early_get_apic_socketid_shift",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614331768,
      "name": "early_get_apic_socketid_shift",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:278",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614331768,
      "name": "early_get_apic_socketid_shift",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 380
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
void early_get_apic_socketid_shift()
```

```json
{
  "name": "early_get_apic_socketid_shift",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615261245,
      "name": "early_get_apic_socketid_shift",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:278",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615261245,
      "name": "early_get_apic_socketid_shift",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 380
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
void early_get_apic_socketid_shift()
```

```json
{
  "name": "early_get_apic_socketid_shift",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617037667,
      "name": "early_get_apic_socketid_shift",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:284",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617037667,
      "name": "early_get_apic_socketid_shift",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 376
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
void early_get_apic_socketid_shift()
```

```json
{
  "name": "early_get_apic_socketid_shift",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627673488,
      "name": "early_get_apic_socketid_shift",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:284",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627673488,
      "name": "early_get_apic_socketid_shift",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 460
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
void early_get_apic_socketid_shift()
```

```json
{
  "name": "early_get_apic_socketid_shift",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619430752,
      "name": "early_get_apic_socketid_shift",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:284",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619430752,
      "name": "early_get_apic_socketid_shift",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 476
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
void early_get_apic_socketid_shift()
```

```json
{
  "name": "early_get_apic_socketid_shift",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621726960,
      "name": "early_get_apic_socketid_shift",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:286",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621726960,
      "name": "early_get_apic_socketid_shift",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 476
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "early_get_apic_socketid_shift",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604780225,
      "name": "early_get_apic_socketid_shift",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:225",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check"
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void early_get_apic_socketid_shift()
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
