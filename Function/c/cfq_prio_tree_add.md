# Function: <code>cfq_prio_tree_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cfq_prio_tree_add(struct cfq_data * cfqd, struct cfq_queue * cfqq)
```

```json
{
  "name": "cfq_prio_tree_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582898464,
      "name": "cfq_prio_tree_add",
      "external": false,
      "loc": "block/cfq-iosched.c:2313",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_add_cfqq_rr",
        "block/cfq-iosched.c:cfq_add_rq_rb",
        "block/cfq-iosched.c:__cfq_slice_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582898464,
      "name": "cfq_prio_tree_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void cfq_prio_tree_add(struct cfq_data * cfqd, struct cfq_queue * cfqq)
```

```json
{
  "name": "cfq_prio_tree_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583185440,
      "name": "cfq_prio_tree_add",
      "external": false,
      "loc": "block/cfq-iosched.c:2338",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:cfq_add_rq_rb",
        "block/cfq-iosched.c:cfq_add_cfqq_rr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583185440,
      "name": "cfq_prio_tree_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void cfq_prio_tree_add(struct cfq_data * cfqd, struct cfq_queue * cfqq)
```

```json
{
  "name": "cfq_prio_tree_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583297840,
      "name": "cfq_prio_tree_add",
      "external": false,
      "loc": "block/cfq-iosched.c:2329",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:cfq_add_rq_rb",
        "block/cfq-iosched.c:cfq_add_cfqq_rr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583297840,
      "name": "cfq_prio_tree_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cfq_prio_tree_add(struct cfq_data * cfqd, struct cfq_queue * cfqq)
```

```json
{
  "name": "cfq_prio_tree_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583365360,
      "name": "cfq_prio_tree_add",
      "external": false,
      "loc": "block/cfq-iosched.c:2334",
      "file": "block/cfq-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:cfq_add_rq_rb",
        "block/cfq-iosched.c:cfq_add_cfqq_rr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583365360,
      "name": "cfq_prio_tree_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cfq_prio_tree_add(struct cfq_data * cfqd, struct cfq_queue * cfqq)
```

```json
{
  "name": "cfq_prio_tree_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583545456,
      "name": "cfq_prio_tree_add",
      "external": false,
      "loc": "block/cfq-iosched.c:2310",
      "file": "block/cfq-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:cfq_add_rq_rb",
        "block/cfq-iosched.c:cfq_add_rq_rb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583545456,
      "name": "cfq_prio_tree_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void cfq_prio_tree_add(struct cfq_data * cfqd, struct cfq_queue * cfqq)
```

```json
{
  "name": "cfq_prio_tree_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583757936,
      "name": "cfq_prio_tree_add",
      "external": false,
      "loc": "block/cfq-iosched.c:2313",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:cfq_add_rq_rb",
        "block/cfq-iosched.c:cfq_add_rq_rb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757936,
      "name": "cfq_prio_tree_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void cfq_prio_tree_add(struct cfq_data * cfqd, struct cfq_queue * cfqq)
```
</details>
</li>
</ul>
