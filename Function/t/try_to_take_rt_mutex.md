# Function: <code>try_to_take_rt_mutex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579676272,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:766",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676272,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579695456,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:767",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579695456,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579722560,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:831",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579722560,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579718368,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:820",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718368,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579750800,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:808",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579750800,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579785280,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:808",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579785280,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579831760,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:808",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831760,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579866464,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:809",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866464,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579915088,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:807",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915088,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579959568,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:805",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959568,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579947712,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:805",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947712,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591648896,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:782",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock",
        "kernel/locking/rtmutex.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591648896,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
int try_to_take_rt_mutex(struct rt_mutex_base * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592822416,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:962",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex_api.c:__rt_mutex_start_proxy_lock",
        "kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex_api.c:rt_mutex_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592822416,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
int try_to_take_rt_mutex(struct rt_mutex_base * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594729936,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:971",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock",
        "kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex_api.c:rt_mutex_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594729936,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
int try_to_take_rt_mutex(struct rt_mutex_base * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596481696,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1009",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock",
        "kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex_api.c:rt_mutex_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596481696,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
int try_to_take_rt_mutex(struct rt_mutex_base * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597023232,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1064",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock",
        "kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex_api.c:rt_mutex_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597023232,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
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
int try_to_take_rt_mutex(struct rt_mutex_base * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597952576,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:1083",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock",
        "kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex_api.c:rt_mutex_trylock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597952576,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491118632,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:807",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491118632,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225119784,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:807",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225119784,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284009264,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:807",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284009264,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271693362,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:807",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271693362,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579887200,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:807",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887200,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579822176,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:807",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822176,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579875360,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:807",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579875360,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int try_to_take_rt_mutex(struct rt_mutex * lock, struct task_struct * task, struct rt_mutex_waiter * waiter)
```

```json
{
  "name": "try_to_take_rt_mutex",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579920880,
      "name": "try_to_take_rt_mutex",
      "external": false,
      "loc": "kernel/locking/rtmutex.c:807",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:__rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_futex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_slowlock",
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920880,
      "name": "try_to_take_rt_mutex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rt_mutex * lock</code> ➡️ <code>struct rt_mutex_base * lock</code>
</li>
</ul>
</details>
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
