# Function: <code>rcu_qs</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579964662,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:953",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_check_callbacks",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_check_callbacks",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962704,
      "name": "rcu_qs.part.44",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_qs()
```

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580002256,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:811",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002256,
      "name": "rcu_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void rcu_qs()
```

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580052448,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:797",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052448,
      "name": "rcu_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void rcu_qs()
```

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580122197,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:786",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_softirq_qs",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110384,
      "name": "rcu_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void rcu_qs()
```

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580103861,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:814",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_softirq_qs",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092624,
      "name": "rcu_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void rcu_qs()
```

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580106709,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:881",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_softirq_qs",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094400,
      "name": "rcu_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void rcu_qs()
```

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580247381,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:841",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_softirq_qs",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580233072,
      "name": "rcu_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580409061,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:284",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_flavor_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_flavor_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_softirq_qs",
        "kernel/rcu/tree.c:rcu_softirq_qs"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580640853,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:284",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_softirq_qs",
        "kernel/rcu/tree.c:rcu_softirq_qs"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580708997,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:286",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_softirq_qs",
        "kernel/rcu/tree.c:rcu_softirq_qs"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580775845,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:286",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_softirq_qs",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void rcu_qs()
```

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491260792,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:797",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491260792,
      "name": "rcu_qs",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void rcu_qs()
```

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225264380,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:797",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225264380,
      "name": "rcu_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void rcu_qs()
```

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284156704,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:797",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284156704,
      "name": "rcu_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void rcu_qs()
```

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271783708,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:797",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271783708,
      "name": "rcu_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_qs()
```

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580021184,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:797",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021184,
      "name": "rcu_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void rcu_qs()
```

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579962320,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:797",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962320,
      "name": "rcu_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void rcu_qs()
```

```json
{
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580012720,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:797",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012720,
      "name": "rcu_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
  "name": "rcu_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580062302,
      "name": "rcu_qs",
      "external": false,
      "loc": "kernel/rcu/tree_plugin.h:259",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580060384,
      "name": "rcu_qs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void rcu_qs()
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void rcu_qs()
```
</details>
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
void rcu_qs()
```
</details>
</li>
</ul>
