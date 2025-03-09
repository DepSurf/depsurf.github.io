# Function: <code>klp_try_complete_transition</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579864608,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:352",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:__klp_disable_patch",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579864608,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908160,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:377",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:__klp_disable_patch",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908160,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579942368,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:365",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:__klp_disable_patch",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942368,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579989456,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:358",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:__klp_disable_patch",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579989456,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:388",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032790,
      "name": "klp_try_complete_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580031088,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:388",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083510,
      "name": "klp_try_complete_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580081808,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580141680,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:388",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:__klp_enable_patch",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141680,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580118912,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:388",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:__klp_enable_patch",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580118912,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:387",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591252647,
      "name": "klp_try_complete_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580122192,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:387",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592149302,
      "name": "klp_try_complete_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071580264864,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:384",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593921897,
      "name": "klp_try_complete_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580435072,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 779
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
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:384",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595992780,
      "name": "klp_try_complete_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580677408,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 806
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
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:451",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596511040,
      "name": "klp_try_complete_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580753920,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 811
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
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:451",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597409913,
      "name": "klp_try_complete_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580839040,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 811
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284207248,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:388",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284207248,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1156
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:388",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052246,
      "name": "klp_try_complete_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580050544,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:388",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579997558,
      "name": "klp_try_complete_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579995856,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:388",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580043782,
      "name": "klp_try_complete_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580042080,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
void klp_try_complete_transition()
```

```json
{
  "name": "klp_try_complete_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_try_complete_transition",
      "external": true,
      "loc": "kernel/livepatch/transition.c:388",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/transition.c:klp_transition_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094550,
      "name": "klp_try_complete_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580092864,
      "name": "klp_try_complete_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void klp_try_complete_transition()
```
</details>
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
void klp_try_complete_transition()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void klp_try_complete_transition()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void klp_try_complete_transition()
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
