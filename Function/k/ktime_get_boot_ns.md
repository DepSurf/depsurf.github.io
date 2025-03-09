# Function: <code>ktime_get_boot_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boot_ns()
```

```json
{
  "name": "ktime_get_boot_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579364148,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:219",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580391440,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:219",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580391440,
      "name": "ktime_get_boot_ns",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boot_ns()
```

```json
{
  "name": "ktime_get_boot_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579371529,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:235",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580459184,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:235",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580459184,
      "name": "ktime_get_boot_ns",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boot_ns()
```

```json
{
  "name": "ktime_get_boot_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579390169,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:235",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580521632,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:235",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521632,
      "name": "ktime_get_boot_ns",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boot_ns()
```

```json
{
  "name": "ktime_get_boot_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579377670,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:224",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580554224,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:224",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580554224,
      "name": "ktime_get_boot_ns",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boot_ns()
```

```json
{
  "name": "ktime_get_boot_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579404406,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:104",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580547576,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:104",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634992,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:104",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580634992,
      "name": "ktime_get_boot_ns",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boot_ns()
```

```json
{
  "name": "ktime_get_boot_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579420139,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:119",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580638851,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:119",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580761552,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:119",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761552,
      "name": "ktime_get_boot_ns",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_boot_ns()
```

```json
{
  "name": "ktime_get_boot_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579454054,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:134",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580695234,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:134",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580828368,
      "name": "ktime_get_boot_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:134",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828368,
      "name": "ktime_get_boot_ns",
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
u64 ktime_get_boot_ns()
```
</details>
</li>
</ul>
