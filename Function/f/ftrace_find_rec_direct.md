# Function: <code>ftrace_find_rec_direct</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int ftrace_find_rec_direct(long unsigned int ip)
```

```json
{
  "name": "ftrace_find_rec_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580612128,
      "name": "ftrace_find_rec_direct",
      "external": true,
      "loc": "kernel/trace/ftrace.c:2360",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:t_show",
        "kernel/trace/ftrace.c:ftrace_get_addr_curr",
        "kernel/trace/ftrace.c:ftrace_get_addr_new",
        "kernel/trace/ftrace.c:call_direct_funcs",
        "kernel/trace/fgraph.c:function_graph_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580612128,
      "name": "ftrace_find_rec_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
long unsigned int ftrace_find_rec_direct(long unsigned int ip)
```

```json
{
  "name": "ftrace_find_rec_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580602320,
      "name": "ftrace_find_rec_direct",
      "external": true,
      "loc": "kernel/trace/ftrace.c:2380",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:t_show",
        "kernel/trace/ftrace.c:ftrace_get_addr_curr",
        "kernel/trace/ftrace.c:ftrace_get_addr_new",
        "kernel/trace/ftrace.c:call_direct_funcs",
        "kernel/trace/fgraph.c:function_graph_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602320,
      "name": "ftrace_find_rec_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
long unsigned int ftrace_find_rec_direct(long unsigned int ip)
```

```json
{
  "name": "ftrace_find_rec_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580605040,
      "name": "ftrace_find_rec_direct",
      "external": true,
      "loc": "kernel/trace/ftrace.c:2386",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:t_show",
        "kernel/trace/ftrace.c:ftrace_get_addr_curr",
        "kernel/trace/ftrace.c:ftrace_get_addr_new",
        "kernel/trace/ftrace.c:call_direct_funcs",
        "kernel/trace/fgraph.c:function_graph_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605040,
      "name": "ftrace_find_rec_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int ftrace_find_rec_direct(long unsigned int ip)
```

```json
{
  "name": "ftrace_find_rec_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_find_rec_direct",
      "external": true,
      "loc": "kernel/trace/ftrace.c:2387",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:t_show",
        "kernel/trace/ftrace.c:call_direct_funcs",
        "kernel/trace/fgraph.c:function_graph_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592166448,
      "name": "ftrace_find_rec_direct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580776432,
      "name": "ftrace_find_rec_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int ftrace_find_rec_direct(long unsigned int ip)
```

```json
{
  "name": "ftrace_find_rec_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_find_rec_direct",
      "external": true,
      "loc": "kernel/trace/ftrace.c:2398",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:register_ftrace_direct_multi",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:t_show",
        "kernel/trace/ftrace.c:call_direct_funcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593939950,
      "name": "ftrace_find_rec_direct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580995152,
      "name": "ftrace_find_rec_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int ftrace_find_rec_direct(long unsigned int ip)
```

```json
{
  "name": "ftrace_find_rec_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_find_rec_direct",
      "external": true,
      "loc": "kernel/trace/ftrace.c:2449",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:register_ftrace_direct_multi",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:t_show",
        "kernel/trace/ftrace.c:call_direct_funcs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596002758,
      "name": "ftrace_find_rec_direct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581293024,
      "name": "ftrace_find_rec_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int ftrace_find_rec_direct(long unsigned int ip)
```

```json
{
  "name": "ftrace_find_rec_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_find_rec_direct",
      "external": true,
      "loc": "kernel/trace/ftrace.c:2547",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:t_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596521204,
      "name": "ftrace_find_rec_direct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581388240,
      "name": "ftrace_find_rec_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int ftrace_find_rec_direct(long unsigned int ip)
```

```json
{
  "name": "ftrace_find_rec_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_find_rec_direct",
      "external": true,
      "loc": "kernel/trace/ftrace.c:2546",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:t_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597421669,
      "name": "ftrace_find_rec_direct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581496256,
      "name": "ftrace_find_rec_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long unsigned int ftrace_find_rec_direct(long unsigned int ip)
```
</details>
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
