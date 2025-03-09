# Function: <code>rcu_momentary_dyntick_idle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788544,
      "name": "rcu_momentary_dyntick_idle",
      "external": false,
      "loc": "kernel/rcu/tree.c:304",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:force_qs_rnp",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_check_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788544,
      "name": "rcu_momentary_dyntick_idle",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579806864,
      "name": "rcu_momentary_dyntick_idle",
      "external": false,
      "loc": "kernel/rcu/tree.c:299",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_all_qs",
        "kernel/rcu/tree.c:rcu_note_context_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579806864,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579836512,
      "name": "rcu_momentary_dyntick_idle",
      "external": false,
      "loc": "kernel/rcu/tree.c:300",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_all_qs",
        "kernel/rcu/tree.c:rcu_note_context_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836512,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579846609,
      "name": "rcu_momentary_dyntick_idle",
      "external": false,
      "loc": "kernel/rcu/tree.c:445",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_note_context_switch"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579887271,
      "name": "rcu_momentary_dyntick_idle",
      "external": false,
      "loc": "kernel/rcu/tree.c:442",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_note_context_switch"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579916183,
      "name": "rcu_momentary_dyntick_idle",
      "external": false,
      "loc": "kernel/rcu/tree.c:429",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_note_context_switch"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959600,
      "name": "rcu_momentary_dyntick_idle",
      "external": false,
      "loc": "kernel/rcu/tree.c:371",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959600,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579998912,
      "name": "rcu_momentary_dyntick_idle",
      "external": false,
      "loc": "kernel/rcu/tree.c:366",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998912,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048976,
      "name": "rcu_momentary_dyntick_idle",
      "external": false,
      "loc": "kernel/rcu/tree.c:367",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048976,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580104512,
      "name": "rcu_momentary_dyntick_idle",
      "external": true,
      "loc": "kernel/rcu/tree.c:407",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/stop_machine.c:multi_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580104512,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580085744,
      "name": "rcu_momentary_dyntick_idle",
      "external": true,
      "loc": "kernel/rcu/tree.c:420",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/stop_machine.c:multi_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085744,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580087376,
      "name": "rcu_momentary_dyntick_idle",
      "external": true,
      "loc": "kernel/rcu/tree.c:426",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/stop_machine.c:multi_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580087376,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580233387,
      "name": "rcu_momentary_dyntick_idle",
      "external": true,
      "loc": "kernel/rcu/tree.c:402",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_note_context_switch"
      ],
      "caller_func": [
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/stop_machine.c:multi_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580224000,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580403856,
      "name": "rcu_momentary_dyntick_idle",
      "external": true,
      "loc": "kernel/rcu/tree.c:413",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/stop_machine.c:multi_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580403856,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580642336,
      "name": "rcu_momentary_dyntick_idle",
      "external": true,
      "loc": "kernel/rcu/tree.c:344",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/stop_machine.c:multi_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580642336,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580710480,
      "name": "rcu_momentary_dyntick_idle",
      "external": true,
      "loc": "kernel/rcu/tree.c:325",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/stop_machine.c:multi_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580710480,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580777328,
      "name": "rcu_momentary_dyntick_idle",
      "external": true,
      "loc": "kernel/rcu/tree.c:326",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:nocb_cb_wait",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/stop_machine.c:multi_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580777328,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491256192,
      "name": "rcu_momentary_dyntick_idle",
      "external": false,
      "loc": "kernel/rcu/tree.c:367",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491256192,
      "name": "rcu_momentary_dyntick_idle",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225272384,
      "name": "rcu_momentary_dyntick_idle",
      "external": false,
      "loc": "kernel/rcu/tree.c:367",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225272384,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284157184,
      "name": "rcu_momentary_dyntick_idle",
      "external": false,
      "loc": "kernel/rcu/tree.c:367",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284157184,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271781874,
      "name": "rcu_momentary_dyntick_idle",
      "external": false,
      "loc": "kernel/rcu/tree.c:367",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271781874,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580017712,
      "name": "rcu_momentary_dyntick_idle",
      "external": false,
      "loc": "kernel/rcu/tree.c:367",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580017712,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579956448,
      "name": "rcu_momentary_dyntick_idle",
      "external": false,
      "loc": "kernel/rcu/tree.c:367",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nocb_cb_kthread",
        "kernel/rcu/tree.c:rcu_note_context_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956448,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void rcu_momentary_dyntick_idle()
```

```json
{
  "name": "rcu_momentary_dyntick_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009248,
      "name": "rcu_momentary_dyntick_idle",
      "external": false,
      "loc": "kernel/rcu/tree.c:367",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009248,
      "name": "rcu_momentary_dyntick_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
void rcu_momentary_dyntick_idle()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void rcu_momentary_dyntick_idle()
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➖</summary>

```c
void rcu_momentary_dyntick_idle()
```
</details>
</li>
</ul>
