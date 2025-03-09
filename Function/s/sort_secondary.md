# Function: <code>sort_secondary</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580289878,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:920",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580333494,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:920",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580345748,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:923",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580399232,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:924",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580461325,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:995",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580516973,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:986",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580573158,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:986",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580620310,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:986",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void sort_secondary(struct tracing_map * map, const struct tracing_map_sort_entry * * entries, unsigned int n_entries, struct tracing_map_sort_key * primary_key, struct tracing_map_sort_key * secondary_key)
```

```json
{
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580715728,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:986",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580715728,
      "name": "sort_secondary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
void sort_secondary(struct tracing_map * map, const struct tracing_map_sort_entry * * entries, unsigned int n_entries, struct tracing_map_sort_key * primary_key, struct tracing_map_sort_key * secondary_key)
```

```json
{
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580705168,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:986",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705168,
      "name": "sort_secondary",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580713128,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:986",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580891773,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:998",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581127019,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:998",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581437461,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:997",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581534293,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:997",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581646458,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:1002",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491922056,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:986",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285017488,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:986",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580589110,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:986",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580535734,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:986",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580580358,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:986",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sort_secondary",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580637094,
      "name": "sort_secondary",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:986",
      "file": "kernel/trace/tracing_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_sort_entries"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void sort_secondary(struct tracing_map * map, const struct tracing_map_sort_entry * * entries, unsigned int n_entries, struct tracing_map_sort_key * primary_key, struct tracing_map_sort_key * secondary_key)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void sort_secondary(struct tracing_map * map, const struct tracing_map_sort_entry * * entries, unsigned int n_entries, struct tracing_map_sort_key * primary_key, struct tracing_map_sort_key * secondary_key)
```
</details>
</li>
</ul>
