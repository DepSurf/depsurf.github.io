# Function: <code>audit_buffer_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580030807,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1248",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_start"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580063459,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1260",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_start"
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580103697,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1410",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580109424,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1612",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580161980,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1620",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580221807,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1674",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580274236,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1671",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580324940,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1671",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580373740,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1673",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
struct audit_buffer * audit_buffer_alloc(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580443968,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1748",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580443968,
      "name": "audit_buffer_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
struct audit_buffer * audit_buffer_alloc(struct audit_context * ctx, gfp_t gfp_mask, int type)
```

```json
{
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580431920,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1759",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431920,
      "name": "audit_buffer_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580440065,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1759",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580604913,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1796",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580810021,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1779",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_start"
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581095989,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1777",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_start"
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581187621,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1777",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_start"
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581293813,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1795",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_log_start"
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491638900,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1673",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225591472,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1673",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284633912,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1673",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272034760,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1673",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580342540,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1673",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580289708,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1673",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580333788,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1673",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "audit_buffer_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580389040,
      "name": "audit_buffer_alloc",
      "external": false,
      "loc": "kernel/audit.c:1673",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
struct audit_buffer * audit_buffer_alloc(struct audit_context * ctx, gfp_t gfp_mask, int type)
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
struct audit_buffer * audit_buffer_alloc(struct audit_context * ctx, gfp_t gfp_mask, int type)
```
</details>
</li>
</ul>
