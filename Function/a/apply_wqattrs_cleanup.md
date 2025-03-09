# Function: <code>apply_wqattrs_cleanup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx * ctx)
```

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579473680,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3488",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:workqueue_set_unbound_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579473680,
      "name": "apply_wqattrs_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx * ctx)
```

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579487392,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3589",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487392,
      "name": "apply_wqattrs_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx * ctx)
```

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579515168,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3617",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515168,
      "name": "apply_wqattrs_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579511444,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3622",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495952,
      "name": "apply_wqattrs_cleanup.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579538372,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3633",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579522640,
      "name": "apply_wqattrs_cleanup.part.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx * ctx)
```

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579550448,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3706",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550448,
      "name": "apply_wqattrs_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx * ctx)
```

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579587024,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3729",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587024,
      "name": "apply_wqattrs_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579625315,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3870",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611104,
      "name": "apply_wqattrs_cleanup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579651347,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3879",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636288,
      "name": "apply_wqattrs_cleanup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579678719,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3888",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_apply_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_apply_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672864,
      "name": "apply_wqattrs_cleanup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579658543,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3901",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_apply_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_apply_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579652688,
      "name": "apply_wqattrs_cleanup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579669343,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3908",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659088,
      "name": "apply_wqattrs_cleanup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579746395,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3947",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736160,
      "name": "apply_wqattrs_cleanup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579850650,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3930",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834704,
      "name": "apply_wqattrs_cleanup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579991187,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3937",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979648,
      "name": "apply_wqattrs_cleanup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580044899,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:4265",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028752,
      "name": "apply_wqattrs_cleanup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580080665,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:4319",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_apply_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_apply_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073216,
      "name": "apply_wqattrs_cleanup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490824164,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3879",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490807760,
      "name": "apply_wqattrs_cleanup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx * ctx)
```

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224839400,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3879",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224839400,
      "name": "apply_wqattrs_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283658884,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3879",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283636688,
      "name": "apply_wqattrs_cleanup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx * ctx)
```

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271485920,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3879",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271485920,
      "name": "apply_wqattrs_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579627651,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3879",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612592,
      "name": "apply_wqattrs_cleanup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579556003,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3879",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541616,
      "name": "apply_wqattrs_cleanup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579624931,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3879",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579609872,
      "name": "apply_wqattrs_cleanup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "apply_wqattrs_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579658579,
      "name": "apply_wqattrs_cleanup",
      "external": false,
      "loc": "kernel/workqueue.c:3879",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_set_unbound_cpumask",
        "kernel/workqueue.c:apply_workqueue_attrs_locked",
        "kernel/workqueue.c:apply_wqattrs_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645360,
      "name": "apply_wqattrs_cleanup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx * ctx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx * ctx)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx * ctx)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx * ctx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void apply_wqattrs_cleanup(struct apply_wqattrs_ctx * ctx)
```
</details>
</li>
</ul>
