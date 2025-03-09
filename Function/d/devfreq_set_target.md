# Function: <code>devfreq_set_target</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587738912,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:288",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587738912,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:288",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588042368,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    },
    {
      "addr": 18446744071588051361,
      "name": "devfreq_set_target.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:289",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:update_devfreq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588248416,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    },
    {
      "addr": 18446744071588257409,
      "name": "devfreq_set_target.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:342",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:update_devfreq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589132096,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071589137226,
      "name": "devfreq_set_target.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:349",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_update_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589131216,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
    },
    {
      "addr": 18446744071591621737,
      "name": "devfreq_set_target.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:350",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_update_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589020944,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    },
    {
      "addr": 18446744071591565102,
      "name": "devfreq_set_target.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:350",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_update_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589736544,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071592686231,
      "name": "devfreq_set_target.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:347",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_resume_device",
        "drivers/devfreq/devfreq.c:devfreq_suspend_device",
        "drivers/devfreq/devfreq.c:devfreq_update_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591239456,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071594570591,
      "name": "devfreq_set_target.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592991520,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:347",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_resume_device",
        "drivers/devfreq/devfreq.c:devfreq_suspend_device",
        "drivers/devfreq/devfreq.c:devfreq_update_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592991520,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593442976,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:347",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_resume_device",
        "drivers/devfreq/devfreq.c:devfreq_suspend_device",
        "drivers/devfreq/devfreq.c:devfreq_update_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593442976,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594189456,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:347",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_resume_device",
        "drivers/devfreq/devfreq.c:devfreq_suspend_device",
        "drivers/devfreq/devfreq.c:devfreq_update_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594189456,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501706488,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:289",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:update_devfreq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501706488,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234230916,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:289",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:update_devfreq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234230916,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295145984,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:289",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:update_devfreq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295145984,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278124106,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:289",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:update_devfreq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278124106,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:289",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:update_devfreq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587860112,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    },
    {
      "addr": 18446744071587869105,
      "name": "devfreq_set_target.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:289",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:update_devfreq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587586912,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    },
    {
      "addr": 18446744071587595905,
      "name": "devfreq_set_target.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:289",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:update_devfreq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588185472,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    },
    {
      "addr": 18446744071588194465,
      "name": "devfreq_set_target.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
```

```json
{
  "name": "devfreq_set_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devfreq_set_target",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:289",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:update_devfreq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588320752,
      "name": "devfreq_set_target",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    },
    {
      "addr": 18446744071588329761,
      "name": "devfreq_set_target.cold",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int devfreq_set_target(struct devfreq * devfreq, long unsigned int new_freq, u32 flags)
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
