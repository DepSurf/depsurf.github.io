# Function: <code>perf_callchain_user32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578875597,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2239",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578875996,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2327",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578876142,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2343",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578875520,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2362",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578876598,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2397",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578878186,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2403",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578877898,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2419",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int perf_callchain_user32(struct pt_regs * regs, struct perf_callchain_entry_ctx * entry)
```

```json
{
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578868224,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2385",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578868224,
      "name": "perf_callchain_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879197,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2474",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
int perf_callchain_user32(struct pt_regs * regs, struct perf_callchain_entry_ctx * entry)
```

```json
{
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578875360,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2487",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578875360,
      "name": "perf_callchain_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879468,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2598",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578881973,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2828",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578885764,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2828",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578883542,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2841",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578888822,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2825",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578886854,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2823",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578909158,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2820",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879197,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2474",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578873037,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2474",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879133,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2474",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
  "name": "perf_callchain_user32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879485,
      "name": "perf_callchain_user32",
      "external": false,
      "loc": "arch/x86/events/core.c:2474",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int perf_callchain_user32(struct pt_regs * regs, struct perf_callchain_entry_ctx * entry)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int perf_callchain_user32(struct pt_regs * regs, struct perf_callchain_entry_ctx * entry)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int perf_callchain_user32(struct pt_regs * regs, struct perf_callchain_entry_ctx * entry)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int perf_callchain_user32(struct pt_regs * regs, struct perf_callchain_entry_ctx * entry)
```
</details>
</li>
</ul>
