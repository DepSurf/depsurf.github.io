# Function: <code>get_pi_state</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579958832,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:816",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/futex.c:exit_pi_state_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958832,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580004640,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:816",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580004640,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580057264,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:816",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057264,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580104320,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:824",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580104320,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580148336,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:839",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148336,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580196352,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:860",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580196352,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580266016,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:788",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580266016,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580249888,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:789",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580249888,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580255024,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:788",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255024,
      "name": "get_pi_state",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580406336,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:846",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580406336,
      "name": "get_pi_state",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580633904,
      "name": "get_pi_state",
      "external": true,
      "loc": "kernel/futex/pi.c:68",
      "file": "kernel/futex/pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/futex/requeue.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633904,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580900352,
      "name": "get_pi_state",
      "external": true,
      "loc": "kernel/futex/pi.c:68",
      "file": "kernel/futex/pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/futex/requeue.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580900352,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580984320,
      "name": "get_pi_state",
      "external": true,
      "loc": "kernel/futex/pi.c:68",
      "file": "kernel/futex/pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/futex/requeue.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984320,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581079904,
      "name": "get_pi_state",
      "external": true,
      "loc": "kernel/futex/pi.c:69",
      "file": "kernel/futex/pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/futex/requeue.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581079904,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491427784,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:860",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491427784,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225423200,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:860",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225423200,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284375888,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:860",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284375888,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271893634,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:860",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271893634,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580165152,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:860",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165152,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580112768,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:860",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112768,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580156624,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:860",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580156624,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void get_pi_state(struct futex_pi_state * pi_state)
```

```json
{
  "name": "get_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580208640,
      "name": "get_pi_state",
      "external": false,
      "loc": "kernel/futex.c:860",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:attach_to_pi_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580208640,
      "name": "get_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void get_pi_state(struct futex_pi_state * pi_state)
```
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
