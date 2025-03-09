# Function: <code>__snr_uncore_mmio_init_box</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __snr_uncore_mmio_init_box(struct intel_uncore_box * box, unsigned int box_ctl, int mem_offset)
```

```json
{
  "name": "__snr_uncore_mmio_init_box",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578968848,
      "name": "__snr_uncore_mmio_init_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4420",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578968848,
      "name": "__snr_uncore_mmio_init_box",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void __snr_uncore_mmio_init_box(struct intel_uncore_box * box, unsigned int box_ctl, int mem_offset)
```

```json
{
  "name": "__snr_uncore_mmio_init_box",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__snr_uncore_mmio_init_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4667",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970416,
      "name": "__snr_uncore_mmio_init_box",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071591241271,
      "name": "__snr_uncore_mmio_init_box.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void __snr_uncore_mmio_init_box(struct intel_uncore_box * box, unsigned int box_ctl, int mem_offset)
```

```json
{
  "name": "__snr_uncore_mmio_init_box",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__snr_uncore_mmio_init_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4692",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578975696,
      "name": "__snr_uncore_mmio_init_box",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    },
    {
      "addr": 18446744071591184425,
      "name": "__snr_uncore_mmio_init_box.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
  "name": "__snr_uncore_mmio_init_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578990661,
      "name": "__snr_uncore_mmio_init_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4869",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
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
  "name": "__snr_uncore_mmio_init_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579006581,
      "name": "__snr_uncore_mmio_init_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4869",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
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
  "name": "__snr_uncore_mmio_init_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579031269,
      "name": "__snr_uncore_mmio_init_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:5125",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
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
  "name": "__snr_uncore_mmio_init_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579032165,
      "name": "__snr_uncore_mmio_init_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:5115",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
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
  "name": "__snr_uncore_mmio_init_box",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579056789,
      "name": "__snr_uncore_mmio_init_box",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:5123",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:icx_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
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
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __snr_uncore_mmio_init_box(struct intel_uncore_box * box, unsigned int box_ctl, int mem_offset)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void __snr_uncore_mmio_init_box(struct intel_uncore_box * box, unsigned int box_ctl, int mem_offset)
```
</details>
</li>
</ul>
