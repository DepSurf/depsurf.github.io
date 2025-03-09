# Function: <code>mem_cgroup_scan_tasks</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581159024,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:938",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581159024,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581206768,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:908",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206768,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581337104,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:922",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581337104,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581485024,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:893",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485024,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570800,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1067",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570800,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581682240,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1203",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581682240,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581754640,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1214",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581754640,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974432,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1175",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974432,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582023632,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1300",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023632,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582050112,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1127",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582050112,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582356832,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1182",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582356832,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582848272,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1162",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582848272,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583394160,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1242",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583394160,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
void mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583613440,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1267",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583613440,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583808336,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1318",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:out_of_memory",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583808336,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493208176,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1214",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493208176,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226838880,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1214",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226838880,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286716528,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1214",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286716528,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272985512,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1214",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272985512,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581723376,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1214",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581723376,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581662176,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1214",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581662176,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581714688,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1214",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714688,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```

```json
{
  "name": "mem_cgroup_scan_tasks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581782240,
      "name": "mem_cgroup_scan_tasks",
      "external": true,
      "loc": "mm/memcontrol.c:1214",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581782240,
      "name": "mem_cgroup_scan_tasks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup * memcg, int (*)(struct task_struct *, void *) fn, void * arg)
```
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
