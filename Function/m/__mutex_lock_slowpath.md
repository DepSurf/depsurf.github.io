# Function: <code>__mutex_lock_slowpath</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __mutex_lock_slowpath(atomic_t * lock_count)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587373600,
      "name": "__mutex_lock_slowpath",
      "external": true,
      "loc": "kernel/locking/mutex.c:816",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373600,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void __mutex_lock_slowpath(atomic_t * lock_count)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587874432,
      "name": "__mutex_lock_slowpath",
      "external": true,
      "loc": "kernel/locking/mutex.c:820",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587874432,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588087328,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:954",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588087328,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588315216,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1129",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588315216,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588880688,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1129",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588880688,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589261040,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1153",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589261040,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589503536,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1331",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589503536,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589964208,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1336",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589964208,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590191872,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1362",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590191872,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591208160,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1362",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock",
        "kernel/locking/mutex.c:mutex_lock_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591208160,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591703360,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1365",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock",
        "kernel/locking/mutex.c:mutex_lock_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591703360,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591643648,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1363",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock",
        "kernel/locking/mutex.c:mutex_lock_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591643648,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592817296,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:977",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock",
        "kernel/locking/mutex.c:mutex_lock_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592817296,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594724224,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1033",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock",
        "kernel/locking/mutex.c:mutex_lock_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594724224,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596474624,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1033",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock",
        "kernel/locking/mutex.c:mutex_lock_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596474624,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597013184,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1033",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock",
        "kernel/locking/mutex.c:mutex_lock_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597013184,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597942528,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1038",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock",
        "kernel/locking/mutex.c:mutex_lock_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597942528,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503932400,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1362",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503932400,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236546652,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1362",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236546652,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297784800,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1362",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297784800,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279802946,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1362",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279802946,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589794160,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1362",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589794160,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589516640,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1362",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589516640,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590237568,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1362",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590237568,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __mutex_lock_slowpath(struct mutex * lock)
```

```json
{
  "name": "__mutex_lock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590285632,
      "name": "__mutex_lock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1362",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590285632,
      "name": "__mutex_lock_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mutex * lock</code>
</li>
<li>
<b>Param removed. </b>
<code>atomic_t * lock_count</code>
</li>
</ul>
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
