# Function: <code>uncore_get_uncores</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type * * uncore_get_uncores(enum uncore_access_type type_id, int num_extra, struct intel_uncore_type * * extra)
```

```json
{
  "name": "uncore_get_uncores",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578989648,
      "name": "uncore_get_uncores",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:5992",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989648,
      "name": "uncore_get_uncores",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
struct intel_uncore_type * * uncore_get_uncores(enum uncore_access_type type_id, int num_extra, struct intel_uncore_type * * extra)
```

```json
{
  "name": "uncore_get_uncores",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579005568,
      "name": "uncore_get_uncores",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:5992",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579005568,
      "name": "uncore_get_uncores",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
struct intel_uncore_type * * uncore_get_uncores(enum uncore_access_type type_id, int num_extra, struct intel_uncore_type * * extra)
```

```json
{
  "name": "uncore_get_uncores",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579028864,
      "name": "uncore_get_uncores",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:6367",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579028864,
      "name": "uncore_get_uncores",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
struct intel_uncore_type * * uncore_get_uncores(enum uncore_access_type type_id, int num_extra, struct intel_uncore_type * * extra)
```

```json
{
  "name": "uncore_get_uncores",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579029440,
      "name": "uncore_get_uncores",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:6414",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579029440,
      "name": "uncore_get_uncores",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
struct intel_uncore_type * * uncore_get_uncores(enum uncore_access_type type_id, int num_extra, struct intel_uncore_type * * extra, int max_num_types, struct intel_uncore_type * * uncores)
```

```json
{
  "name": "uncore_get_uncores",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579054528,
      "name": "uncore_get_uncores",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:6426",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:gnr_uncore_mmio_init",
        "arch/x86/events/intel/uncore_snbep.c:gnr_uncore_pci_init",
        "arch/x86/events/intel/uncore_snbep.c:gnr_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_init",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054528,
      "name": "uncore_get_uncores",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct intel_uncore_type * * uncore_get_uncores(enum uncore_access_type type_id, int num_extra, struct intel_uncore_type * * extra)
```
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int max_num_types</code>
</li>
<li>
<b>Param added. </b>
<code>struct intel_uncore_type * * uncores</code>
</li>
</ul>
</details>
</li>
</ul>
