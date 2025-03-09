# Function: <code>show_all_irqs</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582399911,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:95",
      "file": "fs/proc/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:show_stat"
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
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582498951,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:95",
      "file": "fs/proc/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:show_stat"
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
void show_all_irqs(struct seq_file * p)
```

```json
{
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582798464,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:95",
      "file": "fs/proc/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582798464,
      "name": "show_all_irqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void show_all_irqs(struct seq_file * p)
```

```json
{
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582872016,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:96",
      "file": "fs/proc/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582872016,
      "name": "show_all_irqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582902161,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:96",
      "file": "fs/proc/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:show_stat"
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
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583236054,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:96",
      "file": "fs/proc/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:show_stat"
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
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583734861,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:96",
      "file": "fs/proc/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:show_stat"
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
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584348011,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:96",
      "file": "fs/proc/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:show_stat"
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
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584578240,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:70",
      "file": "fs/proc/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:show_stat"
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
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584809730,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:70",
      "file": "fs/proc/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:show_stat"
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
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494122992,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:95",
      "file": "fs/proc/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:show_stat"
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
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227572412,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:95",
      "file": "fs/proc/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:show_stat"
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
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287795244,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:95",
      "file": "fs/proc/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:show_stat"
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
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273605480,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:95",
      "file": "fs/proc/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:show_stat"
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
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582467687,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:95",
      "file": "fs/proc/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:show_stat"
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
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582404919,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:95",
      "file": "fs/proc/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:show_stat"
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
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582458167,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:95",
      "file": "fs/proc/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:show_stat"
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
  "name": "show_all_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582538519,
      "name": "show_all_irqs",
      "external": false,
      "loc": "fs/proc/stat.c:95",
      "file": "fs/proc/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/stat.c:show_stat"
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
void show_all_irqs(struct seq_file * p)
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
void show_all_irqs(struct seq_file * p)
```
</details>
</li>
</ul>
