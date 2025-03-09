# Function: <code>free_chunk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void free_chunk(struct audit_chunk * chunk)
```

```json
{
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580069696,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:109",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580069696,
      "name": "free_chunk",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void free_chunk(struct audit_chunk * chunk)
```

```json
{
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580102976,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:109",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102976,
      "name": "free_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void free_chunk(struct audit_chunk * chunk)
```

```json
{
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580143232,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:109",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:tag_mount",
        "kernel/audit_tree.c:untag_chunk",
        "kernel/audit_tree.c:audit_put_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143232,
      "name": "free_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580152149,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:110",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580204920,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:111",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:111",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491685188,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225638596,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void free_chunk(struct audit_chunk * chunk)
```

```json
{
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272070936,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit_tree.c:__put_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272070936,
      "name": "free_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
  "name": "free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "free_chunk",
      "external": false,
      "loc": "kernel/audit_tree.c:128",
      "file": "kernel/audit_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_put_chunk"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void free_chunk(struct audit_chunk * chunk)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void free_chunk(struct audit_chunk * chunk)
```
</details>
</li>
</ul>
