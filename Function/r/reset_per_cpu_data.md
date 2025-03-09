# Function: <code>reset_per_cpu_data</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588760640,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:129",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588760640,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589631264,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:130",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589631264,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589654096,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:132",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589654096,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589543568,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:132",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589543568,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590287744,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:132",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590287744,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591870928,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:143",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591870928,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593671584,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:130",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593671584,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594151696,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:132",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594151696,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594948048,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:132",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594948048,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502324784,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:129",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502324784,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235065108,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:129",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235065108,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295840768,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:129",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295840768,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278549000,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:129",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278549000,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588367376,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:129",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588367376,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588080080,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:129",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588080080,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588699200,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:129",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588699200,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```

```json
{
  "name": "reset_per_cpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588839040,
      "name": "reset_per_cpu_data",
      "external": false,
      "loc": "net/core/drop_monitor.c:129",
      "file": "net/core/drop_monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:send_dm_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588839040,
      "name": "reset_per_cpu_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct sk_buff * reset_per_cpu_data(struct per_cpu_dm_data * data)
```
</details>
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
