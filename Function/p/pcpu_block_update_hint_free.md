# Function: <code>pcpu_block_update_hint_free</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580918188,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:784",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_free_area"
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
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581049669,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:781",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_free_area"
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
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581127255,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:789",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_free_area"
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
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581191996,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:931",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_free_area"
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
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581250444,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:931",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_free_area"
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
void pcpu_block_update_hint_free(struct pcpu_chunk * chunk, int bit_off, int bits)
```

```json
{
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581438112,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:903",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438112,
      "name": "pcpu_block_update_hint_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
void pcpu_block_update_hint_free(struct pcpu_chunk * chunk, int bit_off, int bits)
```

```json
{
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581481232,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:912",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581481232,
      "name": "pcpu_block_update_hint_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 662
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
void pcpu_block_update_hint_free(struct pcpu_chunk * chunk, int bit_off, int bits)
```

```json
{
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581504736,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:913",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504736,
      "name": "pcpu_block_update_hint_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void pcpu_block_update_hint_free(struct pcpu_chunk * chunk, int bit_off, int bits)
```

```json
{
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:960",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581766144,
      "name": "pcpu_block_update_hint_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
    },
    {
      "addr": 18446744071592194047,
      "name": "pcpu_block_update_hint_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void pcpu_block_update_hint_free(struct pcpu_chunk * chunk, int bit_off, int bits)
```

```json
{
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:959",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152320,
      "name": "pcpu_block_update_hint_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
    },
    {
      "addr": 18446744071593970708,
      "name": "pcpu_block_update_hint_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void pcpu_block_update_hint_free(struct pcpu_chunk * chunk, int bit_off, int bits)
```

```json
{
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:963",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582631152,
      "name": "pcpu_block_update_hint_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
    },
    {
      "addr": 18446744071596028064,
      "name": "pcpu_block_update_hint_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void pcpu_block_update_hint_free(struct pcpu_chunk * chunk, int bit_off, int bits)
```

```json
{
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:963",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582840272,
      "name": "pcpu_block_update_hint_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
    },
    {
      "addr": 18446744071596550461,
      "name": "pcpu_block_update_hint_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void pcpu_block_update_hint_free(struct pcpu_chunk * chunk, int bit_off, int bits)
```

```json
{
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:963",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_free_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015376,
      "name": "pcpu_block_update_hint_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
    },
    {
      "addr": 18446744071597454126,
      "name": "pcpu_block_update_hint_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492651912,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:931",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_free_area"
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
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226494728,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:931",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_free_area"
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
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285973932,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:931",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_free_area"
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
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272666950,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:931",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_free_area"
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
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581219292,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:931",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_free_area"
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
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581165996,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:931",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_free_area"
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
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581210492,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:931",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_free_area"
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
  "name": "pcpu_block_update_hint_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581273852,
      "name": "pcpu_block_update_hint_free",
      "external": false,
      "loc": "mm/percpu.c:931",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_free_area"
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
void pcpu_block_update_hint_free(struct pcpu_chunk * chunk, int bit_off, int bits)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
