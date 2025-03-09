# Function: <code>dec_rlimit_put_ucounts</code>

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
void dec_rlimit_put_ucounts(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_rlimit_put_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804608,
      "name": "dec_rlimit_put_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:303",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:sigqueue_free",
        "kernel/signal.c:flush_sigqueue_mask",
        "kernel/signal.c:collect_signal",
        "kernel/signal.c:__flush_itimer_signals",
        "kernel/signal.c:flush_sigqueue",
        "kernel/signal.c:__sigqueue_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804608,
      "name": "dec_rlimit_put_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void dec_rlimit_put_ucounts(struct ucounts * ucounts, enum ucount_type type)
```

```json
{
  "name": "dec_rlimit_put_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579914384,
      "name": "dec_rlimit_put_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:309",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:sigqueue_free",
        "kernel/signal.c:flush_sigqueue_mask",
        "kernel/signal.c:collect_signal",
        "kernel/signal.c:__flush_itimer_signals",
        "kernel/signal.c:flush_sigqueue",
        "kernel/signal.c:__sigqueue_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914384,
      "name": "dec_rlimit_put_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void dec_rlimit_put_ucounts(struct ucounts * ucounts, enum rlimit_type type)
```

```json
{
  "name": "dec_rlimit_put_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580068560,
      "name": "dec_rlimit_put_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:305",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:sigqueue_free",
        "kernel/signal.c:flush_sigqueue_mask",
        "kernel/signal.c:collect_signal",
        "kernel/signal.c:__flush_itimer_signals",
        "kernel/signal.c:flush_sigqueue",
        "kernel/signal.c:__sigqueue_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068560,
      "name": "dec_rlimit_put_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void dec_rlimit_put_ucounts(struct ucounts * ucounts, enum rlimit_type type)
```

```json
{
  "name": "dec_rlimit_put_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122128,
      "name": "dec_rlimit_put_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:305",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:sigqueue_free",
        "kernel/signal.c:flush_sigqueue_mask",
        "kernel/signal.c:collect_signal",
        "kernel/signal.c:__flush_itimer_signals",
        "kernel/signal.c:flush_sigqueue",
        "kernel/signal.c:__sigqueue_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122128,
      "name": "dec_rlimit_put_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void dec_rlimit_put_ucounts(struct ucounts * ucounts, enum rlimit_type type)
```

```json
{
  "name": "dec_rlimit_put_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580167712,
      "name": "dec_rlimit_put_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:306",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:sigqueue_free",
        "kernel/signal.c:flush_sigqueue_mask",
        "kernel/signal.c:collect_signal",
        "kernel/signal.c:__flush_itimer_signals",
        "kernel/signal.c:flush_sigqueue",
        "kernel/signal.c:__sigqueue_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167712,
      "name": "dec_rlimit_put_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void dec_rlimit_put_ucounts(struct ucounts * ucounts, enum ucount_type type)
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
