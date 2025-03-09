# Function: <code>snr_uncore_mmio_enable_event</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578954656,
      "name": "snr_uncore_mmio_enable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4456",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578954656,
      "name": "snr_uncore_mmio_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578957088,
      "name": "snr_uncore_mmio_enable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4432",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578957088,
      "name": "snr_uncore_mmio_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578962960,
      "name": "snr_uncore_mmio_enable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4475",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578962960,
      "name": "snr_uncore_mmio_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578971281,
      "name": "snr_uncore_mmio_enable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4725",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578971216,
      "name": "snr_uncore_mmio_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071591241295,
      "name": "snr_uncore_mmio_enable_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578976541,
      "name": "snr_uncore_mmio_enable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4750",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578976480,
      "name": "snr_uncore_mmio_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071591184449,
      "name": "snr_uncore_mmio_enable_event.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578990580,
      "name": "snr_uncore_mmio_enable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4908",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578990480,
      "name": "snr_uncore_mmio_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071592045736,
      "name": "snr_uncore_mmio_enable_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579007129,
      "name": "snr_uncore_mmio_enable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4908",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579007024,
      "name": "snr_uncore_mmio_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071593812255,
      "name": "snr_uncore_mmio_enable_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579031925,
      "name": "snr_uncore_mmio_enable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:5164",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579031824,
      "name": "snr_uncore_mmio_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071595955974,
      "name": "snr_uncore_mmio_enable_event.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579032821,
      "name": "snr_uncore_mmio_enable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:5154",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579032720,
      "name": "snr_uncore_mmio_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071596473324,
      "name": "snr_uncore_mmio_enable_event.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579057445,
      "name": "snr_uncore_mmio_enable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:5162",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579057344,
      "name": "snr_uncore_mmio_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071597368666,
      "name": "snr_uncore_mmio_enable_event.cold",
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578957088,
      "name": "snr_uncore_mmio_enable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4432",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578957088,
      "name": "snr_uncore_mmio_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578954608,
      "name": "snr_uncore_mmio_enable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4432",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578954608,
      "name": "snr_uncore_mmio_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578957024,
      "name": "snr_uncore_mmio_enable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4432",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578957024,
      "name": "snr_uncore_mmio_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_enable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578957600,
      "name": "snr_uncore_mmio_enable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4432",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578957600,
      "name": "snr_uncore_mmio_enable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box * box, struct perf_event * event)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
