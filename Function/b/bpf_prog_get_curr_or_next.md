# Function: <code>bpf_prog_get_curr_or_next</code>

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
struct bpf_prog * bpf_prog_get_curr_or_next(u32 * id)
```

```json
{
  "name": "bpf_prog_get_curr_or_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580948128,
      "name": "bpf_prog_get_curr_or_next",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3180",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/prog_iter.c:bpf_prog_seq_next",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580948128,
      "name": "bpf_prog_get_curr_or_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_get_curr_or_next(u32 * id)
```

```json
{
  "name": "bpf_prog_get_curr_or_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580951904,
      "name": "bpf_prog_get_curr_or_next",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3203",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/prog_iter.c:bpf_prog_seq_next",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951904,
      "name": "bpf_prog_get_curr_or_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_get_curr_or_next(u32 * id)
```

```json
{
  "name": "bpf_prog_get_curr_or_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581156736,
      "name": "bpf_prog_get_curr_or_next",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3386",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/prog_iter.c:bpf_prog_seq_next",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581156736,
      "name": "bpf_prog_get_curr_or_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_get_curr_or_next(u32 * id)
```

```json
{
  "name": "bpf_prog_get_curr_or_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581432720,
      "name": "bpf_prog_get_curr_or_next",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3644",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/prog_iter.c:bpf_prog_seq_next",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432720,
      "name": "bpf_prog_get_curr_or_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_get_curr_or_next(u32 * id)
```

```json
{
  "name": "bpf_prog_get_curr_or_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581785984,
      "name": "bpf_prog_get_curr_or_next",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3687",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/prog_iter.c:bpf_prog_seq_next",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785984,
      "name": "bpf_prog_get_curr_or_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_get_curr_or_next(u32 * id)
```

```json
{
  "name": "bpf_prog_get_curr_or_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581947152,
      "name": "bpf_prog_get_curr_or_next",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3823",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/prog_iter.c:bpf_prog_seq_next",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581947152,
      "name": "bpf_prog_get_curr_or_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_get_curr_or_next(u32 * id)
```

```json
{
  "name": "bpf_prog_get_curr_or_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582073616,
      "name": "bpf_prog_get_curr_or_next",
      "external": true,
      "loc": "kernel/bpf/syscall.c:4160",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/prog_iter.c:bpf_prog_seq_next",
        "kernel/bpf/prog_iter.c:bpf_prog_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073616,
      "name": "bpf_prog_get_curr_or_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
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
struct bpf_prog * bpf_prog_get_curr_or_next(u32 * id)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
