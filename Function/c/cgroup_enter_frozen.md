# Function: <code>cgroup_enter_frozen</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580279424,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580279424,
      "name": "cgroup_enter_frozen",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580327536,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580327536,
      "name": "cgroup_enter_frozen",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580400096,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:wait_for_vfork_done",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580400096,
      "name": "cgroup_enter_frozen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580387376,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:wait_for_vfork_done",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580387376,
      "name": "cgroup_enter_frozen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580390304,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580390304,
      "name": "cgroup_enter_frozen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580552368,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580552368,
      "name": "cgroup_enter_frozen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580751024,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580751024,
      "name": "cgroup_enter_frozen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581028448,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028448,
      "name": "cgroup_enter_frozen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581116816,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581116816,
      "name": "cgroup_enter_frozen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581215056,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581215056,
      "name": "cgroup_enter_frozen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491587352,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491587352,
      "name": "cgroup_enter_frozen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225547520,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225547520,
      "name": "cgroup_enter_frozen",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284569120,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284569120,
      "name": "cgroup_enter_frozen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271994996,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271994996,
      "name": "cgroup_enter_frozen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580296336,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580296336,
      "name": "cgroup_enter_frozen",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580243696,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243696,
      "name": "cgroup_enter_frozen",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580287584,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287584,
      "name": "cgroup_enter_frozen",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void cgroup_enter_frozen()
```

```json
{
  "name": "cgroup_enter_frozen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580341712,
      "name": "cgroup_enter_frozen",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:107",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580341712,
      "name": "cgroup_enter_frozen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void cgroup_enter_frozen()
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
