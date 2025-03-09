# Function: <code>qdisc_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586451184,
      "name": "qdisc_destroy",
      "external": true,
      "loc": "net/sched/sch_generic.c:669",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_create_dflt",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_mq.c:mq_attach",
        "net/sched/sch_mq.c:mq_destroy",
        "net/sched/sch_api.c:notify_and_destroy",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586451184,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586897152,
      "name": "qdisc_destroy",
      "external": true,
      "loc": "net/sched/sch_generic.c:695",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:qdisc_create_dflt",
        "net/sched/sch_mq.c:mq_attach",
        "net/sched/sch_mq.c:mq_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:notify_and_destroy",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586897152,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587091328,
      "name": "qdisc_destroy",
      "external": true,
      "loc": "net/sched/sch_generic.c:699",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:qdisc_create_dflt",
        "net/sched/sch_mq.c:mq_attach",
        "net/sched/sch_mq.c:mq_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:notify_and_destroy",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587091328,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587219904,
      "name": "qdisc_destroy",
      "external": true,
      "loc": "net/sched/sch_generic.c:699",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:qdisc_create_dflt",
        "net/sched/sch_mq.c:mq_attach",
        "net/sched/sch_mq.c:mq_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:notify_and_destroy",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587219904,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587737552,
      "name": "qdisc_destroy",
      "external": true,
      "loc": "net/sched/sch_generic.c:727",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:qdisc_create_dflt",
        "net/sched/sch_mq.c:mq_attach",
        "net/sched/sch_mq.c:mq_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:notify_and_destroy",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587737552,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588074416,
      "name": "qdisc_destroy",
      "external": true,
      "loc": "net/sched/sch_generic.c:944",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:qdisc_create_dflt",
        "net/sched/sch_mq.c:mq_attach",
        "net/sched/sch_mq.c:mq_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:notify_and_destroy",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588074416,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588245360,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:962",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put_unlocked",
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588245360,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588636320,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:954",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put_unlocked",
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588636320,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588858688,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:949",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put_unlocked",
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588858688,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589743728,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:954",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put_unlocked",
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589743728,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589776816,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:941",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put_unlocked",
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589776816,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589680576,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:985",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put_unlocked",
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589680576,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590437184,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:1011",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put_unlocked",
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590437184,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592041280,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:1053",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592041280,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593858768,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:1049",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593858768,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594238976,
      "name": "qdisc_destroy",
      "external": true,
      "loc": "net/sched/sch_generic.c:1073",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594238976,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595036272,
      "name": "qdisc_destroy",
      "external": true,
      "loc": "net/sched/sch_generic.c:1077",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595036272,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502444336,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:949",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put_unlocked",
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502444336,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235160908,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:949",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put_unlocked",
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235160908,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295995760,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:949",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put_unlocked",
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295995760,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278631624,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:949",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put_unlocked",
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278631624,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588465072,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:949",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put_unlocked",
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588465072,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588177072,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:949",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put_unlocked",
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588177072,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588797248,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:949",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put_unlocked",
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588797248,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void qdisc_destroy(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588937904,
      "name": "qdisc_destroy",
      "external": false,
      "loc": "net/sched/sch_generic.c:949",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:qdisc_put_unlocked",
        "net/sched/sch_generic.c:qdisc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588937904,
      "name": "qdisc_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
