# Function: <code>uncore_pci_find_dev_pmu</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct intel_uncore_pmu * uncore_pci_find_dev_pmu(struct pci_dev * pdev, const struct pci_device_id * ids)
```

```json
{
  "name": "uncore_pci_find_dev_pmu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578944016,
      "name": "uncore_pci_find_dev_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1020",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578944016,
      "name": "uncore_pci_find_dev_pmu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
  "name": "uncore_pci_find_dev_pmu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578955263,
      "name": "uncore_pci_find_dev_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1080",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578949632,
      "name": "uncore_pci_find_dev_pmu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
  "name": "uncore_pci_find_dev_pmu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578965759,
      "name": "uncore_pci_find_dev_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1087",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578960096,
      "name": "uncore_pci_find_dev_pmu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
  "name": "uncore_pci_find_dev_pmu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578976009,
      "name": "uncore_pci_find_dev_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1087",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970192,
      "name": "uncore_pci_find_dev_pmu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
  "name": "uncore_pci_find_dev_pmu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578994553,
      "name": "uncore_pci_find_dev_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1087",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578988048,
      "name": "uncore_pci_find_dev_pmu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_pci_find_dev_pmu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578993881,
      "name": "uncore_pci_find_dev_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1108",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578987248,
      "name": "uncore_pci_find_dev_pmu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
  "name": "uncore_pci_find_dev_pmu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579018761,
      "name": "uncore_pci_find_dev_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1108",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579012128,
      "name": "uncore_pci_find_dev_pmu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct intel_uncore_pmu * uncore_pci_find_dev_pmu(struct pci_dev * pdev, const struct pci_device_id * ids)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct intel_uncore_pmu * uncore_pci_find_dev_pmu(struct pci_dev * pdev, const struct pci_device_id * ids)
```
</details>
</li>
</ul>
