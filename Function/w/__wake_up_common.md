# Function: <code>__wake_up_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __wake_up_common(wait_queue_head_t * q, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644672,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:65",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:abort_exclusive_wait",
        "kernel/sched/wait.c:__wake_up_sync_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644672,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void __wake_up_common(wait_queue_head_t * q, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579659408,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:65",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:abort_exclusive_wait",
        "kernel/sched/wait.c:__wake_up_sync_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659408,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void __wake_up_common(wait_queue_head_t * q, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683952,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:65",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync_key",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683952,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579669808,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:66",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_sync_key",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669808,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700256,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:72",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700256,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579734368,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:65",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579734368,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774048,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:65",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774048,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579801696,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:66",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801696,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579849264,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:66",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849264,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579887952,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:66",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_sync_key",
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887952,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882192,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:81",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_sync_key",
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882192,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579891344,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:81",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_sync_key",
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891344,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580006272,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:81",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_sync_key",
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006272,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580137984,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:80",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:__wake_up_locked_sync_key",
        "kernel/sched/build_utility.c:__wake_up_locked_key_bookmark",
        "kernel/sched/build_utility.c:__wake_up_locked_key",
        "kernel/sched/build_utility.c:__wake_up_locked",
        "kernel/sched/build_utility.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580137984,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580312704,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:80",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:__wake_up_locked_sync_key",
        "kernel/sched/build_utility.c:__wake_up_locked_key_bookmark",
        "kernel/sched/build_utility.c:__wake_up_locked_key",
        "kernel/sched/build_utility.c:__wake_up_locked",
        "kernel/sched/build_utility.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580312704,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580379376,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:80",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:__wake_up_locked_sync_key",
        "kernel/sched/build_utility.c:__wake_up_locked_key_bookmark",
        "kernel/sched/build_utility.c:__wake_up_locked_key",
        "kernel/sched/build_utility.c:__wake_up_locked",
        "kernel/sched/build_utility.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379376,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580437360,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:73",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:poll_timer_fn",
        "kernel/sched/build_utility.c:update_triggers",
        "kernel/sched/build_utility.c:__wake_up_pollfree",
        "kernel/sched/build_utility.c:__wake_up_sync",
        "kernel/sched/build_utility.c:__wake_up_locked_sync_key",
        "kernel/sched/build_utility.c:__wake_up_locked_key",
        "kernel/sched/build_utility.c:__wake_up_locked",
        "kernel/sched/build_utility.c:__wake_up_on_current_cpu",
        "kernel/sched/build_utility.c:wake_up_var",
        "kernel/sched/build_utility.c:wake_up_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580437360,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491040336,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:66",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491040336,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225049192,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:66",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225049192,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283918784,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:66",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283918784,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271640598,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:66",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271640598,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579821616,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:66",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821616,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756224,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:66",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756224,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579809632,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:66",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809632,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int __wake_up_common(struct wait_queue_head * wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void * key, wait_queue_entry_t * bookmark)
```

```json
{
  "name": "__wake_up_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579854784,
      "name": "__wake_up_common",
      "external": false,
      "loc": "kernel/sched/wait.c:66",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/wait.c:__wake_up_locked_key_bookmark",
        "kernel/sched/wait.c:__wake_up_locked_key",
        "kernel/sched/wait.c:__wake_up_locked",
        "kernel/sched/wait.c:__wake_up_common_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579854784,
      "name": "__wake_up_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
<b>Param removed. </b>
<code>wait_queue_head_t * q</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>wait_queue_entry_t * bookmark</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>wait_queue_entry_t * bookmark</code>
</li>
</ul>
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
