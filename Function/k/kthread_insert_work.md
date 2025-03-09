# Function: <code>kthread_insert_work</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579537184,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:764",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn",
        "kernel/kthread.c:kthread_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537184,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579524272,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:770",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn",
        "kernel/kthread.c:kthread_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524272,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579550336,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:777",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn",
        "kernel/kthread.c:kthread_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550336,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579577296,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:795",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn",
        "kernel/kthread.c:kthread_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577296,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579614800,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:797",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn",
        "kernel/kthread.c:kthread_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614800,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579639712,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:806",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn",
        "kernel/kthread.c:kthread_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579639712,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579665664,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:806",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn",
        "kernel/kthread.c:kthread_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665664,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579697808,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:842",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697808,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579675776,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:893",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675776,
      "name": "kthread_insert_work",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579682192,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:920",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579682192,
      "name": "kthread_insert_work",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579761264,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:920",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761264,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579869888,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:980",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579869888,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580012656,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:981",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012656,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580066192,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:982",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066192,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108832,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:999",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_worker",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108832,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490840848,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:806",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn",
        "kernel/kthread.c:kthread_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490840848,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224871240,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:806",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn",
        "kernel/kthread.c:kthread_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224871240,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283678432,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:806",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn",
        "kernel/kthread.c:kthread_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283678432,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271511142,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:806",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn",
        "kernel/kthread.c:kthread_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271511142,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579641984,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:806",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn",
        "kernel/kthread.c:kthread_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641984,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579570384,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:806",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn",
        "kernel/kthread.c:kthread_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570384,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579639248,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:806",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn",
        "kernel/kthread.c:kthread_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579639248,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
```

```json
{
  "name": "kthread_insert_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579673520,
      "name": "kthread_insert_work",
      "external": false,
      "loc": "kernel/kthread.c:806",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_flush_work",
        "kernel/kthread.c:__kthread_queue_delayed_work",
        "kernel/kthread.c:kthread_delayed_work_timer_fn",
        "kernel/kthread.c:kthread_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673520,
      "name": "kthread_insert_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void kthread_insert_work(struct kthread_worker * worker, struct kthread_work * work, struct list_head * pos)
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
