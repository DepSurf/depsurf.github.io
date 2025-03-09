# Function: <code>pcpu_free_chunk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pcpu_free_chunk(struct pcpu_chunk * chunk)
```

```json
{
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580614912,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:752",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_balance_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580614912,
      "name": "pcpu_free_chunk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580724026,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:747",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
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
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580789852,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:747",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
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
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580829205,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:738",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
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
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580916685,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1206",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn"
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
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581056295,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1203",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
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
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581134101,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1211",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581128064,
      "name": "pcpu_free_chunk.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581197014,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1449",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581192880,
      "name": "pcpu_free_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581255465,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1449",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581251328,
      "name": "pcpu_free_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581444528,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1421",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_create_chunk"
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
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581487429,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1455",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_create_chunk"
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
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581511852,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1456",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_create_chunk"
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
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581771640,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1500",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_create_chunk"
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
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582151966,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1500",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_create_chunk"
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
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582629207,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1497",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_create_chunk"
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
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582838071,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1497",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_create_chunk"
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
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583013015,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1497",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_create_chunk",
        "mm/percpu.c:pcpu_create_chunk"
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
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492658180,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1449",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492650248,
      "name": "pcpu_free_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226497236,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1449",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226491740,
      "name": "pcpu_free_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285979528,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1449",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285969632,
      "name": "pcpu_free_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272670640,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1449",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272664382,
      "name": "pcpu_free_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
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
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581224313,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1449",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581220176,
      "name": "pcpu_free_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581170301,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1449",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166880,
      "name": "pcpu_free_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581215513,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1449",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581211376,
      "name": "pcpu_free_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_free_chunk",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581278199,
      "name": "pcpu_free_chunk",
      "external": false,
      "loc": "mm/percpu.c:1449",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_create_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274768,
      "name": "pcpu_free_chunk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void pcpu_free_chunk(struct pcpu_chunk * chunk)
```
</details>
</li>
</ul>
