# Function: <code>srcu_queue_delayed_work_on</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool srcu_queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579831168,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:446",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831168,
      "name": "srcu_queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
bool srcu_queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579871312,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:447",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871312,
      "name": "srcu_queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
bool srcu_queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579905488,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:478",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905488,
      "name": "srcu_queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
bool srcu_queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953088,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:486",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953088,
      "name": "srcu_queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void srcu_queue_delayed_work_on(struct srcu_data * sdp, long unsigned int delay)
```

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579991680,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:465",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991680,
      "name": "srcu_queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void srcu_queue_delayed_work_on(struct srcu_data * sdp, long unsigned int delay)
```

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580041792,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:465",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041792,
      "name": "srcu_queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580103092,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:478",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_end"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580084628,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:467",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_end"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580085285,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:470",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_end"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580221715,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:462",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_end"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580382647,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:693",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580609511,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:756",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580683241,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:804",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/rcu/srcutree.c:srcu_gp_end"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580750044,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:795",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/rcu/srcutree.c:srcu_gp_end"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void srcu_queue_delayed_work_on(struct srcu_data * sdp, long unsigned int delay)
```

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491243480,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:465",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491243480,
      "name": "srcu_queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void srcu_queue_delayed_work_on(struct srcu_data * sdp, long unsigned int delay)
```

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225256344,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:465",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225256344,
      "name": "srcu_queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void srcu_queue_delayed_work_on(struct srcu_data * sdp, long unsigned int delay)
```

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284145872,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:465",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284145872,
      "name": "srcu_queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void srcu_queue_delayed_work_on(struct srcu_data * sdp, long unsigned int delay)
```

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271772422,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:465",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271772422,
      "name": "srcu_queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void srcu_queue_delayed_work_on(struct srcu_data * sdp, long unsigned int delay)
```

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580010528,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:465",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010528,
      "name": "srcu_queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void srcu_queue_delayed_work_on(struct srcu_data * sdp, long unsigned int delay)
```

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579949280,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:465",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949280,
      "name": "srcu_queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void srcu_queue_delayed_work_on(struct srcu_data * sdp, long unsigned int delay)
```

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580002064,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:465",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002064,
      "name": "srcu_queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void srcu_queue_delayed_work_on(struct srcu_data * sdp, long unsigned int delay)
```

```json
{
  "name": "srcu_queue_delayed_work_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580049056,
      "name": "srcu_queue_delayed_work_on",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:465",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049056,
      "name": "srcu_queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
bool srcu_queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```
</details>
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
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct srcu_data * sdp</code>
</li>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>struct workqueue_struct * wq</code>
</li>
<li>
<b>Param removed. </b>
<code>struct delayed_work * dwork</code>
</li>
<li>
<b>Param reordered. </b>
<code>cpu, wq, dwork, delay</code> ➡️ <code>sdp, delay</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void srcu_queue_delayed_work_on(struct srcu_data * sdp, long unsigned int delay)
```
</details>
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
