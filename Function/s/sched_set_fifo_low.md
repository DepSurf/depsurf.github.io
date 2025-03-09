# Function: <code>sched_set_fifo_low</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_set_fifo_low(struct task_struct * p)
```

```json
{
  "name": "sched_set_fifo_low",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579757776,
      "name": "sched_set_fifo_low",
      "external": true,
      "loc": "kernel/sched/core.c:6124",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_worker",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579757776,
      "name": "sched_set_fifo_low",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_set_fifo_low(struct task_struct * p)
```

```json
{
  "name": "sched_set_fifo_low",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579764800,
      "name": "sched_set_fifo_low",
      "external": true,
      "loc": "kernel/sched/core.c:6425",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_worker",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764800,
      "name": "sched_set_fifo_low",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void sched_set_fifo_low(struct task_struct * p)
```

```json
{
  "name": "sched_set_fifo_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851200,
      "name": "sched_set_fifo_low",
      "external": true,
      "loc": "kernel/sched/core.c:7589",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_poll_worker",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851200,
      "name": "sched_set_fifo_low",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void sched_set_fifo_low(struct task_struct * p)
```

```json
{
  "name": "sched_set_fifo_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579968768,
      "name": "sched_set_fifo_low",
      "external": true,
      "loc": "kernel/sched/core.c:7697",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_poll_worker",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579968768,
      "name": "sched_set_fifo_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void sched_set_fifo_low(struct task_struct * p)
```

```json
{
  "name": "sched_set_fifo_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128656,
      "name": "sched_set_fifo_low",
      "external": true,
      "loc": "kernel/sched/core.c:7839",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_poll_worker",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128656,
      "name": "sched_set_fifo_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void sched_set_fifo_low(struct task_struct * p)
```

```json
{
  "name": "sched_set_fifo_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580190720,
      "name": "sched_set_fifo_low",
      "external": true,
      "loc": "kernel/sched/core.c:7948",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_rtpoll_worker",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190720,
      "name": "sched_set_fifo_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void sched_set_fifo_low(struct task_struct * p)
```

```json
{
  "name": "sched_set_fifo_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580237856,
      "name": "sched_set_fifo_low",
      "external": true,
      "loc": "kernel/sched/core.c:8009",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_rtpoll_worker",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580237856,
      "name": "sched_set_fifo_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void sched_set_fifo_low(struct task_struct * p)
```
</details>
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
