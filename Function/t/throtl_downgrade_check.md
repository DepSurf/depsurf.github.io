# Function: <code>throtl_downgrade_check</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583349661,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:1968",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio"
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
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583531139,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:1966",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio"
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
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583745781,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:1975",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio"
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
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583853216,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:1961",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio"
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
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584043764,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:1958",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio"
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
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584147906,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:1960",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio"
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
void throtl_downgrade_check(struct throtl_grp * tg)
```

```json
{
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584540592,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:2004",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584540592,
      "name": "throtl_downgrade_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void throtl_downgrade_check(struct throtl_grp * tg)
```

```json
{
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584649728,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:2018",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584649728,
      "name": "throtl_downgrade_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584684311,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:2018",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void throtl_downgrade_check(struct throtl_grp * tg)
```

```json
{
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:2029",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585097008,
      "name": "throtl_downgrade_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 805
    },
    {
      "addr": 18446744071592320165,
      "name": "throtl_downgrade_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void throtl_downgrade_check(struct throtl_grp * tg)
```

```json
{
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:1930",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:__blk_throtl_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585823744,
      "name": "throtl_downgrade_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
    },
    {
      "addr": 18446744071594104686,
      "name": "throtl_downgrade_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:2146",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:2149",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:2157",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495998628,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:1960",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void throtl_downgrade_check(struct throtl_grp * tg)
```

```json
{
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229338768,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:1960",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229338768,
      "name": "throtl_downgrade_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 900
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
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290227480,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:1960",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio"
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
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275094768,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:1960",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio"
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
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584116642,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:1960",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio"
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
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584052322,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:1960",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio"
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
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584100402,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:1960",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio"
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
  "name": "throtl_downgrade_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584203974,
      "name": "throtl_downgrade_check",
      "external": false,
      "loc": "block/blk-throttle.c:1960",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio"
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
void throtl_downgrade_check(struct throtl_grp * tg)
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
void throtl_downgrade_check(struct throtl_grp * tg)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void throtl_downgrade_check(struct throtl_grp * tg)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void throtl_downgrade_check(struct throtl_grp * tg)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void throtl_downgrade_check(struct throtl_grp * tg)
```
</details>
</li>
</ul>
