# Function: <code>mem_cgroup_free</code>

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
void mem_cgroup_free(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581064096,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:4163",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581064096,
      "name": "mem_cgroup_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581140974,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:4148",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581188148,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:4177",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581317264,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:4204",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581463472,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:4141",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581547681,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:4414",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581661678,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:4769",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_free(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581730064,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:5083",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730064,
      "name": "mem_cgroup_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581950219,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:4965",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582005508,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:5229",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582034447,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:4996",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582340635,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:5154",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582823233,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:5106",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583367177,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:5251",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583586898,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:5278",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583789298,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:5478",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void mem_cgroup_free(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493185584,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:5083",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493185584,
      "name": "mem_cgroup_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void mem_cgroup_free(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226816120,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:5083",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226816120,
      "name": "mem_cgroup_free",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void mem_cgroup_free(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286678272,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:5083",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286678272,
      "name": "mem_cgroup_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void mem_cgroup_free(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272965996,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:5083",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272965996,
      "name": "mem_cgroup_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void mem_cgroup_free(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581698800,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:5083",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581698800,
      "name": "mem_cgroup_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void mem_cgroup_free(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581637824,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:5083",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581637824,
      "name": "mem_cgroup_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void mem_cgroup_free(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581690112,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:5083",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581690112,
      "name": "mem_cgroup_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void mem_cgroup_free(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581757888,
      "name": "mem_cgroup_free",
      "external": false,
      "loc": "mm/memcontrol.c:5083",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581757888,
      "name": "mem_cgroup_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void mem_cgroup_free(struct mem_cgroup * memcg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void mem_cgroup_free(struct mem_cgroup * memcg)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void mem_cgroup_free(struct mem_cgroup * memcg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void mem_cgroup_free(struct mem_cgroup * memcg)
```
</details>
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
