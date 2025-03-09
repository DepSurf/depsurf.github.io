# Function: <code>bpf_test_timer_continue</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool bpf_test_timer_continue(struct bpf_test_timer * t, u32 repeat, int * err, u32 * duration)
```

```json
{
  "name": "bpf_test_timer_continue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589792592,
      "name": "bpf_test_timer_continue",
      "external": false,
      "loc": "net/bpf/test_run.c:52",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589792592,
      "name": "bpf_test_timer_continue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
bool bpf_test_timer_continue(struct bpf_test_timer * t, u32 repeat, int * err, u32 * duration)
```

```json
{
  "name": "bpf_test_timer_continue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590552688,
      "name": "bpf_test_timer_continue",
      "external": false,
      "loc": "net/bpf/test_run.c:54",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590552688,
      "name": "bpf_test_timer_continue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
bool bpf_test_timer_continue(struct bpf_test_timer * t, int iterations, u32 repeat, int * err, u32 * duration)
```

```json
{
  "name": "bpf_test_timer_continue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592165488,
      "name": "bpf_test_timer_continue",
      "external": false,
      "loc": "net/bpf/test_run.c:57",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run_xdp_live"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592165488,
      "name": "bpf_test_timer_continue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
bool bpf_test_timer_continue(struct bpf_test_timer * t, int iterations, u32 repeat, int * err, u32 * duration)
```

```json
{
  "name": "bpf_test_timer_continue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593992912,
      "name": "bpf_test_timer_continue",
      "external": false,
      "loc": "net/bpf/test_run.c:57",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run_xdp_live"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593992912,
      "name": "bpf_test_timer_continue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
bool bpf_test_timer_continue(struct bpf_test_timer * t, int iterations, u32 repeat, int * err, u32 * duration)
```

```json
{
  "name": "bpf_test_timer_continue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594370112,
      "name": "bpf_test_timer_continue",
      "external": false,
      "loc": "net/bpf/test_run.c:59",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run_xdp_live"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594370112,
      "name": "bpf_test_timer_continue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
bool bpf_test_timer_continue(struct bpf_test_timer * t, int iterations, u32 repeat, int * err, u32 * duration)
```

```json
{
  "name": "bpf_test_timer_continue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595170928,
      "name": "bpf_test_timer_continue",
      "external": false,
      "loc": "net/bpf/test_run.c:60",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run_xdp_live"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595170928,
      "name": "bpf_test_timer_continue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
bool bpf_test_timer_continue(struct bpf_test_timer * t, u32 repeat, int * err, u32 * duration)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int iterations</code>
</li>
<li>
<b>Param reordered. </b>
<code>t, repeat, err, duration</code> ➡️ <code>t, iterations, repeat, err, duration</code>
</li>
</ul>
</details>
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
