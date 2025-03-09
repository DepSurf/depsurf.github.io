# Function: <code>drop_futex_key_refs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579892928,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:431",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_wake",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892928,
      "name": "drop_futex_key_refs.isra.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579921968,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:449",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579921968,
      "name": "drop_futex_key_refs.isra.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579952624,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:458",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952624,
      "name": "drop_futex_key_refs.isra.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579958944,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:460",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958944,
      "name": "drop_futex_key_refs.isra.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580004768,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:460",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580004768,
      "name": "drop_futex_key_refs.isra.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580057392,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:460",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057392,
      "name": "drop_futex_key_refs.isra.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580104560,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:463",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580104560,
      "name": "drop_futex_key_refs.isra.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580149536,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:447",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149536,
      "name": "drop_futex_key_refs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580197536,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:453",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580197536,
      "name": "drop_futex_key_refs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491428480,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:453",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491428480,
      "name": "drop_futex_key_refs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void drop_futex_key_refs(union futex_key * key)
```

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225423044,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:453",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225423044,
      "name": "drop_futex_key_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284375968,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:453",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284375968,
      "name": "drop_futex_key_refs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271893806,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:453",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271893806,
      "name": "drop_futex_key_refs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580166336,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:453",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166336,
      "name": "drop_futex_key_refs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580113952,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:453",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580113952,
      "name": "drop_futex_key_refs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580157808,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:453",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580157808,
      "name": "drop_futex_key_refs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "drop_futex_key_refs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580210464,
      "name": "drop_futex_key_refs",
      "external": false,
      "loc": "kernel/futex.c:453",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:futex_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580210464,
      "name": "drop_futex_key_refs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void drop_futex_key_refs(union futex_key * key)
```
</details>
</li>
</ul>
