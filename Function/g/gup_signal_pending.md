# Function: <code>gup_signal_pending</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool gup_signal_pending(unsigned int flags)
```

```json
{
  "name": "gup_signal_pending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582725576,
      "name": "gup_signal_pending",
      "external": false,
      "loc": "mm/gup.c:1322",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_dump_page"
      ],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582705088,
      "name": "gup_signal_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool gup_signal_pending(unsigned int flags)
```

```json
{
  "name": "gup_signal_pending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582919360,
      "name": "gup_signal_pending",
      "external": false,
      "loc": "mm/gup.c:1427",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582919360,
      "name": "gup_signal_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool gup_signal_pending(unsigned int flags)
```

```json
{
  "name": "gup_signal_pending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583093504,
      "name": "gup_signal_pending",
      "external": false,
      "loc": "mm/gup.c:1442",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583093504,
      "name": "gup_signal_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
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
bool gup_signal_pending(unsigned int flags)
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
