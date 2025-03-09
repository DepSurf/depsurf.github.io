# Function: <code>decode_suspend_state</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579731766,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:105",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579727670,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:105",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579760518,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:105",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579795237,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:134",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579841845,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:134",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579875829,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:146",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579926117,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:147",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
suspend_state_t decode_suspend_state(const char * buf, size_t n)
```

```json
{
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579969792,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:147",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:mem_sleep_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579969792,
      "name": "decode_suspend_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
suspend_state_t decode_suspend_state(const char * buf, size_t n)
```

```json
{
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579957712,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:147",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:mem_sleep_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957712,
      "name": "decode_suspend_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579960451,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:147",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580089971,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:147",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580226835,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:150",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580418307,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:153",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580487379,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:194",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580547219,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:178",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491135292,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:147",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225132252,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:147",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284026852,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:147",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579833189,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:147",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579886389,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:147",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
  "name": "decode_suspend_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579932149,
      "name": "decode_suspend_state",
      "external": false,
      "loc": "kernel/power/main.c:147",
      "file": "kernel/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:mem_sleep_store"
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
suspend_state_t decode_suspend_state(const char * buf, size_t n)
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
suspend_state_t decode_suspend_state(const char * buf, size_t n)
```
</details>
</li>
</ul>
