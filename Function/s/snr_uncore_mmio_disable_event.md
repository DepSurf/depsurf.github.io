# Function: <code>snr_uncore_mmio_disable_event</code>

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
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578954704,
      "name": "snr_uncore_mmio_disable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4468",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578954704,
      "name": "snr_uncore_mmio_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578957136,
      "name": "snr_uncore_mmio_disable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4444",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578957136,
      "name": "snr_uncore_mmio_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578963008,
      "name": "snr_uncore_mmio_disable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4487",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578963008,
      "name": "snr_uncore_mmio_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578971953,
      "name": "snr_uncore_mmio_disable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4740",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578971888,
      "name": "snr_uncore_mmio_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071591241325,
      "name": "snr_uncore_mmio_disable_event.cold",
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
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578977197,
      "name": "snr_uncore_mmio_disable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4765",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578977136,
      "name": "snr_uncore_mmio_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071591184480,
      "name": "snr_uncore_mmio_disable_event.cold",
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
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578991620,
      "name": "snr_uncore_mmio_disable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4923",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578991520,
      "name": "snr_uncore_mmio_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071592045926,
      "name": "snr_uncore_mmio_disable_event.cold",
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
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579007817,
      "name": "snr_uncore_mmio_disable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4923",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579007712,
      "name": "snr_uncore_mmio_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071593812407,
      "name": "snr_uncore_mmio_disable_event.cold",
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
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579032245,
      "name": "snr_uncore_mmio_disable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:5179",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579032144,
      "name": "snr_uncore_mmio_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071595955995,
      "name": "snr_uncore_mmio_disable_event.cold",
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
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579033141,
      "name": "snr_uncore_mmio_disable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:5169",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033040,
      "name": "snr_uncore_mmio_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071596473345,
      "name": "snr_uncore_mmio_disable_event.cold",
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
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579057765,
      "name": "snr_uncore_mmio_disable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:5177",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579057664,
      "name": "snr_uncore_mmio_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071597368687,
      "name": "snr_uncore_mmio_disable_event.cold",
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
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578957136,
      "name": "snr_uncore_mmio_disable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4444",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578957136,
      "name": "snr_uncore_mmio_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578954656,
      "name": "snr_uncore_mmio_disable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4444",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578954656,
      "name": "snr_uncore_mmio_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578957072,
      "name": "snr_uncore_mmio_disable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4444",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578957072,
      "name": "snr_uncore_mmio_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "snr_uncore_mmio_disable_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578957648,
      "name": "snr_uncore_mmio_disable_event",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:4444",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578957648,
      "name": "snr_uncore_mmio_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
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
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void snr_uncore_mmio_disable_event(struct intel_uncore_box * box, struct perf_event * event)
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
