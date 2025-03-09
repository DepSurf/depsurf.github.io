# Function: <code>invalidate_mapping_pagevec</code>

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
void invalidate_mapping_pagevec(struct address_space * mapping, long unsigned int start, long unsigned int end, long unsigned int * nr_pagevec)
```

```json
{
  "name": "invalidate_mapping_pagevec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386272,
      "name": "invalidate_mapping_pagevec",
      "external": true,
      "loc": "mm/truncate.c:650",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386272,
      "name": "invalidate_mapping_pagevec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void invalidate_mapping_pagevec(struct address_space * mapping, long unsigned int start, long unsigned int end, long unsigned int * nr_pagevec)
```

```json
{
  "name": "invalidate_mapping_pagevec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581406080,
      "name": "invalidate_mapping_pagevec",
      "external": true,
      "loc": "mm/truncate.c:547",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406080,
      "name": "invalidate_mapping_pagevec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void invalidate_mapping_pagevec(struct address_space * mapping, long unsigned int start, long unsigned int end, long unsigned int * nr_pagevec)
```

```json
{
  "name": "invalidate_mapping_pagevec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581657344,
      "name": "invalidate_mapping_pagevec",
      "external": true,
      "loc": "mm/truncate.c:548",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657344,
      "name": "invalidate_mapping_pagevec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long unsigned int invalidate_mapping_pagevec(struct address_space * mapping, long unsigned int start, long unsigned int end, long unsigned int * nr_pagevec)
```

```json
{
  "name": "invalidate_mapping_pagevec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582026864,
      "name": "invalidate_mapping_pagevec",
      "external": true,
      "loc": "mm/truncate.c:502",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/truncate.c:invalidate_mapping_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026864,
      "name": "invalidate_mapping_pagevec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
long unsigned int invalidate_mapping_pagevec(struct address_space * mapping, long unsigned int start, long unsigned int end, long unsigned int * nr_pagevec)
```

```json
{
  "name": "invalidate_mapping_pagevec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582460608,
      "name": "invalidate_mapping_pagevec",
      "external": true,
      "loc": "mm/truncate.c:498",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/truncate.c:invalidate_mapping_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582460608,
      "name": "invalidate_mapping_pagevec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
    }
  ]
}
```
</details>
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
void invalidate_mapping_pagevec(struct address_space * mapping, long unsigned int start, long unsigned int end, long unsigned int * nr_pagevec)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>long unsigned int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
long unsigned int invalidate_mapping_pagevec(struct address_space * mapping, long unsigned int start, long unsigned int end, long unsigned int * nr_pagevec)
```
</details>
</li>
</ul>
