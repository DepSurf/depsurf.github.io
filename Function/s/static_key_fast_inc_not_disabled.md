# Function: <code>static_key_fast_inc_not_disabled</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool static_key_fast_inc_not_disabled(struct static_key * key)
```

```json
{
  "name": "static_key_fast_inc_not_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_fast_inc_not_disabled",
      "external": true,
      "loc": "kernel/jump_label.c:127",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked",
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked",
        "net/ipv4/tcp_ipv4.c:tcp_md5_key_copy",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596023522,
      "name": "static_key_fast_inc_not_disabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582338080,
      "name": "static_key_fast_inc_not_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
bool static_key_fast_inc_not_disabled(struct static_key * key)
```

```json
{
  "name": "static_key_fast_inc_not_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_fast_inc_not_disabled",
      "external": true,
      "loc": "kernel/jump_label.c:127",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked",
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked",
        "net/ipv4/tcp_ipv4.c:tcp_md5_key_copy",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596545808,
      "name": "static_key_fast_inc_not_disabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582540048,
      "name": "static_key_fast_inc_not_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
bool static_key_fast_inc_not_disabled(struct static_key * key)
```

```json
{
  "name": "static_key_fast_inc_not_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "static_key_fast_inc_not_disabled",
      "external": true,
      "loc": "kernel/jump_label.c:127",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked",
        "kernel/jump_label.c:static_key_slow_inc_cpuslocked",
        "net/ipv4/tcp_ipv4.c:tcp_md5_key_copy",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait",
        "net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597449587,
      "name": "static_key_fast_inc_not_disabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582709200,
      "name": "static_key_fast_inc_not_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool static_key_fast_inc_not_disabled(struct static_key * key)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
