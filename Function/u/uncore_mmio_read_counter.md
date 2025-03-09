# Function: <code>uncore_mmio_read_counter</code>

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
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_mmio_read_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578939760,
      "name": "uncore_mmio_read_counter",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:129",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578939760,
      "name": "uncore_mmio_read_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_mmio_read_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578942240,
      "name": "uncore_mmio_read_counter",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:129",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942240,
      "name": "uncore_mmio_read_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_mmio_read_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578949328,
      "name": "uncore_mmio_read_counter",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:129",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578949328,
      "name": "uncore_mmio_read_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_mmio_read_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_mmio_read_counter",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:131",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591241170,
      "name": "uncore_mmio_read_counter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071578950928,
      "name": "uncore_mmio_read_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_mmio_read_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_mmio_read_counter",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:148",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591184324,
      "name": "uncore_mmio_read_counter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071578955920,
      "name": "uncore_mmio_read_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_mmio_read_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_mmio_read_counter",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:148",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592044614,
      "name": "uncore_mmio_read_counter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071578966464,
      "name": "uncore_mmio_read_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_mmio_read_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_mmio_read_counter",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:148",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593811197,
      "name": "uncore_mmio_read_counter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071578977248,
      "name": "uncore_mmio_read_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_mmio_read_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_mmio_read_counter",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:148",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595955008,
      "name": "uncore_mmio_read_counter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071578995936,
      "name": "uncore_mmio_read_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_mmio_read_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_mmio_read_counter",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:163",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596472178,
      "name": "uncore_mmio_read_counter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071578995680,
      "name": "uncore_mmio_read_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_mmio_read_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_mmio_read_counter",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:163",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597367520,
      "name": "uncore_mmio_read_counter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579020608,
      "name": "uncore_mmio_read_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_mmio_read_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578942240,
      "name": "uncore_mmio_read_counter",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:129",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942240,
      "name": "uncore_mmio_read_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_mmio_read_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578939248,
      "name": "uncore_mmio_read_counter",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:129",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578939248,
      "name": "uncore_mmio_read_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_mmio_read_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578942176,
      "name": "uncore_mmio_read_counter",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:129",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942176,
      "name": "uncore_mmio_read_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```

```json
{
  "name": "uncore_mmio_read_counter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578942752,
      "name": "uncore_mmio_read_counter",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:129",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942752,
      "name": "uncore_mmio_read_counter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
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
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box * box, struct perf_event * event)
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
