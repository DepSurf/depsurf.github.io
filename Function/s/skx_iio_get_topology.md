# Function: <code>skx_iio_get_topology</code>

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
int skx_iio_get_topology(struct intel_uncore_type * type)
```

```json
{
  "name": "skx_iio_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578974304,
      "name": "skx_iio_get_topology",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:3706",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578974304,
      "name": "skx_iio_get_topology",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
  "name": "skx_iio_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578978280,
      "name": "skx_iio_get_topology",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:3736",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int skx_iio_get_topology(struct intel_uncore_type * type)
```

```json
{
  "name": "skx_iio_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578992448,
      "name": "skx_iio_get_topology",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:3767",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578992448,
      "name": "skx_iio_get_topology",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int skx_iio_get_topology(struct intel_uncore_type * type)
```

```json
{
  "name": "skx_iio_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579008752,
      "name": "skx_iio_get_topology",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:3767",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579008752,
      "name": "skx_iio_get_topology",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
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
int skx_iio_get_topology(struct intel_uncore_type * type)
```

```json
{
  "name": "skx_iio_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579032720,
      "name": "skx_iio_get_topology",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:3899",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579032720,
      "name": "skx_iio_get_topology",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int skx_iio_get_topology(struct intel_uncore_type * type)
```

```json
{
  "name": "skx_iio_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579028016,
      "name": "skx_iio_get_topology",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:3889",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579028016,
      "name": "skx_iio_get_topology",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int skx_iio_get_topology(struct intel_uncore_type * type)
```

```json
{
  "name": "skx_iio_get_topology",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579052944,
      "name": "skx_iio_get_topology",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:3897",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579052944,
      "name": "skx_iio_get_topology",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int skx_iio_get_topology(struct intel_uncore_type * type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int skx_iio_get_topology(struct intel_uncore_type * type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int skx_iio_get_topology(struct intel_uncore_type * type)
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
