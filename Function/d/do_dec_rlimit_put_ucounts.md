# Function: <code>do_dec_rlimit_put_ucounts</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void do_dec_rlimit_put_ucounts(struct ucounts * ucounts, struct ucounts * last, enum ucount_type type)
```

```json
{
  "name": "do_dec_rlimit_put_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804016,
      "name": "do_dec_rlimit_put_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:290",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:inc_rlimit_get_ucounts",
        "kernel/ucount.c:dec_rlimit_put_ucounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804016,
      "name": "do_dec_rlimit_put_ucounts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void do_dec_rlimit_put_ucounts(struct ucounts * ucounts, struct ucounts * last, enum ucount_type type)
```

```json
{
  "name": "do_dec_rlimit_put_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579913680,
      "name": "do_dec_rlimit_put_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:296",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:inc_rlimit_get_ucounts",
        "kernel/ucount.c:dec_rlimit_put_ucounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579913680,
      "name": "do_dec_rlimit_put_ucounts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void do_dec_rlimit_put_ucounts(struct ucounts * ucounts, struct ucounts * last, enum rlimit_type type)
```

```json
{
  "name": "do_dec_rlimit_put_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067568,
      "name": "do_dec_rlimit_put_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:292",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:inc_rlimit_get_ucounts",
        "kernel/ucount.c:dec_rlimit_put_ucounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067568,
      "name": "do_dec_rlimit_put_ucounts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void do_dec_rlimit_put_ucounts(struct ucounts * ucounts, struct ucounts * last, enum rlimit_type type)
```

```json
{
  "name": "do_dec_rlimit_put_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580120896,
      "name": "do_dec_rlimit_put_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:292",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:inc_rlimit_get_ucounts",
        "kernel/ucount.c:dec_rlimit_put_ucounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580120896,
      "name": "do_dec_rlimit_put_ucounts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void do_dec_rlimit_put_ucounts(struct ucounts * ucounts, struct ucounts * last, enum rlimit_type type)
```

```json
{
  "name": "do_dec_rlimit_put_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580166480,
      "name": "do_dec_rlimit_put_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:293",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:inc_rlimit_get_ucounts",
        "kernel/ucount.c:dec_rlimit_put_ucounts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166480,
      "name": "do_dec_rlimit_put_ucounts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void do_dec_rlimit_put_ucounts(struct ucounts * ucounts, struct ucounts * last, enum ucount_type type)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum ucount_type type</code> ➡️ <code>enum rlimit_type type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
