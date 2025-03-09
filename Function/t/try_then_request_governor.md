# Function: <code>try_then_request_governor</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587745088,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:233",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587745088,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:233",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588043712,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071588051435,
      "name": "try_then_request_governor.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588254792,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:234",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588254688,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071588257825,
      "name": "try_then_request_governor.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589130883,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:287",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130832,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071589136976,
      "name": "try_then_request_governor.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589129843,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:294",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589129792,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071591621460,
      "name": "try_then_request_governor.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589019603,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:295",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589019552,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071591564825,
      "name": "try_then_request_governor.cold",
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
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589735347,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:295",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589735296,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071592685954,
      "name": "try_then_request_governor.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591247937,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:292",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591247872,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071594571293,
      "name": "try_then_request_governor.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593006216,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:292",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:governor_store"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593001264,
      "name": "try_then_request_governor.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    },
    {
      "addr": 18446744071593001472,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593457736,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:292",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:governor_store"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593452736,
      "name": "try_then_request_governor.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    },
    {
      "addr": 18446744071593452944,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594204680,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:292",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:governor_store"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594199408,
      "name": "try_then_request_governor.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    },
    {
      "addr": 18446744071594199616,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501708232,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:234",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501708232,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234237708,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:234",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234237708,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295157136,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:234",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295157136,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278130386,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:234",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278130386,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587866488,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:234",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587866384,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071587869521,
      "name": "try_then_request_governor.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587593288,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:234",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587593184,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071587596321,
      "name": "try_then_request_governor.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588191848,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:234",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588191744,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071588194881,
      "name": "try_then_request_governor.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devfreq_governor * try_then_request_governor(const char * name)
```

```json
{
  "name": "try_then_request_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588327144,
      "name": "try_then_request_governor",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:234",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:governor_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588327040,
      "name": "try_then_request_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071588330177,
      "name": "try_then_request_governor.cold",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct devfreq_governor * try_then_request_governor(const char * name)
```
</details>
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
