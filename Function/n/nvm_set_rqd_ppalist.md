# Function: <code>nvm_set_rqd_ppalist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int nvm_set_rqd_ppalist(struct nvm_dev * dev, struct nvm_rq * rqd, struct ppa_addr * ppas, int nr_ppas)
```

```json
{
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584361456,
      "name": "nvm_set_rqd_ppalist",
      "external": true,
      "loc": "drivers/lightnvm/core.c:241",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_erase_ppa",
        "drivers/lightnvm/core.c:nvm_submit_ppa",
        "drivers/lightnvm/sysblk.c:nvm_set_bb_tbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584361456,
      "name": "nvm_set_rqd_ppalist",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int nvm_set_rqd_ppalist(struct nvm_dev * dev, struct nvm_rq * rqd, const struct ppa_addr * ppas, int nr_ppas, int vblk)
```

```json
{
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584696320,
      "name": "nvm_set_rqd_ppalist",
      "external": true,
      "loc": "drivers/lightnvm/core.c:239",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_submit_ppa",
        "drivers/lightnvm/core.c:nvm_erase_ppa",
        "drivers/lightnvm/sysblk.c:nvm_set_bb_tbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584696320,
      "name": "nvm_set_rqd_ppalist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int nvm_set_rqd_ppalist(struct nvm_dev * dev, struct nvm_rq * rqd, const struct ppa_addr * ppas, int nr_ppas, int vblk)
```

```json
{
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584882960,
      "name": "nvm_set_rqd_ppalist",
      "external": true,
      "loc": "drivers/lightnvm/core.c:333",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_submit_ppa",
        "drivers/lightnvm/core.c:nvm_erase_ppa",
        "drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl",
        "drivers/lightnvm/core.c:nvm_set_bb_tbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584882960,
      "name": "nvm_set_rqd_ppalist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int nvm_set_rqd_ppalist(struct nvm_tgt_dev * tgt_dev, struct nvm_rq * rqd, const struct ppa_addr * ppas, int nr_ppas, int vblk)
```

```json
{
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584971696,
      "name": "nvm_set_rqd_ppalist",
      "external": true,
      "loc": "drivers/lightnvm/core.c:778",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_erase_sync",
        "drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584971696,
      "name": "nvm_set_rqd_ppalist",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int nvm_set_rqd_ppalist(struct nvm_tgt_dev * tgt_dev, struct nvm_rq * rqd, const struct ppa_addr * ppas, int nr_ppas)
```

```json
{
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585392880,
      "name": "nvm_set_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:607",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_erase_sync",
        "drivers/lightnvm/core.c:nvm_set_tgt_bb_tbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585392880,
      "name": "nvm_set_rqd_ppalist",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585636384,
      "name": "nvm_set_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:670",
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
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585764988,
      "name": "nvm_set_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:669",
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
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585997084,
      "name": "nvm_set_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:671",
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
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586144252,
      "name": "nvm_set_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:676",
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
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586901351,
      "name": "nvm_set_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:675",
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
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586986215,
      "name": "nvm_set_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:671",
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
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586867895,
      "name": "nvm_set_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:671",
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
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498935064,
      "name": "nvm_set_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:676",
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
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231509064,
      "name": "nvm_set_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:676",
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
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292073776,
      "name": "nvm_set_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:676",
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
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276322582,
      "name": "nvm_set_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:676",
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
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585904620,
      "name": "nvm_set_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:676",
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
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586094268,
      "name": "nvm_set_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:676",
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
  "name": "nvm_set_rqd_ppalist",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586202876,
      "name": "nvm_set_rqd_ppalist",
      "external": false,
      "loc": "drivers/lightnvm/core.c:676",
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int vblk</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct ppa_addr * ppas</code> ➡️ <code>const struct ppa_addr * ppas</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int vblk</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int nvm_set_rqd_ppalist(struct nvm_tgt_dev * tgt_dev, struct nvm_rq * rqd, const struct ppa_addr * ppas, int nr_ppas)
```
</details>
</li>
</ul>
