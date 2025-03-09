# Function: <code>get_perf_callchain</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580517680,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:195",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/callchain.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580517680,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580581648,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:195",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/callchain.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580581648,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580612192,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:197",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/callchain.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580612192,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 663
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692976,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:197",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/callchain.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692976,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 685
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580824976,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:179",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824976,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580891728,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:179",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891728,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580989248,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:178",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580989248,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581043232,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:178",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581043232,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581222752,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:178",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222752,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581265440,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:180",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:__bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581265440,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581284144,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:180",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:__bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284144,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581528176,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:180",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:__bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581528176,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581876176,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:180",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:__bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581876176,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582304032,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:180",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:__bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582304032,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582504816,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:180",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:__bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504816,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582673360,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:180",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:__bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582673360,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492398560,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:178",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492398560,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226284004,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:178",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226284004,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285660720,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:178",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285660720,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 860
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272506390,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:178",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272506390,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 526
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581012080,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:178",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581012080,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580958208,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:178",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580958208,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003280,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:178",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003280,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
```

```json
{
  "name": "get_perf_callchain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581064480,
      "name": "get_perf_callchain",
      "external": true,
      "loc": "kernel/events/callchain.c:178",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/stackmap.c:bpf_get_stack",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/events/core.c:perf_callchain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581064480,
      "name": "get_perf_callchain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
struct perf_callchain_entry * get_perf_callchain(struct pt_regs * regs, u32 init_nr, bool kernel, bool user, u32 max_stack, bool crosstask, bool add_mark)
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
