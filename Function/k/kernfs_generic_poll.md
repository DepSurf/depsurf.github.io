# Function: <code>kernfs_generic_poll</code>

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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441648,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:834",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_poll",
        "fs/kernfs/file.c:kernfs_fop_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441648,
      "name": "kernfs_generic_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582540400,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:834",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_poll",
        "fs/kernfs/file.c:kernfs_fop_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582540400,
      "name": "kernfs_generic_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582846576,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:834",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_poll",
        "fs/kernfs/file.c:kernfs_fop_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582846576,
      "name": "kernfs_generic_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582919296,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:815",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_poll",
        "fs/kernfs/file.c:kernfs_fop_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582919296,
      "name": "kernfs_generic_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582946960,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:815",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_poll",
        "fs/kernfs/file.c:kernfs_fop_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582946960,
      "name": "kernfs_generic_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583282176,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:815",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_poll",
        "fs/kernfs/file.c:kernfs_fop_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583282176,
      "name": "kernfs_generic_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583786640,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:815",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_poll",
        "fs/kernfs/file.c:kernfs_fop_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583786640,
      "name": "kernfs_generic_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584405336,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:876",
      "file": "fs/kernfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_fop_poll"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584406016,
      "name": "kernfs_generic_poll",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584633851,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:876",
      "file": "fs/kernfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_fop_poll"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_trigger_poll",
        "kernel/cgroup/cgroup.c:cgroup_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584634560,
      "name": "kernfs_generic_poll",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584865963,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:827",
      "file": "fs/kernfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_fop_poll"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_trigger_poll",
        "kernel/cgroup/cgroup.c:cgroup_file_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584866672,
      "name": "kernfs_generic_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494177152,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:834",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_poll",
        "fs/kernfs/file.c:kernfs_fop_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494177152,
      "name": "kernfs_generic_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227614724,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:834",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_poll",
        "fs/kernfs/file.c:kernfs_fop_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227614724,
      "name": "kernfs_generic_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287863184,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:834",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_poll",
        "fs/kernfs/file.c:kernfs_fop_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287863184,
      "name": "kernfs_generic_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273643136,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:834",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_poll",
        "fs/kernfs/file.c:kernfs_fop_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273643136,
      "name": "kernfs_generic_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582509136,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:834",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_poll",
        "fs/kernfs/file.c:kernfs_fop_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582509136,
      "name": "kernfs_generic_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582446304,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:834",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_poll",
        "fs/kernfs/file.c:kernfs_fop_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582446304,
      "name": "kernfs_generic_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582499616,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:834",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_poll",
        "fs/kernfs/file.c:kernfs_fop_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582499616,
      "name": "kernfs_generic_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
```

```json
{
  "name": "kernfs_generic_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582580224,
      "name": "kernfs_generic_poll",
      "external": true,
      "loc": "fs/kernfs/file.c:834",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_poll",
        "fs/kernfs/file.c:kernfs_fop_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582580224,
      "name": "kernfs_generic_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
__poll_t kernfs_generic_poll(struct kernfs_open_file * of, poll_table * wait)
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
