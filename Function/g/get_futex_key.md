# Function: <code>get_futex_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, int rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892256,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:468",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_wake",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892256,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 663
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, int rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579923904,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:489",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579923904,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1023
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, int rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579954560,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:498",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954560,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1068
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, int rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959328,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:500",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959328,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, int rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580006208,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:500",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006208,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 940
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, int rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580058208,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:500",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058208,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 963
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580105536,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:508",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105536,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 965
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580150448,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:523",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150448,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 941
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580198224,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:572",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580198224,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 943
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580266640,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:504",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580266640,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 913
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
int get_futex_key(u32 * uaddr, bool fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580250544,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:485",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580250544,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 949
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
int get_futex_key(u32 * uaddr, bool fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580255712,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:484",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255712,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
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
int get_futex_key(u32 * uaddr, bool fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580407024,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:542",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580407024,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 953
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
int get_futex_key(u32 * uaddr, bool fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580624272,
      "name": "get_futex_key",
      "external": true,
      "loc": "kernel/futex/core.c:220",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/requeue.c:futex_wait_requeue_pi",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/waitwake.c:futex_wait_setup",
        "kernel/futex/waitwake.c:futex_wait_multiple_setup",
        "kernel/futex/waitwake.c:futex_wake_op",
        "kernel/futex/waitwake.c:futex_wake_op",
        "kernel/futex/waitwake.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580624272,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1563
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
int get_futex_key(u32 * uaddr, bool fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580890160,
      "name": "get_futex_key",
      "external": true,
      "loc": "kernel/futex/core.c:220",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/requeue.c:futex_wait_requeue_pi",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/waitwake.c:futex_wait_setup",
        "kernel/futex/waitwake.c:futex_wait_multiple_setup",
        "kernel/futex/waitwake.c:futex_wake_op",
        "kernel/futex/waitwake.c:futex_wake_op",
        "kernel/futex/waitwake.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580890160,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1563
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
int get_futex_key(u32 * uaddr, bool fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580974000,
      "name": "get_futex_key",
      "external": true,
      "loc": "kernel/futex/core.c:220",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/requeue.c:futex_wait_requeue_pi",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/waitwake.c:futex_wait_setup",
        "kernel/futex/waitwake.c:futex_wait_multiple_setup",
        "kernel/futex/waitwake.c:futex_wake_op",
        "kernel/futex/waitwake.c:futex_wake_op",
        "kernel/futex/waitwake.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974000,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1589
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
int get_futex_key(u32 * uaddr, unsigned int flags, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068736,
      "name": "get_futex_key",
      "external": true,
      "loc": "kernel/futex/core.c:221",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/requeue.c:futex_wait_requeue_pi",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/waitwake.c:futex_wait_setup",
        "kernel/futex/waitwake.c:futex_wait_multiple_setup",
        "kernel/futex/waitwake.c:futex_wake_op",
        "kernel/futex/waitwake.c:futex_wake_op",
        "kernel/futex/waitwake.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068736,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491432376,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:572",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491432376,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1048
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225425764,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:572",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225425764,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1064
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284379088,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:572",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284379088,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1600
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271894328,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:572",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271894328,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580167024,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:572",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167024,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 943
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580114640,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:572",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580114640,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 943
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580158496,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:572",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158496,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 943
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
int get_futex_key(u32 * uaddr, int fshared, union futex_key * key, enum futex_access rw)
```

```json
{
  "name": "get_futex_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580212352,
      "name": "get_futex_key",
      "external": false,
      "loc": "kernel/futex.c:572",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212352,
      "name": "get_futex_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 938
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int rw</code> ➡️ <code>enum futex_access rw</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int fshared</code> ➡️ <code>bool fshared</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool fshared</code>
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
