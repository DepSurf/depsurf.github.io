# Function: <code>ktime_get_boottime_ns</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579472411,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580766800,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580923328,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923328,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579498515,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580817781,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977520,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977520,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579527460,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580943106,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581144048,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144048,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579509761,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:161",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580940120,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:161",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581184096,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:161",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184096,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579513022,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580942595,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581202464,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581202464,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579584591,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146662,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581442112,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581442112,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579675969,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421846,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581783344,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581783344,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579796182,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771235,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582209104,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209104,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579844405,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933469,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582409120,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409120,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579882231,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:163",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060051,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:163",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582577344,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:163",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582577344,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490630832,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492140992,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492326248,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492326248,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224709280,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3226037204,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 3226218288,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226218288,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283450400,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285347312,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285572528,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285572528,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271386296,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272303652,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272451112,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272451112,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579472179,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580786581,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580946320,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580946320,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579401091,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580732757,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580892384,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580892384,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579472099,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580777829,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580937568,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580937568,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boottime_ns()
```

```json
{
  "name": "ktime_get_boottime_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579503900,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580836101,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580999152,
      "name": "ktime_get_boottime_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580999152,
      "name": "ktime_get_boottime_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
u64 ktime_get_boottime_ns()
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
