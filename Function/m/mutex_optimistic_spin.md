# Function: <code>mutex_optimistic_spin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool mutex_optimistic_spin(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, const bool use_ww_ctx)
```

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671248,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:306",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_killable_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671248,
      "name": "mutex_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
bool mutex_optimistic_spin(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, const bool use_ww_ctx)
```

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579690048,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:306",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_killable_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690048,
      "name": "mutex_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
bool mutex_optimistic_spin(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, const bool use_ww_ctx, const bool waiter)
```

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579717824,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:434",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_killable_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_killable_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717824,
      "name": "mutex_optimistic_spin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588314065,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:512",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588879553,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:512",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589258050,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:513",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589500351,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:611",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589960683,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:612",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590188347,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:638",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591204661,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:638",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591699797,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:638",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591642279,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:638",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592816094,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:434",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594719388,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:441",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596469700,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:441",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597011172,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:441",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597940516,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:441",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503930968,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:638",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236542484,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:638",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297782964,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:638",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:714",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589790635,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:638",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589513115,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:638",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590234043,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:638",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mutex_optimistic_spin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590284411,
      "name": "mutex_optimistic_spin",
      "external": false,
      "loc": "kernel/locking/mutex.c:638",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const bool waiter</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
bool mutex_optimistic_spin(struct mutex * lock, struct ww_acquire_ctx * ww_ctx, const bool use_ww_ctx, const bool waiter)
```
</details>
</li>
</ul>
