# Function: <code>rq_attach_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579533760,
      "name": "rq_attach_root",
      "external": false,
      "loc": "kernel/sched/core.c:5833",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:sched_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533760,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544960,
      "name": "rq_attach_root",
      "external": false,
      "loc": "kernel/sched/core.c:5794",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544960,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579570192,
      "name": "rq_attach_root",
      "external": false,
      "loc": "kernel/sched/core.c:5832",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570192,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579677472,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:225",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579677472,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579708112,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:225",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579708112,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579740960,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:217",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740960,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579780720,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:411",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780720,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579809328,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:440",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809328,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579856848,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:440",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856848,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900432,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:438",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900432,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579895216,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:465",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895216,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579903824,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:465",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579903824,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580021424,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:465",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021424,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580193472,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:485",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/build_utility.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580193472,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580384208,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:485",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/build_utility.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580384208,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:487",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/build_utility.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596501466,
      "name": "rq_attach_root.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580452880,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:489",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/build_utility.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597399152,
      "name": "rq_attach_root.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580512496,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491053560,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:440",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491053560,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225058524,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:440",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225058524,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283930944,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:440",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283930944,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271648162,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:440",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271648162,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579829200,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:440",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579829200,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579763776,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:440",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763776,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579817216,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:440",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579817216,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void rq_attach_root(struct rq * rq, struct root_domain * rd)
```

```json
{
  "name": "rq_attach_root",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579862336,
      "name": "rq_attach_root",
      "external": true,
      "loc": "kernel/sched/topology.c:440",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/topology.c:cpu_attach_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579862336,
      "name": "rq_attach_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
