# Function: <code>rcu_cblist_dequeue</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579856816,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:63",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856816,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579897792,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:46",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897792,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579931728,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:46",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931728,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579978784,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:46",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579978784,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580019264,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:33",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019264,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580069920,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:76",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580069920,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128816,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:67",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128816,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580107008,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:67",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107008,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580110448,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:67",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110448,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580251760,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:67",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580251760,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580420256,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:67",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420256,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580659904,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:67",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580659904,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580736000,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:67",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736000,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580821056,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:67",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821056,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491282352,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:76",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491282352,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225289568,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:76",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225289568,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284187424,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:76",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284187424,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271799942,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:76",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271799942,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580038656,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:76",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038656,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579984096,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:76",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984096,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030192,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:76",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030192,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_dequeue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080896,
      "name": "rcu_cblist_dequeue",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:76",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080896,
      "name": "rcu_cblist_dequeue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct callback_head * rcu_cblist_dequeue(struct rcu_cblist * rclp)
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
