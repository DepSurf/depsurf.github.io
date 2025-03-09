# Function: <code>is_valid_gup_args</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_valid_gup_args(struct page * * pages, int * locked, unsigned int * gup_flags_p, unsigned int to_set)
```

```json
{
  "name": "is_valid_gup_args",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582935923,
      "name": "is_valid_gup_args",
      "external": false,
      "loc": "mm/gup.c:2209",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:pin_user_pages_unlocked",
        "mm/gup.c:pin_user_pages",
        "mm/gup.c:pin_user_pages_remote",
        "mm/gup.c:pin_user_pages_fast",
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages_fast_only"
      ],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582917616,
      "name": "is_valid_gup_args",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
bool is_valid_gup_args(struct page * * pages, int * locked, unsigned int * gup_flags_p, unsigned int to_set)
```

```json
{
  "name": "is_valid_gup_args",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583111171,
      "name": "is_valid_gup_args",
      "external": false,
      "loc": "mm/gup.c:2235",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:pin_user_pages_unlocked",
        "mm/gup.c:pin_user_pages",
        "mm/gup.c:pin_user_pages_remote",
        "mm/gup.c:pin_user_pages_fast",
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages_fast_only"
      ],
      "caller_func": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091744,
      "name": "is_valid_gup_args",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
bool is_valid_gup_args(struct page * * pages, int * locked, unsigned int * gup_flags_p, unsigned int to_set)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
