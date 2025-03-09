# Function: <code>call_srcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct * sp, struct callback_head * head, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579777696,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcu.c:387",
      "file": "kernel/rcu/srcu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_notifier.c:mmu_notifier_call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777696,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void call_srcu(struct srcu_struct * sp, struct callback_head * head, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803056,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcu.c:387",
      "file": "kernel/rcu/srcu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_notifier.c:mmu_notifier_call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803056,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void call_srcu(struct srcu_struct * sp, struct callback_head * head, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579831424,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcu.c:387",
      "file": "kernel/rcu/srcu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_notifier.c:mmu_notifier_call_srcu",
        "drivers/base/core.c:__device_link_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831424,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void call_srcu(struct srcu_struct * sp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579836736,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:870",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_notifier.c:mmu_notifier_call_srcu",
        "drivers/base/core.c:__device_link_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836736,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void call_srcu(struct srcu_struct * sp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579877040,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:871",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_notifier.c:mmu_notifier_call_srcu",
        "drivers/base/core.c:__device_link_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877040,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void call_srcu(struct srcu_struct * sp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579911056,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:901",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_notifier.c:mmu_notifier_call_srcu",
        "drivers/base/core.c:__device_link_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911056,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579958736,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:919",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_call_srcu",
        "drivers/base/core.c:__device_link_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958736,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579995280,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:894",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_call_srcu",
        "drivers/base/core.c:__device_link_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995280,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580045408,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:895",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put",
        "drivers/base/core.c:__device_link_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045408,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580101248,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:908",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put",
        "drivers/base/core.c:__device_link_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580101248,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082784,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:897",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put",
        "drivers/base/core.c:devlink_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082784,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580084144,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:911",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084144,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220592,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:903",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220592,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580381168,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:1188",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580381168,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580607904,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:1257",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580607904,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580681600,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:1331",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580681600,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580748384,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:1351",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580748384,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491251288,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:895",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put",
        "drivers/base/core.c:__device_link_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491251288,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225261076,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:895",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put",
        "drivers/base/core.c:__device_link_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225261076,
      "name": "call_srcu",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284150480,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:895",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put",
        "drivers/base/core.c:__device_link_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284150480,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271776060,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:895",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put",
        "drivers/base/core.c:__device_link_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271776060,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014144,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:895",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put",
        "drivers/base/core.c:__device_link_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014144,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952880,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:895",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put",
        "drivers/base/core.c:__device_link_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952880,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580005680,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:895",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put",
        "drivers/base/core.c:__device_link_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005680,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void call_srcu(struct srcu_struct * ssp, struct callback_head * rhp, rcu_callback_t func)
```

```json
{
  "name": "call_srcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054784,
      "name": "call_srcu",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:895",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/tracepoint.c:rcu_free_old_probes",
        "mm/mmu_notifier.c:mmu_notifier_put",
        "drivers/base/core.c:__device_link_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054784,
      "name": "call_srcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct callback_head * rhp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct callback_head * head</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct srcu_struct * ssp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct srcu_struct * sp</code>
</li>
</ul>
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
