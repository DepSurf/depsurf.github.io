# Function: <code>snr_uncore_mmio_map</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int snr_uncore_mmio_map(struct intel_uncore_box * box, unsigned int box_ctl, int mem_offset, unsigned int device)
```

```json
{
  "name": "snr_uncore_mmio_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "snr_uncore_mmio_map",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4840",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989264,
      "name": "snr_uncore_mmio_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071592045635,
      "name": "snr_uncore_mmio_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int snr_uncore_mmio_map(struct intel_uncore_box * box, unsigned int box_ctl, int mem_offset, unsigned int device)
```

```json
{
  "name": "snr_uncore_mmio_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "snr_uncore_mmio_map",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4840",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579005136,
      "name": "snr_uncore_mmio_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071593812155,
      "name": "snr_uncore_mmio_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int snr_uncore_mmio_map(struct intel_uncore_box * box, unsigned int box_ctl, int mem_offset, unsigned int device)
```

```json
{
  "name": "snr_uncore_mmio_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579028352,
      "name": "snr_uncore_mmio_map",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:5094",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579028352,
      "name": "snr_uncore_mmio_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int snr_uncore_mmio_map(struct intel_uncore_box * box, unsigned int box_ctl, int mem_offset, unsigned int device)
```

```json
{
  "name": "snr_uncore_mmio_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579028928,
      "name": "snr_uncore_mmio_map",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:5084",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579028928,
      "name": "snr_uncore_mmio_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int snr_uncore_mmio_map(struct intel_uncore_box * box, unsigned int box_ctl, int mem_offset, unsigned int device)
```

```json
{
  "name": "snr_uncore_mmio_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579053856,
      "name": "snr_uncore_mmio_map",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:5092",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579053856,
      "name": "snr_uncore_mmio_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int snr_uncore_mmio_map(struct intel_uncore_box * box, unsigned int box_ctl, int mem_offset, unsigned int device)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
