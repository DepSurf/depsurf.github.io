# Function: <code>x86_add_exclusive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578869904,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:358",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_setup_perfctr",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578869904,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578870845,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:363",
      "file": "arch/x86/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_setup_perfctr"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_setup_perfctr",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578868176,
      "name": "x86_add_exclusive.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071578870592,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578870368,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:364",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_setup_perfctr",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870368,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578869776,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:365",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578869776,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578870672,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:365",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870672,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578872576,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:369",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_setup_perfctr",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578872576,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578872384,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:369",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578872384,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578872928,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:369",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578872928,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873072,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:369",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873072,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578877264,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:370",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578877264,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873344,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:402",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873344,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578875168,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:428",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578875168,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:428",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592038581,
      "name": "x86_add_exclusive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071578877296,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:430",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_bts_config",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593804702,
      "name": "x86_add_exclusive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071578874544,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:433",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_bts_config",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595950735,
      "name": "x86_add_exclusive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071578880800,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:433",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_bts_config",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596467988,
      "name": "x86_add_exclusive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071578878800,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:431",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_bts_config",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597363024,
      "name": "x86_add_exclusive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071578901104,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873072,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:369",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873072,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578866704,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:369",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578866704,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873008,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:369",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873008,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int x86_add_exclusive(unsigned int what)
```

```json
{
  "name": "x86_add_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873360,
      "name": "x86_add_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:369",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873360,
      "name": "x86_add_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int x86_add_exclusive(unsigned int what)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int x86_add_exclusive(unsigned int what)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int x86_add_exclusive(unsigned int what)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int x86_add_exclusive(unsigned int what)
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
