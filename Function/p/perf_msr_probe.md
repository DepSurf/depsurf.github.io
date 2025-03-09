# Function: <code>perf_msr_probe</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```

```json
{
  "name": "perf_msr_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578879488,
      "name": "perf_msr_probe",
      "external": true,
      "loc": "arch/x86/events/probe.c:14",
      "file": "arch/x86/events/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/msr.c:msr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578879488,
      "name": "perf_msr_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```

```json
{
  "name": "perf_msr_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578880256,
      "name": "perf_msr_probe",
      "external": true,
      "loc": "arch/x86/events/probe.c:14",
      "file": "arch/x86/events/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/msr.c:msr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578880256,
      "name": "perf_msr_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```

```json
{
  "name": "perf_msr_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578884720,
      "name": "perf_msr_probe",
      "external": true,
      "loc": "arch/x86/events/probe.c:19",
      "file": "arch/x86/events/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/msr.c:msr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578884720,
      "name": "perf_msr_probe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071578884960,
      "name": "perf_msr_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```

```json
{
  "name": "perf_msr_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578880240,
      "name": "perf_msr_probe",
      "external": true,
      "loc": "arch/x86/events/probe.c:19",
      "file": "arch/x86/events/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/msr.c:msr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578880240,
      "name": "perf_msr_probe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071578880480,
      "name": "perf_msr_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```

```json
{
  "name": "perf_msr_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578882688,
      "name": "perf_msr_probe",
      "external": true,
      "loc": "arch/x86/events/probe.c:19",
      "file": "arch/x86/events/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/msr.c:msr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578882688,
      "name": "perf_msr_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```

```json
{
  "name": "perf_msr_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_msr_probe",
      "external": true,
      "loc": "arch/x86/events/probe.c:19",
      "file": "arch/x86/events/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/msr.c:msr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592039507,
      "name": "perf_msr_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071578886544,
      "name": "perf_msr_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```

```json
{
  "name": "perf_msr_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_msr_probe",
      "external": true,
      "loc": "arch/x86/events/probe.c:19",
      "file": "arch/x86/events/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/msr.c:msr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593805567,
      "name": "perf_msr_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071578884288,
      "name": "perf_msr_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```

```json
{
  "name": "perf_msr_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_msr_probe",
      "external": true,
      "loc": "arch/x86/events/probe.c:19",
      "file": "arch/x86/events/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/msr.c:msr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595951110,
      "name": "perf_msr_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071578889632,
      "name": "perf_msr_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```

```json
{
  "name": "perf_msr_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_msr_probe",
      "external": true,
      "loc": "arch/x86/events/probe.c:19",
      "file": "arch/x86/events/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/msr.c:msr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596468315,
      "name": "perf_msr_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071578887568,
      "name": "perf_msr_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```

```json
{
  "name": "perf_msr_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578910208,
      "name": "perf_msr_probe",
      "external": true,
      "loc": "arch/x86/events/probe.c:19",
      "file": "arch/x86/events/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/msr.c:msr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578909872,
      "name": "perf_msr_probe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    },
    {
      "addr": 18446744071597363351,
      "name": "perf_msr_probe.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071578910208,
      "name": "perf_msr_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```

```json
{
  "name": "perf_msr_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578880256,
      "name": "perf_msr_probe",
      "external": true,
      "loc": "arch/x86/events/probe.c:14",
      "file": "arch/x86/events/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/msr.c:msr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578880256,
      "name": "perf_msr_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```

```json
{
  "name": "perf_msr_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578874128,
      "name": "perf_msr_probe",
      "external": true,
      "loc": "arch/x86/events/probe.c:14",
      "file": "arch/x86/events/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/msr.c:msr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578874128,
      "name": "perf_msr_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```

```json
{
  "name": "perf_msr_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578880192,
      "name": "perf_msr_probe",
      "external": true,
      "loc": "arch/x86/events/probe.c:14",
      "file": "arch/x86/events/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/msr.c:msr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578880192,
      "name": "perf_msr_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```

```json
{
  "name": "perf_msr_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578880544,
      "name": "perf_msr_probe",
      "external": true,
      "loc": "arch/x86/events/probe.c:14",
      "file": "arch/x86/events/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/msr.c:msr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578880544,
      "name": "perf_msr_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
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
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr * msr, int cnt, bool zero, void * data)
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
