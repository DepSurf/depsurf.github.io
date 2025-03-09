# Function: <code>__flow_cache_shrink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __flow_cache_shrink(struct flow_cache * fc, struct flow_cache_percpu * fcp, int shrink_to)
```

```json
{
  "name": "__flow_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586399728,
      "name": "__flow_cache_shrink",
      "external": false,
      "loc": "net/core/flow.c:112",
      "file": "net/core/flow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow.c:flow_cache_lookup",
        "net/core/flow.c:flow_cache_lookup",
        "net/core/flow.c:flow_cache_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586399728,
      "name": "__flow_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
void __flow_cache_shrink(struct flow_cache * fc, struct flow_cache_percpu * fcp, int shrink_to)
```

```json
{
  "name": "__flow_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586842320,
      "name": "__flow_cache_shrink",
      "external": false,
      "loc": "net/core/flow.c:116",
      "file": "net/core/flow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow.c:flow_cache_cpu",
        "net/core/flow.c:flow_cache_lookup",
        "net/core/flow.c:flow_cache_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586842320,
      "name": "__flow_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
void __flow_cache_shrink(struct flow_cache * fc, struct flow_cache_percpu * fcp, int shrink_to)
```

```json
{
  "name": "__flow_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587033808,
      "name": "__flow_cache_shrink",
      "external": false,
      "loc": "net/core/flow.c:115",
      "file": "net/core/flow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow.c:flow_cache_cpu_dead",
        "net/core/flow.c:flow_cache_lookup",
        "net/core/flow.c:flow_cache_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033808,
      "name": "__flow_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
void __flow_cache_shrink(struct flow_cache * fc, struct flow_cache_percpu * fcp, unsigned int shrink_to)
```

```json
{
  "name": "__flow_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587161696,
      "name": "__flow_cache_shrink",
      "external": false,
      "loc": "net/core/flow.c:116",
      "file": "net/core/flow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow.c:flow_cache_cpu_dead",
        "net/core/flow.c:flow_cache_lookup",
        "net/core/flow.c:flow_cache_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587161696,
      "name": "__flow_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    }
  ]
}
```
</details>
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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int shrink_to</code> ➡️ <code>unsigned int shrink_to</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void __flow_cache_shrink(struct flow_cache * fc, struct flow_cache_percpu * fcp, unsigned int shrink_to)
```
</details>
</li>
</ul>
