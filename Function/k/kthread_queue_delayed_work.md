# Function: <code>kthread_queue_delayed_work</code>

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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579541616,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:885",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541616,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528272,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:890",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528272,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579554752,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:895",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554752,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579582768,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:913",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582768,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579619968,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:915",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619968,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644224,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:925",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644224,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579666848,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:925",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666848,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698320,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:961",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698320,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579676336,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1015",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676336,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579682752,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1043",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579682752,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579761840,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1043",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761840,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579871136,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1103",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871136,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014032,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1103",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014032,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067568,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1104",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067568,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580110208,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:1121",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110208,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490843704,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:925",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490843704,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224872832,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:925",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224872832,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283680464,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:925",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283680464,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271511806,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:925",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271511806,
      "name": "kthread_queue_delayed_work",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643168,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:925",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643168,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571552,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:925",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571552,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579640432,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:925",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640432,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kthread_queue_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674672,
      "name": "kthread_queue_delayed_work",
      "external": true,
      "loc": "kernel/kthread.c:925",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ptp/ptp_clock.c:ptp_aux_kworker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674672,
      "name": "kthread_queue_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool kthread_queue_delayed_work(struct kthread_worker * worker, struct kthread_delayed_work * dwork, long unsigned int delay)
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
