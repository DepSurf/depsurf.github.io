# Function: <code>kthread_mod_delayed_work</code>

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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579541744,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1022",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541744,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528400,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1027",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528400,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579554880,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1032",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554880,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579582896,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1050",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582896,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579620096,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1052",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579620096,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644352,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1062",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644352,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579666976,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1062",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666976,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698448,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1098",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698448,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579676464,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1152",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676464,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579682880,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1190",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579682880,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579761968,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1190",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761968,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579871264,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1250",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871264,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014176,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1250",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014176,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067712,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1251",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067712,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580110352,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1268",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110352,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490846832,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1062",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490846832,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224872952,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1062",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224872952,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283680720,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1062",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283680720,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271511922,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1062",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271511922,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643296,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1062",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643296,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571680,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1062",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571680,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579640560,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1062",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640560,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_mod_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674800,
      "name": "kthread_mod_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1062",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_schedule_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674800,
      "name": "kthread_mod_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
bool kthread_mod_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
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
