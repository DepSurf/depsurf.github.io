# Function: <code>setup_swap_info</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581434224,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2422",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434224,
      "name": "setup_swap_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581498464,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2421",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498464,
      "name": "setup_swap_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581704224,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2451",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:enable_swap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581704224,
      "name": "setup_swap_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751952,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2467",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:enable_swap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751952,
      "name": "setup_swap_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581781056,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2438",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:enable_swap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781056,
      "name": "setup_swap_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064432,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2425",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:enable_swap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064432,
      "name": "setup_swap_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582503984,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2293",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503984,
      "name": "setup_swap_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583016016,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2295",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583016016,
      "name": "setup_swap_info",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583224720,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2286",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583224720,
      "name": "setup_swap_info",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583460096,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2294",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583460096,
      "name": "setup_swap_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492919376,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2421",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:enable_swap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492919376,
      "name": "setup_swap_info",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226709168,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2421",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226709168,
      "name": "setup_swap_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286326640,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2421",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286326640,
      "name": "setup_swap_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272840002,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2421",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272840002,
      "name": "setup_swap_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581467200,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2421",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581467200,
      "name": "setup_swap_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581409456,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2421",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409456,
      "name": "setup_swap_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581458512,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2421",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458512,
      "name": "setup_swap_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```

```json
{
  "name": "setup_swap_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581522944,
      "name": "setup_swap_info",
      "external": false,
      "loc": "mm/swapfile.c:2421",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522944,
      "name": "setup_swap_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void setup_swap_info(struct swap_info_struct * p, int prio, unsigned char * swap_map, struct swap_cluster_info * cluster_info)
```
</details>
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
