# Function: <code>tp_rcu_cond_sync</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tp_rcu_cond_sync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580588391,
      "name": "tp_rcu_cond_sync",
      "external": false,
      "loc": "kernel/tracepoint.c:57",
      "file": "kernel/tracepoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/tracepoint.c:tracepoint_add_func"
      ],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tp_rcu_cond_sync(enum tp_transition_sync sync)
```

```json
{
  "name": "tp_rcu_cond_sync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580758037,
      "name": "tp_rcu_cond_sync",
      "external": false,
      "loc": "kernel/tracepoint.c:57",
      "file": "kernel/tracepoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757984,
      "name": "tp_rcu_cond_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071592165387,
      "name": "tp_rcu_cond_sync.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tp_rcu_cond_sync(enum tp_transition_sync sync)
```

```json
{
  "name": "tp_rcu_cond_sync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580973635,
      "name": "tp_rcu_cond_sync",
      "external": false,
      "loc": "kernel/tracepoint.c:57",
      "file": "kernel/tracepoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580973568,
      "name": "tp_rcu_cond_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071593938773,
      "name": "tp_rcu_cond_sync.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tp_rcu_cond_sync(enum tp_transition_sync sync)
```

```json
{
  "name": "tp_rcu_cond_sync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581269635,
      "name": "tp_rcu_cond_sync",
      "external": false,
      "loc": "kernel/tracepoint.c:57",
      "file": "kernel/tracepoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269568,
      "name": "tp_rcu_cond_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071596001864,
      "name": "tp_rcu_cond_sync.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tp_rcu_cond_sync(enum tp_transition_sync sync)
```

```json
{
  "name": "tp_rcu_cond_sync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581364787,
      "name": "tp_rcu_cond_sync",
      "external": false,
      "loc": "kernel/tracepoint.c:57",
      "file": "kernel/tracepoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581364720,
      "name": "tp_rcu_cond_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071596520425,
      "name": "tp_rcu_cond_sync.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tp_rcu_cond_sync(enum tp_transition_sync sync)
```

```json
{
  "name": "tp_rcu_cond_sync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581471171,
      "name": "tp_rcu_cond_sync",
      "external": false,
      "loc": "kernel/tracepoint.c:57",
      "file": "kernel/tracepoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471104,
      "name": "tp_rcu_cond_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071597420810,
      "name": "tp_rcu_cond_sync.cold",
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void tp_rcu_cond_sync(enum tp_transition_sync sync)
```
</details>
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
