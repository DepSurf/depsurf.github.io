# Function: <code>x86_pmu_disable_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578876224,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:754",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578888048,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:754",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578876224,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071578888048,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578876816,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:763",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578891243,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:763",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578876816,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071578888448,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578876832,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:766",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578891453,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:766",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578876832,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071578888512,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578876144,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:771",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578890173,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:771",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578876144,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071578887536,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578877296,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:781",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578895885,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:781",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578877296,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071578895024,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578879232,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:784",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578897773,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:784",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578879232,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071578896896,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578878944,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/amd/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578898713,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578878944,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071578896992,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578881109,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:839",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900849,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:839",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578899104,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578881909,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:868",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578902293,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:868",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578900240,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578887781,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:877",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578909045,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:877",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578975007,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:877",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578905232,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578883301,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1008",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578904665,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1008",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977727,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1008",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578902112,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578885797,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1131",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578906781,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1131",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578986831,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1131",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578903680,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578890165,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1131",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578910269,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1131",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579002847,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1131",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578905712,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578889605,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1157",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578915869,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1157",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579019539,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1157",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578911424,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578897397,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1165",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578930301,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1165",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579047155,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1165",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578927088,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578895285,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1170",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578928349,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1170",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579047155,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1170",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578925136,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578917781,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1185",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578949277,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1185",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579072483,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1185",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578947296,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578881909,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:868",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578902293,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:868",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578900240,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578877157,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:868",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578896679,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:868",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578894800,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578881845,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:868",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578902229,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:868",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578900176,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```

```json
{
  "name": "x86_pmu_disable_event",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578882197,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:868",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578902693,
      "name": "x86_pmu_disable_event",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:868",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578900640,
      "name": "x86_pmu_disable_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void x86_pmu_disable_event(struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void x86_pmu_disable_event(struct perf_event * event)
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
