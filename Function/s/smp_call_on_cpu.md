# Function: <code>smp_call_on_cpu</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579969664,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:765",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579969664,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579975024,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:776",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975024,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580021552,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:778",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021552,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580075616,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:780",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075616,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122928,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:787",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122928,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580168384,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:800",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580168384,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580216320,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:800",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580216320,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580283488,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:859",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580283488,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580267008,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:996",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267008,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580272016,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:1212",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580272016,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580423856,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:1220",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580423856,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580646592,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:1237",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:__lockup_detector_reconfigure",
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646592,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580913504,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:1238",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:__lockup_detector_reconfigure",
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580913504,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580998672,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:1086",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:__lockup_detector_reconfigure",
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580998672,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581094816,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:1106",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:__lockup_detector_reconfigure",
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094816,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491453280,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:800",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491453280,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225440852,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:800",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225440852,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284405168,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:800",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284405168,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271912522,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:800",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271912522,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580185120,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:800",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580185120,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580132608,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:800",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132608,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580176592,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:800",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580176592,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```

```json
{
  "name": "smp_call_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580228784,
      "name": "smp_call_on_cpu",
      "external": true,
      "loc": "kernel/smp.c:800",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure",
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580228784,
      "name": "smp_call_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*)(void *) func, void * par, bool phys)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
