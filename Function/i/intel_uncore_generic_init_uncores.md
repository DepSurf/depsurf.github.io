# Function: <code>intel_uncore_generic_init_uncores</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_type * * intel_uncore_generic_init_uncores(enum uncore_access_type type_id)
```

```json
{
  "name": "intel_uncore_generic_init_uncores",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578982976,
      "name": "intel_uncore_generic_init_uncores",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_discovery.c:572",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_mmio_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_pci_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578982976,
      "name": "intel_uncore_generic_init_uncores",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
struct intel_uncore_type * * intel_uncore_generic_init_uncores(enum uncore_access_type type_id, int num_extra)
```

```json
{
  "name": "intel_uncore_generic_init_uncores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579000656,
      "name": "intel_uncore_generic_init_uncores",
      "external": true,
      "loc": "arch/x86/events/intel/uncore_discovery.c:572",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:uncore_get_uncores",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_mmio_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_pci_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579000656,
      "name": "intel_uncore_generic_init_uncores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
struct intel_uncore_type * * intel_uncore_generic_init_uncores(enum uncore_access_type type_id, int num_extra)
```

```json
{
  "name": "intel_uncore_generic_init_uncores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579017136,
      "name": "intel_uncore_generic_init_uncores",
      "external": true,
      "loc": "arch/x86/events/intel/uncore_discovery.c:580",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:uncore_get_uncores",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_mmio_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_pci_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579017136,
      "name": "intel_uncore_generic_init_uncores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
struct intel_uncore_type * * intel_uncore_generic_init_uncores(enum uncore_access_type type_id, int num_extra)
```

```json
{
  "name": "intel_uncore_generic_init_uncores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579044544,
      "name": "intel_uncore_generic_init_uncores",
      "external": true,
      "loc": "arch/x86/events/intel/uncore_discovery.c:580",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:uncore_get_uncores",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_mmio_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_pci_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044544,
      "name": "intel_uncore_generic_init_uncores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
struct intel_uncore_type * * intel_uncore_generic_init_uncores(enum uncore_access_type type_id, int num_extra)
```

```json
{
  "name": "intel_uncore_generic_init_uncores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579044544,
      "name": "intel_uncore_generic_init_uncores",
      "external": true,
      "loc": "arch/x86/events/intel/uncore_discovery.c:600",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:uncore_get_uncores",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_mmio_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_pci_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044544,
      "name": "intel_uncore_generic_init_uncores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
struct intel_uncore_type * * intel_uncore_generic_init_uncores(enum uncore_access_type type_id, int num_extra)
```

```json
{
  "name": "intel_uncore_generic_init_uncores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579069840,
      "name": "intel_uncore_generic_init_uncores",
      "external": true,
      "loc": "arch/x86/events/intel/uncore_discovery.c:601",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:uncore_get_uncores",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_mmio_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_pci_init",
        "arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579069840,
      "name": "intel_uncore_generic_init_uncores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct intel_uncore_type * * intel_uncore_generic_init_uncores(enum uncore_access_type type_id)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int num_extra</code>
</li>
</ul>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
