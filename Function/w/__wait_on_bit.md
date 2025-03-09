# Function: <code>__wait_on_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __wait_on_bit(wait_queue_head_t * wq, struct wait_bit_queue * q, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587366720,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait.c:387",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:out_of_line_wait_on_bit",
        "kernel/sched/wait.c:out_of_line_wait_on_bit_timeout",
        "mm/filemap.c:wait_on_page_bit",
        "mm/filemap.c:wait_on_page_bit_killable_timeout",
        "mm/filemap.c:wait_on_page_bit_killable",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587366720,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int __wait_on_bit(wait_queue_head_t * wq, struct wait_bit_queue * q, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587867552,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait.c:387",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait.c:out_of_line_wait_on_bit",
        "mm/filemap.c:wait_on_page_bit_killable_timeout",
        "mm/filemap.c:wait_on_page_bit_killable",
        "mm/filemap.c:wait_on_page_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587867552,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int __wait_on_bit(wait_queue_head_t * wq, struct wait_bit_queue * q, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588082096,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait.c:375",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588082096,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588308896,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:43",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588308896,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588874256,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:43",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588874256,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589253072,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:40",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589253072,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589495296,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:40",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589495296,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589956064,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589956064,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590183728,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590183728,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591201968,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591201968,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591697056,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591697056,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591639568,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591639568,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592813520,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592813520,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594716144,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594716144,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596463456,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596463456,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597005280,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597005280,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597934624,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/build_utility.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597934624,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503927056,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503927056,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236536884,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236536884,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297774928,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297774928,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279795660,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279795660,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589786016,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589786016,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589508560,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589508560,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590229424,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590229424,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __wait_on_bit(struct wait_queue_head * wq_head, struct wait_bit_queue_entry * wbq_entry, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "__wait_on_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590280016,
      "name": "__wait_on_bit",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:41",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout",
        "kernel/sched/wait_bit.c:out_of_line_wait_on_bit",
        "fs/fs-writeback.c:__inode_wait_for_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590280016,
      "name": "__wait_on_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
