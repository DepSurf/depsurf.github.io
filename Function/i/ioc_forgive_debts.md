# Function: <code>ioc_forgive_debts</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void ioc_forgive_debts(struct ioc * ioc, u64 usage_us_sum, int nr_debtors, struct ioc_now * now)
```

```json
{
  "name": "ioc_forgive_debts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584674864,
      "name": "ioc_forgive_debts",
      "external": false,
      "loc": "block/blk-iocost.c:2043",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584674864,
      "name": "ioc_forgive_debts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
void ioc_forgive_debts(struct ioc * ioc, u64 usage_us_sum, int nr_debtors, struct ioc_now * now)
```

```json
{
  "name": "ioc_forgive_debts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584702608,
      "name": "ioc_forgive_debts",
      "external": false,
      "loc": "block/blk-iocost.c:2050",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584702608,
      "name": "ioc_forgive_debts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
void ioc_forgive_debts(struct ioc * ioc, u64 usage_us_sum, int nr_debtors, struct ioc_now * now)
```

```json
{
  "name": "ioc_forgive_debts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_forgive_debts",
      "external": false,
      "loc": "block/blk-iocost.c:2050",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585125904,
      "name": "ioc_forgive_debts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
    },
    {
      "addr": 18446744071592320657,
      "name": "ioc_forgive_debts.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void ioc_forgive_debts(struct ioc * ioc, u64 usage_us_sum, int nr_debtors, struct ioc_now * now)
```

```json
{
  "name": "ioc_forgive_debts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_forgive_debts",
      "external": false,
      "loc": "block/blk-iocost.c:2043",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585855488,
      "name": "ioc_forgive_debts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
    },
    {
      "addr": 18446744071594105055,
      "name": "ioc_forgive_debts.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void ioc_forgive_debts(struct ioc * ioc, u64 usage_us_sum, int nr_debtors, struct ioc_now * now)
```

```json
{
  "name": "ioc_forgive_debts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_forgive_debts",
      "external": false,
      "loc": "block/blk-iocost.c:2048",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586638288,
      "name": "ioc_forgive_debts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
    },
    {
      "addr": 18446744071596109432,
      "name": "ioc_forgive_debts.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void ioc_forgive_debts(struct ioc * ioc, u64 usage_us_sum, int nr_debtors, struct ioc_now * now)
```

```json
{
  "name": "ioc_forgive_debts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_forgive_debts",
      "external": false,
      "loc": "block/blk-iocost.c:2064",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586899280,
      "name": "ioc_forgive_debts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
    },
    {
      "addr": 18446744071596633340,
      "name": "ioc_forgive_debts.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void ioc_forgive_debts(struct ioc * ioc, u64 usage_us_sum, int nr_debtors, struct ioc_now * now)
```

```json
{
  "name": "ioc_forgive_debts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_forgive_debts",
      "external": false,
      "loc": "block/blk-iocost.c:2071",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587177312,
      "name": "ioc_forgive_debts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
    },
    {
      "addr": 18446744071597539658,
      "name": "ioc_forgive_debts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void ioc_forgive_debts(struct ioc * ioc, u64 usage_us_sum, int nr_debtors, struct ioc_now * now)
```
</details>
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
