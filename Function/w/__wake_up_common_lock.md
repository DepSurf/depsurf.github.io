# Function: <code>__wake_up_common_lock</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700560,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:113",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700560,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579734688,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:107",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579734688,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774368,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:109",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774368,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802016,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:110",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802016,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579849584,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:110",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849584,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888272,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:110",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888272,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882512,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:125",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882512,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579891664,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:125",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891664,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580006592,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:125",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_pollfree",
        "kernel/sched/wait.c:__wake_up_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006592,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580138320,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:124",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:poll_timer_fn",
        "kernel/sched/build_utility.c:update_triggers",
        "kernel/sched/build_utility.c:__wake_up_pollfree",
        "kernel/sched/build_utility.c:__wake_up_sync",
        "kernel/sched/build_utility.c:wake_up_var",
        "kernel/sched/build_utility.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138320,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580313056,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:124",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:poll_timer_fn",
        "kernel/sched/build_utility.c:update_triggers",
        "kernel/sched/build_utility.c:__wake_up_sync",
        "kernel/sched/build_utility.c:wake_up_var",
        "kernel/sched/build_utility.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580313056,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
int __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580379728,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:124",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:poll_timer_fn",
        "kernel/sched/build_utility.c:update_triggers",
        "kernel/sched/build_utility.c:__wake_up_pollfree",
        "kernel/sched/build_utility.c:__wake_up_sync",
        "kernel/sched/build_utility.c:wake_up_var",
        "kernel/sched/build_utility.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379728,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580528955,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:99",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:poll_timer_fn",
        "kernel/sched/build_utility.c:update_triggers",
        "kernel/sched/build_utility.c:__wake_up_pollfree",
        "kernel/sched/build_utility.c:__wake_up_sync",
        "kernel/sched/build_utility.c:__wake_up_on_current_cpu",
        "kernel/sched/build_utility.c:wake_up_var",
        "kernel/sched/build_utility.c:wake_up_bit"
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491042224,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:110",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491042224,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225049560,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:110",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225049560,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283919344,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:110",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283919344,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271640864,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:110",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271640864,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579821936,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:110",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821936,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756544,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:110",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756544,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579809952,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:110",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809952,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855104,
      "name": "__wake_up_common_lock",
      "external": false,
      "loc": "kernel/sched/wait.c:110",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855104,
      "name": "__wake_up_common_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int __wake_up_common_lock(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
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
