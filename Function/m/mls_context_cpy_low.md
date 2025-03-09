# Function: <code>mls_context_cpy_low</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582369665,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:60",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582590816,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:60",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582684048,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:60",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mls_context_cpy_low(struct context * dst, struct context * src)
```

```json
{
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582776719,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:60",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ],
      "caller_func": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582772880,
      "name": "mls_context_cpy_low",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mls_context_cpy_low(struct context * dst, struct context * src)
```

```json
{
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582932783,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ],
      "caller_func": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582928944,
      "name": "mls_context_cpy_low",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583132741,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583248693,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583435783,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583541687,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583890960,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584011066,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584039129,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584410249,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585037269,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585755845,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585986521,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586233849,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495312672,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228691108,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289302256,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274529318,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583510423,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583447479,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583494199,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
  "name": "mls_context_cpy_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583590567,
      "name": "mls_context_cpy_low",
      "external": false,
      "loc": "security/selinux/ss/context.h:61",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
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
int mls_context_cpy_low(struct context * dst, struct context * src)
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
int mls_context_cpy_low(struct context * dst, struct context * src)
```
</details>
</li>
</ul>
