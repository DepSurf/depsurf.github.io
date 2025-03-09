# Function: <code>trace_event_trigger_enable_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580312493,
      "name": "trace_event_trigger_enable_disable",
      "external": false,
      "loc": "kernel/trace/trace_events_trigger.c:433",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580312800,
      "name": "trace_event_trigger_enable_disable.constprop.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580357343,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:445",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:hist_unreg_all",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580355168,
      "name": "trace_event_trigger_enable_disable.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071580356752,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580404303,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:445",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:hist_unreg_all",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580402128,
      "name": "trace_event_trigger_enable_disable.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071580403712,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580415678,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:446",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:hist_unreg_all",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580413584,
      "name": "trace_event_trigger_enable_disable.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071580415072,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580471233,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:446",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:hist_unreg_all",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger",
        "kernel/trace/trace_events_hist.c:hist_register_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469072,
      "name": "trace_event_trigger_enable_disable.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071580470624,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580531457,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:445",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580529120,
      "name": "trace_event_trigger_enable_disable.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071580530784,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580589153,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:434",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580586976,
      "name": "trace_event_trigger_enable_disable.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071580588640,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580646368,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:434",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580644144,
      "name": "trace_event_trigger_enable_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071580645856,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580693072,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:441",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580690848,
      "name": "trace_event_trigger_enable_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071580692560,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580798125,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:447",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580797952,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580786141,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:447",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580785968,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580791613,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:448",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791440,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580977485,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:460",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_eprobe.c:enable_trace_eprobe",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977312,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581220714,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:470",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_eprobe.c:enable_trace_eprobe",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581220496,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581539242,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:471",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_eprobe.c:enable_trace_eprobe",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581539008,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581658634,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:473",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_eprobe.c:enable_trace_eprobe",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581658400,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581774634,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:473",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_eprobe.c:enable_trace_eprobe",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774400,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492001568,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:441",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492001568,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225937092,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:441",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225934508,
      "name": "trace_event_trigger_enable_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 3225936500,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285133344,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:441",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285133344,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272267016,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:441",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272266504,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580661872,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:441",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580659648,
      "name": "trace_event_trigger_enable_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071580661360,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580608080,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:441",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605856,
      "name": "trace_event_trigger_enable_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071580607568,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580653120,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:441",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580650896,
      "name": "trace_event_trigger_enable_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071580652608,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```

```json
{
  "name": "trace_event_trigger_enable_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580710624,
      "name": "trace_event_trigger_enable_disable",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:441",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger"
      ],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger",
        "kernel/trace/trace_events_trigger.c:event_enable_register_trigger",
        "kernel/trace/trace_events_trigger.c:unregister_trigger",
        "kernel/trace/trace_events_trigger.c:register_trigger",
        "kernel/trace/trace_events_trigger.c:clear_event_triggers",
        "kernel/trace/trace_events_hist.c:hist_enable_unreg_all",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_unregister_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580708400,
      "name": "trace_event_trigger_enable_disable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071580710112,
      "name": "trace_event_trigger_enable_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file * file, int trigger_enable)
```
</details>
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
