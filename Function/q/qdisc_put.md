# Function: <code>qdisc_put</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588245664,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:994",
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
        "net/sched/cls_api.c:tcf_block_release",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588245664,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588636608,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:986",
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
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_block_release",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588636608,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588858976,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:981",
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
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_block_release",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588858976,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589743920,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:978",
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
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589743920,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589776992,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:965",
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
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589776992,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589680752,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:1009",
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
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589680752,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590437360,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:1035",
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
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590437360,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592041488,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:1077",
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
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592041488,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593858992,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:1073",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:attach_default_qdiscs",
        "net/sched/sch_generic.c:qdisc_create_dflt",
        "net/sched/sch_mq.c:mq_attach",
        "net/sched/sch_mq.c:mq_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593858992,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594233856,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:1081",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:attach_default_qdiscs",
        "net/sched/sch_generic.c:qdisc_create_dflt",
        "net/sched/sch_mq.c:mq_attach",
        "net/sched/sch_mq.c:mq_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594233856,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595031200,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:1085",
      "file": "net/sched/sch_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:dev_shutdown",
        "net/sched/sch_generic.c:attach_default_qdiscs",
        "net/sched/sch_generic.c:qdisc_create_dflt",
        "net/sched/sch_mq.c:mq_attach",
        "net/sched/sch_mq.c:mq_destroy",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595031200,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502444648,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:981",
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
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_block_release",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502444648,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235161216,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:981",
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
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_block_release",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235161216,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295996208,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:981",
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
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_block_release",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295996208,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278631914,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:981",
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
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_block_release",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278631914,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588465360,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:981",
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
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_block_release",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588465360,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588177360,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:981",
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
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_block_release",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588177360,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588797536,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:981",
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
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_block_release",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588797536,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void qdisc_put(struct Qdisc * qdisc)
```

```json
{
  "name": "qdisc_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588938192,
      "name": "qdisc_put",
      "external": true,
      "loc": "net/sched/sch_generic.c:981",
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
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_block_release",
        "net/sched/sch_fifo.c:fifo_create_dflt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588938192,
      "name": "qdisc_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void qdisc_put(struct Qdisc * qdisc)
```
</details>
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
