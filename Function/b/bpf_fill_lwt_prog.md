# Function: <code>bpf_fill_lwt_prog</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int bpf_fill_lwt_prog(struct sk_buff * skb, int attr, struct bpf_lwt_prog * prog)
```

```json
{
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587078624,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:312",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587078624,
      "name": "bpf_fill_lwt_prog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587206284,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:314",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587206128,
      "name": "bpf_fill_lwt_prog.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587720604,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:314",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587720448,
      "name": "bpf_fill_lwt_prog.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588053493,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:314",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588053344,
      "name": "bpf_fill_lwt_prog.isra.9.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588221797,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:313",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588221648,
      "name": "bpf_fill_lwt_prog.isra.9.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588556805,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:441",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588556656,
      "name": "bpf_fill_lwt_prog.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588773813,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:444",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588773664,
      "name": "bpf_fill_lwt_prog.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589644069,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:444",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589643920,
      "name": "bpf_fill_lwt_prog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589667749,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:444",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589667600,
      "name": "bpf_fill_lwt_prog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589559173,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:444",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589559024,
      "name": "bpf_fill_lwt_prog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590304213,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:444",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590304064,
      "name": "bpf_fill_lwt_prog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591889061,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:444",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591888896,
      "name": "bpf_fill_lwt_prog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593691317,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:444",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593691136,
      "name": "bpf_fill_lwt_prog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594172117,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:443",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594171936,
      "name": "bpf_fill_lwt_prog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594968661,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:443",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594968480,
      "name": "bpf_fill_lwt_prog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502339692,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:444",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502339472,
      "name": "bpf_fill_lwt_prog.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235080328,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:444",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235080168,
      "name": "bpf_fill_lwt_prog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295863108,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:444",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295862800,
      "name": "bpf_fill_lwt_prog.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278562014,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:444",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278561830,
      "name": "bpf_fill_lwt_prog.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588380197,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:444",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588380048,
      "name": "bpf_fill_lwt_prog.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588092885,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:444",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588092736,
      "name": "bpf_fill_lwt_prog.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588712373,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:444",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588712224,
      "name": "bpf_fill_lwt_prog.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
  "name": "bpf_fill_lwt_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588852629,
      "name": "bpf_fill_lwt_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:444",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info",
        "net/core/lwt_bpf.c:bpf_fill_encap_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588852480,
      "name": "bpf_fill_lwt_prog.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int bpf_fill_lwt_prog(struct sk_buff * skb, int attr, struct bpf_lwt_prog * prog)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int bpf_fill_lwt_prog(struct sk_buff * skb, int attr, struct bpf_lwt_prog * prog)
```
</details>
</li>
</ul>
