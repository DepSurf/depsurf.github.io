# Function: <code>calc_load_n</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579570061,
      "name": "calc_load_n",
      "external": false,
      "loc": "kernel/sched/loadavg.c:290",
      "file": "kernel/sched/loadavg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579580400,
      "name": "calc_load_n",
      "external": false,
      "loc": "kernel/sched/loadavg.c:293",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580400,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579606576,
      "name": "calc_load_n",
      "external": false,
      "loc": "kernel/sched/loadavg.c:293",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579606576,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579584144,
      "name": "calc_load_n",
      "external": false,
      "loc": "kernel/sched/loadavg.c:294",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584144,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579613536,
      "name": "calc_load_n",
      "external": false,
      "loc": "kernel/sched/loadavg.c:295",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613536,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643952,
      "name": "calc_load_n",
      "external": false,
      "loc": "kernel/sched/loadavg.c:291",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643952,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579681632,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:157",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/psi.c:update_stats",
        "kernel/sched/psi.c:update_stats",
        "kernel/sched/psi.c:update_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579681632,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579715488,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:157",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715488,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579757984,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:157",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579757984,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791296,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:157",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_nohz",
        "kernel/sched/loadavg.c:calc_global_nohz",
        "kernel/sched/loadavg.c:calc_global_nohz",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791296,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579782144,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:157",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_nohz",
        "kernel/sched/loadavg.c:calc_global_nohz",
        "kernel/sched/loadavg.c:calc_global_nohz",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782144,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579790272,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:157",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790272,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579885968,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:157",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579885968,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580189376,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:156",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:calc_global_load",
        "kernel/sched/build_utility.c:calc_global_load",
        "kernel/sched/build_utility.c:calc_global_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580189376,
      "name": "calc_load_n",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580379776,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:156",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:calc_global_load",
        "kernel/sched/build_utility.c:calc_global_load",
        "kernel/sched/build_utility.c:calc_global_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379776,
      "name": "calc_load_n",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580448448,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:156",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:calc_global_load",
        "kernel/sched/build_utility.c:calc_global_load",
        "kernel/sched/build_utility.c:calc_global_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580448448,
      "name": "calc_load_n",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580507776,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:156",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:calc_global_load",
        "kernel/sched/build_utility.c:calc_global_load",
        "kernel/sched/build_utility.c:calc_global_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507776,
      "name": "calc_load_n",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490936416,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:157",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490936416,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224954880,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:157",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224954880,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283792336,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:157",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283792336,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271569032,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:157",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271569032,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579733904,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:157",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733904,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579662736,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:157",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662736,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718352,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:157",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718352,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
```

```json
{
  "name": "calc_load_n",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579765632,
      "name": "calc_load_n",
      "external": true,
      "loc": "kernel/sched/loadavg.c:157",
      "file": "kernel/sched/loadavg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765632,
      "name": "calc_load_n",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n)
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
