# Function: <code>hardlockup_detector_perf_enable</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void hardlockup_detector_perf_enable()
```

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580270048,
      "name": "hardlockup_detector_perf_enable",
      "external": true,
      "loc": "kernel/watchdog_hld.c:189",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270048,
      "name": "hardlockup_detector_perf_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void hardlockup_detector_perf_enable()
```

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": true,
      "loc": "kernel/watchdog_hld.c:189",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580330750,
      "name": "hardlockup_detector_perf_enable.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580330320,
      "name": "hardlockup_detector_perf_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void hardlockup_detector_perf_enable()
```

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": true,
      "loc": "kernel/watchdog_hld.c:189",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580383989,
      "name": "hardlockup_detector_perf_enable.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580383584,
      "name": "hardlockup_detector_perf_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void hardlockup_detector_perf_enable()
```

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": true,
      "loc": "kernel/watchdog_hld.c:190",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580436827,
      "name": "hardlockup_detector_perf_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580436416,
      "name": "hardlockup_detector_perf_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void hardlockup_detector_perf_enable()
```

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": true,
      "loc": "kernel/watchdog_hld.c:190",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580485595,
      "name": "hardlockup_detector_perf_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580485184,
      "name": "hardlockup_detector_perf_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void hardlockup_detector_perf_enable()
```

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": true,
      "loc": "kernel/watchdog_hld.c:190",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580570502,
      "name": "hardlockup_detector_perf_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580570080,
      "name": "hardlockup_detector_perf_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void hardlockup_detector_perf_enable()
```

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": true,
      "loc": "kernel/watchdog_hld.c:190",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591317604,
      "name": "hardlockup_detector_perf_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580557776,
      "name": "hardlockup_detector_perf_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void hardlockup_detector_perf_enable()
```

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": true,
      "loc": "kernel/watchdog_hld.c:190",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591259732,
      "name": "hardlockup_detector_perf_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580561040,
      "name": "hardlockup_detector_perf_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void hardlockup_detector_perf_enable()
```

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": true,
      "loc": "kernel/watchdog_hld.c:190",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592165218,
      "name": "hardlockup_detector_perf_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580731072,
      "name": "hardlockup_detector_perf_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void hardlockup_detector_perf_enable()
```

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": true,
      "loc": "kernel/watchdog_hld.c:190",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593938448,
      "name": "hardlockup_detector_perf_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580943808,
      "name": "hardlockup_detector_perf_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void hardlockup_detector_perf_enable()
```

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237888,
      "name": "hardlockup_detector_perf_enable",
      "external": true,
      "loc": "kernel/watchdog_hld.c:190",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237888,
      "name": "hardlockup_detector_perf_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": false,
      "loc": "include/linux/nmi.h:109",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": false,
      "loc": "include/linux/nmi.h:109",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": false,
      "loc": "include/linux/nmi.h:109",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": false,
      "loc": "include/linux/nmi.h:109",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void hardlockup_detector_perf_enable()
```

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": true,
      "loc": "kernel/watchdog_hld.c:190",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580454395,
      "name": "hardlockup_detector_perf_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580453984,
      "name": "hardlockup_detector_perf_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void hardlockup_detector_perf_enable()
```

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": true,
      "loc": "kernel/watchdog_hld.c:190",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580401467,
      "name": "hardlockup_detector_perf_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580401056,
      "name": "hardlockup_detector_perf_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void hardlockup_detector_perf_enable()
```

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": true,
      "loc": "kernel/watchdog_hld.c:190",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580445643,
      "name": "hardlockup_detector_perf_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580445232,
      "name": "hardlockup_detector_perf_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void hardlockup_detector_perf_enable()
```

```json
{
  "name": "hardlockup_detector_perf_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hardlockup_detector_perf_enable",
      "external": true,
      "loc": "kernel/watchdog_hld.c:190",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580501275,
      "name": "hardlockup_detector_perf_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580500864,
      "name": "hardlockup_detector_perf_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void hardlockup_detector_perf_enable()
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void hardlockup_detector_perf_enable()
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void hardlockup_detector_perf_enable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void hardlockup_detector_perf_enable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void hardlockup_detector_perf_enable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void hardlockup_detector_perf_enable()
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
