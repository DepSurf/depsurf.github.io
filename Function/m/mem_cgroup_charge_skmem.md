# Function: <code>mem_cgroup_charge_skmem</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090480,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:5722",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_schedule",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090480,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581165696,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:5710",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165696,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581213472,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:5772",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581213472,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581344032,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:5871",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344032,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581491488,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:5939",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581491488,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581577328,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:6270",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581577328,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581688640,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:6562",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581688640,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581762064,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:6892",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581762064,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581981296,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:6750",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581981296,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582031552,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:7010",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031552,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582058288,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:6871",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582058288,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582366272,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:7053",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582366272,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582864160,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:7033",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:sock_setsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582864160,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583411648,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:7222",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:sk_setsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583411648,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583631920,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:7290",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:sk_setsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583631920,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583826848,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:7667",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:sk_setsockopt",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583826848,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493216008,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:6892",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493216008,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226847288,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:6892",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226847288,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286729056,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:6892",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286729056,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272992416,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:6892",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272992416,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581730800,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:6892",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730800,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581669552,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:6892",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581669552,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581722112,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:6892",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581722112,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_charge_skmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790304,
      "name": "mem_cgroup_charge_skmem",
      "external": true,
      "loc": "mm/memcontrol.c:6892",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790304,
      "name": "mem_cgroup_charge_skmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool mem_cgroup_charge_skmem(struct mem_cgroup * memcg, unsigned int nr_pages)
```
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
