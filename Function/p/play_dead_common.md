# Function: <code>play_dead_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579182912,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1532",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_play_dead",
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579182912,
      "name": "play_dead_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579183184,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1559",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_play_dead",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183184,
      "name": "play_dead_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579193696,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1587",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_play_dead",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579193696,
      "name": "play_dead_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579191936,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1593",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579191936,
      "name": "play_dead_common",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579207856,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1506",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579207744,
      "name": "play_dead_common",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579219221,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1562",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219120,
      "name": "play_dead_common",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579242901,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1563",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579242800,
      "name": "play_dead_common",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579256917,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1628",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256800,
      "name": "play_dead_common",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579258581,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1628",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258464,
      "name": "play_dead_common",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579284997,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1655",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579284880,
      "name": "play_dead_common",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579292325,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1649",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/kernel/sev-es.c:sev_es_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292160,
      "name": "play_dead_common",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579294997,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1650",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/kernel/sev.c:sev_es_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294880,
      "name": "play_dead_common",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579342117,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1657",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/kernel/sev.c:sev_es_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342000,
      "name": "play_dead_common",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579403056,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1722",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/kernel/sev.c:sev_es_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403056,
      "name": "play_dead_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579483600,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1722",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/kernel/sev.c:sev_es_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483600,
      "name": "play_dead_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579495696,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1612",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/kernel/sev.c:sev_es_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495696,
      "name": "play_dead_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525440,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1478",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/kernel/sev.c:sev_es_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525440,
      "name": "play_dead_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579257285,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1628",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579257168,
      "name": "play_dead_common",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579192485,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1628",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579192384,
      "name": "play_dead_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579258485,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1628",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258368,
      "name": "play_dead_common",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void play_dead_common()
```

```json
{
  "name": "play_dead_common",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579264085,
      "name": "play_dead_common",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1628",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579263968,
      "name": "play_dead_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void play_dead_common()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void play_dead_common()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void play_dead_common()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void play_dead_common()
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
