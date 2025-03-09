# Function: <code>calc_stack</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580521568,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1391",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580579280,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1384",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580637504,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1406",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580684224,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1408",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
int calc_stack(const char * str, int * parens, int * preds, int * err)
```

```json
{
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580784176,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1408",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:process_preds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784176,
      "name": "calc_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
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
int calc_stack(const char * str, int * parens, int * preds, int * err)
```

```json
{
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772160,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1408",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:process_preds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772160,
      "name": "calc_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580783016,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1408",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580968120,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1501",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581212008,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1529",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581529864,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1626",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581649080,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1717",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581764936,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1978",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491992712,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1408",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225927780,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1408",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285117392,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1408",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272259338,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1408",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580653024,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1408",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580599232,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1408",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580644272,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1408",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
  "name": "calc_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580701776,
      "name": "calc_stack",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1408",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:process_preds"
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
int calc_stack(const char * str, int * parens, int * preds, int * err)
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
int calc_stack(const char * str, int * parens, int * preds, int * err)
```
</details>
</li>
</ul>
