# Function: <code>__wait_on_bit_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __wait_on_bit_lock(wait_queue_head_t * wq, struct wait_bit_queue * q, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587367232,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait.c:425",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:out_of_line_wait_on_bit_lock",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:__lock_page_killable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587367232,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int __wait_on_bit_lock(wait_queue_head_t * wq, struct wait_bit_queue * q, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587868064,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait.c:425",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:out_of_line_wait_on_bit_lock",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587868064,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int __wait_on_bit_lock(wait_queue_head_t * wq, struct wait_bit_queue * q, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588082240,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait.c:413",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588082240,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588309408,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:81",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588309408,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588874768,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:81",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588874768,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589253584,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:81",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589253584,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589495808,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:81",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589495808,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589956592,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589956592,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590184256,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590184256,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591202496,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591202496,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591697584,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591697584,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591640096,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591640096,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592814048,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592814048,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594715712,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594715712,
      "name": "__wait_on_bit_lock",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596462992,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596462992,
      "name": "__wait_on_bit_lock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597004816,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597004816,
      "name": "__wait_on_bit_lock",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597934160,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597934160,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503927720,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503927720,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236537484,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236537484,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297775744,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297775744,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279796178,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279796178,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589786544,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589786544,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589509088,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589509088,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590229952,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590229952,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int __wait_on_bit_lock(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590280544,
      "name": "__wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:82",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590280544,
      "name": "__wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct wait_queue_head * wq_head</code>
</li>
<li>
<b>Param added. </b>
<code>struct wait_bit_queue_entry * wbq_entry</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_head_t * wq</code>
</li>
<li>
<b>Param removed. </b>
<code>struct wait_bit_queue * q</code>
</li>
</ul>
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
