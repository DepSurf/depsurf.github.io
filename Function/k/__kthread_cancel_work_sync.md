# Function: <code>__kthread_cancel_work_sync</code>

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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538112,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1052",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538112,
      "name": "__kthread_cancel_work_sync",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525088,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1057",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525088,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550960,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1062",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550960,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578400,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1080",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578400,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579615408,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1082",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615408,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579640480,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1092",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640480,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579666432,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1092",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666432,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579701776,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1128",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701776,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579679968,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1182",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579679968,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686416,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1237",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686416,
      "name": "__kthread_cancel_work_sync",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579764736,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1237",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764736,
      "name": "__kthread_cancel_work_sync",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579870672,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1297",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870672,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013504,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1297",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013504,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067040,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1298",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067040,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580109680,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1315",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109680,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490847152,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1092",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490847152,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224872280,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1092",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224872280,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283679808,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1092",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283679808,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271514648,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1092",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271514648,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579642752,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1092",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642752,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571136,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1092",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571136,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579640016,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1092",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640016,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
```

```json
{
  "name": "__kthread_cancel_work_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674256,
      "name": "__kthread_cancel_work_sync",
      "external": false,
      "loc": "kernel/kthread.c:1092",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_cancel_delayed_work_sync",
        "kernel/kthread.c:kthread_cancel_work_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674256,
      "name": "__kthread_cancel_work_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
bool __kthread_cancel_work_sync(struct kthread_work * work, bool is_dwork)
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
