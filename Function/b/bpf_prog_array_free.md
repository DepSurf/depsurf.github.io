# Function: <code>bpf_prog_array_free</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580540960,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1453",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540960,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580624720,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1551",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580624720,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580684960,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1802",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684960,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752368,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1797",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752368,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580802928,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1797",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802928,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920368,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1875",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920368,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916864,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1877",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916864,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920816,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1973",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920816,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581123328,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1986",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123328,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581392672,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:2272",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581392672,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581742256,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:2245",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742256,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581901568,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:2262",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901568,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582025232,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:2438",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_pernet_pre_exit",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_detach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025232,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492117856,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1797",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492117856,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226018972,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1797",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226018972,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285325616,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1797",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285325616,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272289988,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1797",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272289988,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580771728,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1797",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771728,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580717904,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1797",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580717904,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580762976,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1797",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580762976,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void bpf_prog_array_free(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580821120,
      "name": "bpf_prog_array_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1797",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821120,
      "name": "bpf_prog_array_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void bpf_prog_array_free(struct bpf_prog_array * progs)
```
</details>
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
