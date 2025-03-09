# Function: <code>cpu_stop_queue_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580024576,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:84",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu",
        "kernel/stop_machine.c:stop_one_cpu_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580024576,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580057168,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:80",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057168,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580097248,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:75",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097248,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580102832,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:75",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102832,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580155488,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:75",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155488,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580215120,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:77",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215120,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580267584,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:77",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267584,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580318416,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:76",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580318416,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580367248,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:77",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580367248,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580440640,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:77",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580440640,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580428624,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:93",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580428624,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580433056,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:93",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433056,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:93",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597312,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071592162189,
      "name": "cpu_stop_queue_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:93",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800608,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    },
    {
      "addr": 18446744071593935403,
      "name": "cpu_stop_queue_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:93",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085856,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    },
    {
      "addr": 18446744071596000609,
      "name": "cpu_stop_queue_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:93",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581177712,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    },
    {
      "addr": 18446744071596519102,
      "name": "cpu_stop_queue_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:93",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581283392,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    },
    {
      "addr": 18446744071597419452,
      "name": "cpu_stop_queue_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491631048,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:77",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491631048,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225583948,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:77",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225583948,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284623408,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:77",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284623408,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272027924,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:77",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272027924,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580336048,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:77",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336048,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580283312,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:77",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580283312,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580327296,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:77",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580327296,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
bool cpu_stop_queue_work(unsigned int cpu, struct cpu_stop_work * work)
```

```json
{
  "name": "cpu_stop_queue_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580382368,
      "name": "cpu_stop_queue_work",
      "external": false,
      "loc": "kernel/stop_machine.c:77",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:queue_stop_cpus_work",
        "kernel/stop_machine.c:stop_one_cpu_nowait",
        "kernel/stop_machine.c:stop_one_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580382368,
      "name": "cpu_stop_queue_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
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
