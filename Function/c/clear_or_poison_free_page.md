# Function: <code>clear_or_poison_free_page</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void clear_or_poison_free_page(struct page * page)
```

```json
{
  "name": "clear_or_poison_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579968000,
      "name": "clear_or_poison_free_page",
      "external": false,
      "loc": "kernel/power/snapshot.c:1181",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579968000,
      "name": "clear_or_poison_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
  "name": "clear_or_poison_free_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579975602,
      "name": "clear_or_poison_free_page",
      "external": false,
      "loc": "kernel/power/snapshot.c:1181",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
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
  "name": "clear_or_poison_free_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580106943,
      "name": "clear_or_poison_free_page",
      "external": false,
      "loc": "kernel/power/snapshot.c:1174",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
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
  "name": "clear_or_poison_free_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580246415,
      "name": "clear_or_poison_free_page",
      "external": false,
      "loc": "kernel/power/snapshot.c:1178",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
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
  "name": "clear_or_poison_free_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580444397,
      "name": "clear_or_poison_free_page",
      "external": false,
      "loc": "kernel/power/snapshot.c:1178",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
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
  "name": "clear_or_poison_free_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580514414,
      "name": "clear_or_poison_free_page",
      "external": false,
      "loc": "kernel/power/snapshot.c:1178",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
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
  "name": "clear_or_poison_free_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580574906,
      "name": "clear_or_poison_free_page",
      "external": false,
      "loc": "kernel/power/snapshot.c:1188",
      "file": "kernel/power/snapshot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void clear_or_poison_free_page(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void clear_or_poison_free_page(struct page * page)
```
</details>
</li>
</ul>
