# Function: <code>hash_futex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893024,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:379",
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
        "kernel/futex.c:exit_pi_state_list",
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893024,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579922064,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:387",
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
        "kernel/futex.c:futex_wake",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579922064,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952720,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:391",
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
        "kernel/futex.c:futex_wake",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952720,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959008,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:393",
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
        "kernel/futex.c:futex_wake",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959008,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580004832,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:393",
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
        "kernel/futex.c:futex_wake",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580004832,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580057456,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:393",
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
        "kernel/futex.c:futex_wake",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057456,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580104624,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:396",
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
        "kernel/futex.c:futex_wake",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580104624,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580149600,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:380",
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
        "kernel/futex.c:futex_wake",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149600,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580197584,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:386",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
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
      "addr": 18446744071580197584,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580265456,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:378",
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
        "kernel/futex.c:futex_wake",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580265456,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580249408,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:360",
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
        "kernel/futex.c:futex_wake",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580249408,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580254560,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:359",
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
        "kernel/futex.c:futex_wake",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580254560,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580405872,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:417",
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
        "kernel/futex.c:futex_wake",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580405872,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491427856,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:386",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
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
      "addr": 18446603336491427856,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225423968,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:386",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_cleanup",
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
      "addr": 3225423968,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284376112,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:386",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
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
      "addr": 13835058055284376112,
      "name": "hash_futex",
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271894026,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:386",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
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
      "addr": 18446743936271894026,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580166384,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:386",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
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
      "addr": 18446744071580166384,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580114000,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:386",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
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
      "addr": 18446744071580114000,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580157856,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:386",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
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
      "addr": 18446744071580157856,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct futex_hash_bucket * hash_futex(union futex_key * key)
```

```json
{
  "name": "hash_futex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580211648,
      "name": "hash_futex",
      "external": false,
      "loc": "kernel/futex.c:386",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_cleanup",
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
      "addr": 18446744071580211648,
      "name": "hash_futex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct futex_hash_bucket * hash_futex(union futex_key * key)
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
