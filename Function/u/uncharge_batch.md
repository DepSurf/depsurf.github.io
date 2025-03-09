# Function: <code>uncharge_batch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void uncharge_batch(struct mem_cgroup * memcg, long unsigned int pgpgout, long unsigned int nr_anon, long unsigned int nr_file, long unsigned int nr_huge, struct page * dummy_page)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580931984,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:5422",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:uncharge_list",
        "mm/memcontrol.c:uncharge_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931984,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void uncharge_batch(struct mem_cgroup * memcg, long unsigned int pgpgout, long unsigned int nr_anon, long unsigned int nr_file, long unsigned int nr_huge, long unsigned int nr_kmem, struct page * dummy_page)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581078416,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:5489",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:uncharge_list",
        "mm/memcontrol.c:uncharge_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078416,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
void uncharge_batch(struct mem_cgroup * memcg, long unsigned int pgpgout, long unsigned int nr_anon, long unsigned int nr_file, long unsigned int nr_huge, long unsigned int nr_kmem, struct page * dummy_page)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581154048,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:5474",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:uncharge_list",
        "mm/memcontrol.c:uncharge_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581154048,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
void uncharge_batch(struct mem_cgroup * memcg, long unsigned int pgpgout, long unsigned int nr_anon, long unsigned int nr_file, long unsigned int nr_kmem, long unsigned int nr_huge, long unsigned int nr_shmem, struct page * dummy_page)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581201264,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:5531",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:uncharge_list",
        "mm/memcontrol.c:uncharge_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581201264,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581331728,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:5630",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581331728,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581480128,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:5698",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581480128,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581560880,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:6029",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581560880,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581674608,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:6321",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581674608,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581747008,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:6661",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581747008,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581964256,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:6537",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581964256,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582012784,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:6795",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582012784,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582043040,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:6655",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582043040,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582348576,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:6839",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_list",
        "mm/memcontrol.c:__mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582348576,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582845600,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:6829",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_list",
        "mm/memcontrol.c:__mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582845600,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583390096,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:7018",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_list",
        "mm/memcontrol.c:__mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390096,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583610800,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:7086",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_list",
        "mm/memcontrol.c:__mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583610800,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583805504,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:7413",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_list",
        "mm/memcontrol.c:__mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583805504,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493200232,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:6661",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493200232,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226831500,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:6661",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226831500,
      "name": "uncharge_batch",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286704224,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:6661",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286704224,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272979218,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:6661",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272979218,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581715744,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:6661",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715744,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581654640,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:6661",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581654640,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581707056,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:6661",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581707056,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
void uncharge_batch(const struct uncharge_gather * ug)
```

```json
{
  "name": "uncharge_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581774448,
      "name": "uncharge_batch",
      "external": false,
      "loc": "mm/memcontrol.c:6661",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774448,
      "name": "uncharge_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int nr_kmem</code>
</li>
<li>
<b>Param reordered. </b>
<code>memcg, pgpgout, nr_anon, nr_file, nr_huge, dummy_page</code> ➡️ <code>memcg, pgpgout, nr_anon, nr_file, nr_huge, nr_kmem, dummy_page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int nr_shmem</code>
</li>
<li>
<b>Param reordered. </b>
<code>memcg, pgpgout, nr_anon, nr_file, nr_huge, nr_kmem, dummy_page</code> ➡️ <code>memcg, pgpgout, nr_anon, nr_file, nr_kmem, nr_huge, nr_shmem, dummy_page</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct uncharge_gather * ug</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mem_cgroup * memcg</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int pgpgout</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_anon</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_file</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_kmem</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_huge</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_shmem</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * dummy_page</code>
</li>
</ul>
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
