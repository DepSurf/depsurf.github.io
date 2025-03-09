# Function: <code>pmu_iio_mapping_visible</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmu_iio_mapping_visible",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578991415,
      "name": "pmu_iio_mapping_visible",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:3709",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:icx_iio_mapping_visible",
        "arch/x86/events/intel/uncore_snbep.c:snr_iio_mapping_visible",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_visible"
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
  "name": "pmu_iio_mapping_visible",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579007447,
      "name": "pmu_iio_mapping_visible",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:3709",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:icx_iio_mapping_visible",
        "arch/x86/events/intel/uncore_snbep.c:snr_iio_mapping_visible",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_visible"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
umode_t pmu_iio_mapping_visible(struct kobject * kobj, struct attribute * attr, int die, int zero_bus_pmu)
```

```json
{
  "name": "pmu_iio_mapping_visible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579033904,
      "name": "pmu_iio_mapping_visible",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:3735",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:icx_iio_mapping_visible",
        "arch/x86/events/intel/uncore_snbep.c:snr_iio_mapping_visible",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_visible"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033904,
      "name": "pmu_iio_mapping_visible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
umode_t pmu_iio_mapping_visible(struct kobject * kobj, struct attribute * attr, int die, int zero_bus_pmu)
```

```json
{
  "name": "pmu_iio_mapping_visible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579033872,
      "name": "pmu_iio_mapping_visible",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:3725",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:icx_iio_mapping_visible",
        "arch/x86/events/intel/uncore_snbep.c:snr_iio_mapping_visible",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_visible"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033872,
      "name": "pmu_iio_mapping_visible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
umode_t pmu_iio_mapping_visible(struct kobject * kobj, struct attribute * attr, int die, int zero_bus_pmu)
```

```json
{
  "name": "pmu_iio_mapping_visible",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579057872,
      "name": "pmu_iio_mapping_visible",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:3733",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:icx_iio_mapping_visible",
        "arch/x86/events/intel/uncore_snbep.c:snr_iio_mapping_visible",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_visible"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579057872,
      "name": "pmu_iio_mapping_visible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
umode_t pmu_iio_mapping_visible(struct kobject * kobj, struct attribute * attr, int die, int zero_bus_pmu)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
