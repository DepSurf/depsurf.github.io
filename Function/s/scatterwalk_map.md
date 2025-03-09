# Function: <code>scatterwalk_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * scatterwalk_map(struct scatter_walk * walk)
```

```json
{
  "name": "scatterwalk_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582639968,
      "name": "scatterwalk_map",
      "external": true,
      "loc": "crypto/scatterwalk.c:43",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582639968,
      "name": "scatterwalk_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582889641,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:89",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582897649,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:89",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582986214,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:89",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582994113,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:89",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583036251,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:89",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583044093,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:89",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583201624,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:89",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583209485,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:89",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583410104,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:89",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583418493,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:89",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583531816,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:76",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583538925,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:76",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583719787,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583727011,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583829499,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583836675,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584224933,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
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
  "name": "scatterwalk_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584343317,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
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
  "name": "scatterwalk_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584377834,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
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
  "name": "scatterwalk_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584773066,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
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
  "name": "scatterwalk_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585457948,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:72",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
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
  "name": "scatterwalk_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586216828,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:66",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586452189,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:66",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586462024,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:66",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_next",
        "crypto/skcipher.c:skcipher_walk_next",
        "crypto/skcipher.c:skcipher_next_copy",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586718077,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:66",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586733176,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:66",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_walk_next",
        "crypto/skcipher.c:skcipher_walk_next",
        "crypto/skcipher.c:skcipher_next_copy",
        "crypto/skcipher.c:skcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495640716,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495649244,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228996472,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 3229003780,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289771896,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289782904,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274795358,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274803062,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583798235,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583805411,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583735291,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583742467,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583781995,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583789171,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
  "name": "scatterwalk_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583882987,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583890179,
      "name": "scatterwalk_map",
      "external": false,
      "loc": "include/crypto/scatterwalk.h:71",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void * scatterwalk_map(struct scatter_walk * walk)
```
</details>
</li>
</ul>
