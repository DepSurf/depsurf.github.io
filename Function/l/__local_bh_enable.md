# Function: <code>__local_bh_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __local_bh_enable(unsigned int cnt)
```

```json
{
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579389056,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:127",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:_local_bh_enable",
        "kernel/softirq.c:__do_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579389056,
      "name": "__local_bh_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void __local_bh_enable(unsigned int cnt)
```

```json
{
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402144,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:127",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402144,
      "name": "__local_bh_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void __local_bh_enable(unsigned int cnt)
```

```json
{
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579422464,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:138",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579422464,
      "name": "__local_bh_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __local_bh_enable(unsigned int cnt)
```

```json
{
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409712,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:138",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable",
        "kernel/softirq.c:_local_bh_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409712,
      "name": "__local_bh_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591428481,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:138",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591428478,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:142",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593525647,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:142",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593525640,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:142",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593525640,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:142",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593525621,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:142",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595622759,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:149",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595622754,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:337",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595622782,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:336",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597719956,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:349",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596503141,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:349",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597040629,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:334",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597972615,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:334",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490163548,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:142",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224382096,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:142",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297806112,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:142",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279819388,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:142",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593525640,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:142",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593525628,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:142",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593525640,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:142",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
  "name": "__local_bh_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593525640,
      "name": "__local_bh_enable",
      "external": false,
      "loc": "kernel/softirq.c:142",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__do_softirq",
        "kernel/softirq.c:_local_bh_enable"
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void __local_bh_enable(unsigned int cnt)
```
</details>
</li>
</ul>
