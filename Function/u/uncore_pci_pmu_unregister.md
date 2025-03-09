# Function: <code>uncore_pci_pmu_unregister</code>

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
void uncore_pci_pmu_unregister(struct intel_uncore_pmu * pmu, int phys_id, int die)
```

```json
{
  "name": "uncore_pci_pmu_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578947600,
      "name": "uncore_pci_pmu_unregister",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1148",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578947600,
      "name": "uncore_pci_pmu_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void uncore_pci_pmu_unregister(struct intel_uncore_pmu * pmu, int die)
```

```json
{
  "name": "uncore_pci_pmu_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578952512,
      "name": "uncore_pci_pmu_unregister",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1208",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578952512,
      "name": "uncore_pci_pmu_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void uncore_pci_pmu_unregister(struct intel_uncore_pmu * pmu, int die)
```

```json
{
  "name": "uncore_pci_pmu_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_pci_pmu_unregister",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1215",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578963024,
      "name": "uncore_pci_pmu_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071592044593,
      "name": "uncore_pci_pmu_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void uncore_pci_pmu_unregister(struct intel_uncore_pmu * pmu, int die)
```

```json
{
  "name": "uncore_pci_pmu_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_pci_pmu_unregister",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1215",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578973264,
      "name": "uncore_pci_pmu_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071593811176,
      "name": "uncore_pci_pmu_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void uncore_pci_pmu_unregister(struct intel_uncore_pmu * pmu, int die)
```

```json
{
  "name": "uncore_pci_pmu_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_pci_pmu_unregister",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1215",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578991696,
      "name": "uncore_pci_pmu_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071595954987,
      "name": "uncore_pci_pmu_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void uncore_pci_pmu_unregister(struct intel_uncore_pmu * pmu, int die)
```

```json
{
  "name": "uncore_pci_pmu_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_pci_pmu_unregister",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1236",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578990960,
      "name": "uncore_pci_pmu_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071596472157,
      "name": "uncore_pci_pmu_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void uncore_pci_pmu_unregister(struct intel_uncore_pmu * pmu, int die)
```

```json
{
  "name": "uncore_pci_pmu_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_pci_pmu_unregister",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1236",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579015840,
      "name": "uncore_pci_pmu_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071597367499,
      "name": "uncore_pci_pmu_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void uncore_pci_pmu_unregister(struct intel_uncore_pmu * pmu, int phys_id, int die)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int phys_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>pmu, phys_id, die</code> ➡️ <code>pmu, die</code>
</li>
</ul>
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
