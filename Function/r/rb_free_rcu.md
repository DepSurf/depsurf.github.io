# Function: <code>rb_free_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580389776,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:60",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580442432,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:60",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580389776,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580442432,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580457632,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:60",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580457632,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580520048,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:60",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580520048,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580553040,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:60",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580553040,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580633168,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:61",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633168,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580760528,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:61",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580760528,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580827040,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:61",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580827040,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580921712,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:62",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580921712,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580975168,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:62",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580975168,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581142192,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:63",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581142192,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581182144,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:63",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581182144,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581200688,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:63",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581200688,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581440640,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:63",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581440640,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581781152,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:63",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781152,
      "name": "rb_free_rcu",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582207456,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:63",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582207456,
      "name": "rb_free_rcu",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582407456,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:63",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582407456,
      "name": "rb_free_rcu",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582575680,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:63",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582575680,
      "name": "rb_free_rcu",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492324536,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:62",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492324536,
      "name": "rb_free_rcu",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226216156,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:62",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226216156,
      "name": "rb_free_rcu",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285570432,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:62",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285570432,
      "name": "rb_free_rcu",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272449864,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:62",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272449864,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580943968,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:62",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580943968,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580890032,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:62",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580890032,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935216,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:62",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935216,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void rb_free_rcu(struct callback_head * callback_head)
```

```json
{
  "name": "rb_free_rcu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580996752,
      "name": "rb_free_rcu",
      "external": false,
      "loc": "kernel/events/internal.h:62",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580996752,
      "name": "rb_free_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
