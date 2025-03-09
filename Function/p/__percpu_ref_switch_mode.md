# Function: <code>__percpu_ref_switch_mode</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583453104,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:212",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583453104,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583473600,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:212",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583473600,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583654576,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:212",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583654576,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872272,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:212",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872272,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583957568,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:212",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957568,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584137664,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:222",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137664,
      "name": "__percpu_ref_switch_mode",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584260112,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:222",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584260112,
      "name": "__percpu_ref_switch_mode",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584667584,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:223",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584667584,
      "name": "__percpu_ref_switch_mode",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584785440,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:257",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584785440,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584829504,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:263",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584829504,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585248176,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:263",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585248176,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586089856,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:264",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586089856,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587073024,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:265",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587073024,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587331040,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:265",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587331040,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587614432,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:265",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587614432,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496140320,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:222",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496140320,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229462740,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:222",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229462740,
      "name": "__percpu_ref_switch_mode",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290398800,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:222",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290398800,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275196698,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:222",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275196698,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584228848,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:222",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228848,
      "name": "__percpu_ref_switch_mode",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584164064,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:222",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164064,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584212608,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:222",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584212608,
      "name": "__percpu_ref_switch_mode",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
```

```json
{
  "name": "__percpu_ref_switch_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584317200,
      "name": "__percpu_ref_switch_mode",
      "external": false,
      "loc": "lib/percpu-refcount.c:222",
      "file": "lib/percpu-refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_percpu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584317200,
      "name": "__percpu_ref_switch_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
void __percpu_ref_switch_mode(struct percpu_ref * ref, percpu_ref_func_t * confirm_switch)
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
