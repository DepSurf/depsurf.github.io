# Function: <code>pcpu_memcg_post_alloc_hook</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_memcg_post_alloc_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581490052,
      "name": "pcpu_memcg_post_alloc_hook",
      "external": false,
      "loc": "mm/percpu.c:1603",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581484064,
      "name": "pcpu_memcg_post_alloc_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_memcg_post_alloc_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581509465,
      "name": "pcpu_memcg_post_alloc_hook",
      "external": false,
      "loc": "mm/percpu.c:1604",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581508832,
      "name": "pcpu_memcg_post_alloc_hook.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void pcpu_memcg_post_alloc_hook(struct obj_cgroup * objcg, struct pcpu_chunk * chunk, int off, size_t size)
```

```json
{
  "name": "pcpu_memcg_post_alloc_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581771936,
      "name": "pcpu_memcg_post_alloc_hook",
      "external": false,
      "loc": "mm/percpu.c:1647",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581771936,
      "name": "pcpu_memcg_post_alloc_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void pcpu_memcg_post_alloc_hook(struct obj_cgroup * objcg, struct pcpu_chunk * chunk, int off, size_t size)
```

```json
{
  "name": "pcpu_memcg_post_alloc_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582154304,
      "name": "pcpu_memcg_post_alloc_hook",
      "external": false,
      "loc": "mm/percpu.c:1647",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154304,
      "name": "pcpu_memcg_post_alloc_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
void pcpu_memcg_post_alloc_hook(struct obj_cgroup * objcg, struct pcpu_chunk * chunk, int off, size_t size)
```

```json
{
  "name": "pcpu_memcg_post_alloc_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582634624,
      "name": "pcpu_memcg_post_alloc_hook",
      "external": false,
      "loc": "mm/percpu.c:1644",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582634624,
      "name": "pcpu_memcg_post_alloc_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
void pcpu_memcg_post_alloc_hook(struct obj_cgroup * objcg, struct pcpu_chunk * chunk, int off, size_t size)
```

```json
{
  "name": "pcpu_memcg_post_alloc_hook",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582843776,
      "name": "pcpu_memcg_post_alloc_hook",
      "external": false,
      "loc": "mm/percpu.c:1644",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582843776,
      "name": "pcpu_memcg_post_alloc_hook",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcpu_memcg_post_alloc_hook(struct obj_cgroup * objcg, struct pcpu_chunk * chunk, int off, size_t size)
```

```json
{
  "name": "pcpu_memcg_post_alloc_hook",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583015072,
      "name": "pcpu_memcg_post_alloc_hook",
      "external": false,
      "loc": "mm/percpu.c:1642",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015072,
      "name": "pcpu_memcg_post_alloc_hook",
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void pcpu_memcg_post_alloc_hook(struct obj_cgroup * objcg, struct pcpu_chunk * chunk, int off, size_t size)
```
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
