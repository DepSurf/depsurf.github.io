# Function: <code>klp_send_signals</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void klp_send_signals()
```

```json
{
  "name": "klp_send_signals",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579943937,
      "name": "klp_send_signals",
      "external": true,
      "loc": "kernel/livepatch/transition.c:583",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943937,
      "name": "klp_send_signals",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void klp_send_signals()
```

```json
{
  "name": "klp_send_signals",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579991025,
      "name": "klp_send_signals",
      "external": true,
      "loc": "kernel/livepatch/transition.c:576",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991025,
      "name": "klp_send_signals",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_send_signals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580031517,
      "name": "klp_send_signals",
      "external": false,
      "loc": "kernel/livepatch/transition.c:343",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
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
  "name": "klp_send_signals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580082237,
      "name": "klp_send_signals",
      "external": false,
      "loc": "kernel/livepatch/transition.c:343",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void klp_send_signals()
```

```json
{
  "name": "klp_send_signals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_send_signals",
      "external": false,
      "loc": "kernel/livepatch/transition.c:343",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580140624,
      "name": "klp_send_signals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 18446744071580143288,
      "name": "klp_send_signals.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void klp_send_signals()
```

```json
{
  "name": "klp_send_signals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_send_signals",
      "external": false,
      "loc": "kernel/livepatch/transition.c:343",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580117856,
      "name": "klp_send_signals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 18446744071591310435,
      "name": "klp_send_signals.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
  "name": "klp_send_signals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580122615,
      "name": "klp_send_signals",
      "external": false,
      "loc": "kernel/livepatch/transition.c:344",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
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
  "name": "klp_send_signals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580265287,
      "name": "klp_send_signals",
      "external": false,
      "loc": "kernel/livepatch/transition.c:344",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
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
  "name": "klp_send_signals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580435466,
      "name": "klp_send_signals",
      "external": false,
      "loc": "kernel/livepatch/transition.c:341",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
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
  "name": "klp_send_signals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580677812,
      "name": "klp_send_signals",
      "external": false,
      "loc": "kernel/livepatch/transition.c:341",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
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
  "name": "klp_send_signals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580754324,
      "name": "klp_send_signals",
      "external": false,
      "loc": "kernel/livepatch/transition.c:408",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
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
  "name": "klp_send_signals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580839444,
      "name": "klp_send_signals",
      "external": false,
      "loc": "kernel/livepatch/transition.c:408",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "klp_send_signals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284207960,
      "name": "klp_send_signals",
      "external": false,
      "loc": "kernel/livepatch/transition.c:343",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
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
  "name": "klp_send_signals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580050973,
      "name": "klp_send_signals",
      "external": false,
      "loc": "kernel/livepatch/transition.c:343",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
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
  "name": "klp_send_signals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579996285,
      "name": "klp_send_signals",
      "external": false,
      "loc": "kernel/livepatch/transition.c:343",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
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
  "name": "klp_send_signals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580042509,
      "name": "klp_send_signals",
      "external": false,
      "loc": "kernel/livepatch/transition.c:343",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
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
  "name": "klp_send_signals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580093292,
      "name": "klp_send_signals",
      "external": false,
      "loc": "kernel/livepatch/transition.c:343",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_try_complete_transition"
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void klp_send_signals()
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void klp_send_signals()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void klp_send_signals()
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
void klp_send_signals()
```
</details>
</li>
</ul>
