# Function: <code>nvm_free_rqd_ppalist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nvm_free_rqd_ppalist(struct nvm_dev * dev, struct nvm_rq * rqd)
```

```json
{
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584360864,
      "name": "nvm_free_rqd_ppalist",
      "external": true,
      "loc": "drivers/lightnvm/core.c:276",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_erase_ppa",
        "drivers/lightnvm/core.c:nvm_submit_ppa"
      ],
      "caller_func": [
        "drivers/lightnvm/sysblk.c:nvm_set_bb_tbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584360864,
      "name": "nvm_free_rqd_ppalist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nvm_free_rqd_ppalist(struct nvm_dev * dev, struct nvm_rq * rqd)
```

```json
{
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584697747,
      "name": "nvm_free_rqd_ppalist",
      "external": true,
      "loc": "drivers/lightnvm/core.c:279",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_submit_ppa",
        "drivers/lightnvm/core.c:nvm_erase_ppa"
      ],
      "caller_func": [
        "drivers/lightnvm/sysblk.c:nvm_set_bb_tbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584695008,
      "name": "nvm_free_rqd_ppalist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nvm_free_rqd_ppalist(struct nvm_dev * dev, struct nvm_rq * rqd)
```

```json
{
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584885315,
      "name": "nvm_free_rqd_ppalist",
      "external": true,
      "loc": "drivers/lightnvm/core.c:374",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_submit_ppa",
        "drivers/lightnvm/core.c:nvm_erase_ppa",
        "drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl",
        "drivers/lightnvm/core.c:nvm_set_bb_tbl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584881616,
      "name": "nvm_free_rqd_ppalist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void nvm_free_rqd_ppalist(struct nvm_tgt_dev * tgt_dev, struct nvm_rq * rqd)
```

```json
{
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584972557,
      "name": "nvm_free_rqd_ppalist",
      "external": true,
      "loc": "drivers/lightnvm/core.c:820",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_erase_sync",
        "drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584971232,
      "name": "nvm_free_rqd_ppalist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585393535,
      "name": "nvm_free_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:643",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_erase_sync",
        "drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl"
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
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585636613,
      "name": "nvm_free_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:706",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl"
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
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585765224,
      "name": "nvm_free_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:705",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta"
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
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585997315,
      "name": "nvm_free_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:707",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta"
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
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586144483,
      "name": "nvm_free_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:712",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta"
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
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586901593,
      "name": "nvm_free_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:711",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta"
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
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586986457,
      "name": "nvm_free_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:707",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta"
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
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586868136,
      "name": "nvm_free_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:707",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta"
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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498935268,
      "name": "nvm_free_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:712",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta"
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
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231509320,
      "name": "nvm_free_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:712",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta"
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
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292074056,
      "name": "nvm_free_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:712",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta"
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
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276322824,
      "name": "nvm_free_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:712",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta"
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
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585904851,
      "name": "nvm_free_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:712",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586094499,
      "name": "nvm_free_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:712",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta"
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
  "name": "nvm_free_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586203107,
      "name": "nvm_free_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:712",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_set_chunk_meta"
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nvm_tgt_dev * tgt_dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nvm_dev * dev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void nvm_free_rqd_ppalist(struct nvm_tgt_dev * tgt_dev, struct nvm_rq * rqd)
```
</details>
</li>
</ul>
