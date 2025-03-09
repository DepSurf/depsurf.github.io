# Function: <code>kblockd_mod_delayed_work_on</code>

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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583177056,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:3196",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583177056,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583351968,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:3420",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583351968,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583561536,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:3571",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583561536,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583683008,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1677",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583683008,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583871840,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1628",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871840,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583974736,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1669",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974736,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584361872,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1760",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list",
        "block/blk-mq.c:blk_mq_add_to_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584361872,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584478880,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1654",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list",
        "block/blk-mq.c:blk_mq_add_to_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584478880,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584513600,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1646",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list",
        "block/blk-mq.c:blk_mq_add_to_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584513600,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584924816,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1632",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list",
        "block/blk-mq.c:blk_mq_add_to_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584924816,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585628752,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1097",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list",
        "block/blk-mq.c:blk_mq_add_to_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585628752,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586396448,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1035",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list",
        "block/blk-mq.c:blk_mq_add_to_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586396448,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586643264,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1034",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list",
        "block/blk-mq.c:blk_mq_requeue_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586643264,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586914224,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1069",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list",
        "block/blk-mq.c:blk_mq_requeue_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586914224,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495794520,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1669",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495794520,
      "name": "kblockd_mod_delayed_work_on",
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229150176,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1669",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229150176,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289982480,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1669",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list",
        "block/blk-mq.c:blk_mq_add_to_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289982480,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274939018,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1669",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274939018,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583943472,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1669",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583943472,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583880416,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1669",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583880416,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583927232,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1669",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927232,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "kblockd_mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584028624,
      "name": "kblockd_mod_delayed_work_on",
      "external": true,
      "loc": "block/blk-core.c:1669",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028624,
      "name": "kblockd_mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work * dwork, long unsigned int delay)
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
