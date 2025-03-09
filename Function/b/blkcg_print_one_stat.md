# Function: <code>blkcg_print_one_stat</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void blkcg_print_one_stat(struct blkcg_gq * blkg, struct seq_file * s)
```

```json
{
  "name": "blkcg_print_one_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkcg_print_one_stat",
      "external": false,
      "loc": "block/blk-cgroup.c:886",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_print_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076544,
      "name": "blkcg_print_one_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    },
    {
      "addr": 18446744071592320039,
      "name": "blkcg_print_one_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkcg_print_one_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585801231,
      "name": "blkcg_print_one_stat",
      "external": false,
      "loc": "block/blk-cgroup.c:947",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_print_stat"
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
  "name": "blkcg_print_one_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586585264,
      "name": "blkcg_print_one_stat",
      "external": false,
      "loc": "block/blk-cgroup.c:959",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_print_stat"
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
  "name": "blkcg_print_one_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586843651,
      "name": "blkcg_print_one_stat",
      "external": false,
      "loc": "block/blk-cgroup.c:1092",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_print_stat"
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
  "name": "blkcg_print_one_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587120992,
      "name": "blkcg_print_one_stat",
      "external": false,
      "loc": "block/blk-cgroup.c:1105",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_print_stat"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void blkcg_print_one_stat(struct blkcg_gq * blkg, struct seq_file * s)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void blkcg_print_one_stat(struct blkcg_gq * blkg, struct seq_file * s)
```
</details>
</li>
</ul>
