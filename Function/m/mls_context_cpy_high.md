# Function: <code>mls_context_cpy_high</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582370048,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:80",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582591194,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:80",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582684426,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:80",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int mls_context_cpy_high(struct context * dst, struct context * src)
```

```json
{
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582772752,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:80",
      "file": "security/selinux/ss/mls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582772752,
      "name": "mls_context_cpy_high",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int mls_context_cpy_high(struct context * dst, struct context * src)
```

```json
{
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582928816,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582928816,
      "name": "mls_context_cpy_high",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583132988,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583248965,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583436020,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583541924,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583891496,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584011603,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584039649,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584410769,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585037789,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585756365,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585986884,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586234212,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495312944,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228691208,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289302524,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274529650,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583510660,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583447716,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583494436,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
  "name": "mls_context_cpy_high",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583590804,
      "name": "mls_context_cpy_high",
      "external": false,
      "loc": "security/selinux/ss/context.h:81",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int mls_context_cpy_high(struct context * dst, struct context * src)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int mls_context_cpy_high(struct context * dst, struct context * src)
```
</details>
</li>
</ul>
