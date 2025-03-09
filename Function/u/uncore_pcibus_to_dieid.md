# Function: <code>uncore_pcibus_to_dieid</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int uncore_pcibus_to_dieid(struct pci_bus * bus)
```

```json
{
  "name": "uncore_pcibus_to_dieid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578955361,
      "name": "uncore_pcibus_to_dieid",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:39",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe",
        "arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578954624,
      "name": "uncore_pcibus_to_dieid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int uncore_pcibus_to_dieid(struct pci_bus * bus)
```

```json
{
  "name": "uncore_pcibus_to_dieid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578965857,
      "name": "uncore_pcibus_to_dieid",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:39",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578965360,
      "name": "uncore_pcibus_to_dieid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int uncore_pcibus_to_dieid(struct pci_bus * bus)
```

```json
{
  "name": "uncore_pcibus_to_dieid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578976040,
      "name": "uncore_pcibus_to_dieid",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:39",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe",
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578976400,
      "name": "uncore_pcibus_to_dieid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int uncore_pcibus_to_dieid(struct pci_bus * bus)
```

```json
{
  "name": "uncore_pcibus_to_dieid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627513365,
      "name": "uncore_pcibus_to_dieid",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:39",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe",
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578994976,
      "name": "uncore_pcibus_to_dieid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int uncore_pcibus_to_dieid(struct pci_bus * bus)
```

```json
{
  "name": "uncore_pcibus_to_dieid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619258277,
      "name": "uncore_pcibus_to_dieid",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:39",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe",
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578994304,
      "name": "uncore_pcibus_to_dieid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int uncore_pcibus_to_dieid(struct pci_bus * bus)
```

```json
{
  "name": "uncore_pcibus_to_dieid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621550949,
      "name": "uncore_pcibus_to_dieid",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:39",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe",
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579019184,
      "name": "uncore_pcibus_to_dieid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int uncore_pcibus_to_dieid(struct pci_bus * bus)
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
