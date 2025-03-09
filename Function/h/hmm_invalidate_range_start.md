# Function: <code>hmm_invalidate_range_start</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void hmm_invalidate_range_start(struct mmu_notifier * mn, struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hmm_invalidate_range_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581388480,
      "name": "hmm_invalidate_range_start",
      "external": false,
      "loc": "mm/hmm.c:163",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581388480,
      "name": "hmm_invalidate_range_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void hmm_invalidate_range_start(struct mmu_notifier * mn, struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "hmm_invalidate_range_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581539232,
      "name": "hmm_invalidate_range_start",
      "external": false,
      "loc": "mm/hmm.c:180",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581539232,
      "name": "hmm_invalidate_range_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier * mn, const struct mmu_notifier_range * range)
```

```json
{
  "name": "hmm_invalidate_range_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581630720,
      "name": "hmm_invalidate_range_start",
      "external": false,
      "loc": "mm/hmm.c:191",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581630720,
      "name": "hmm_invalidate_range_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier * mn, const struct mmu_notifier_range * nrange)
```

```json
{
  "name": "hmm_invalidate_range_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hmm_invalidate_range_start",
      "external": false,
      "loc": "mm/hmm.c:163",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581743600,
      "name": "hmm_invalidate_range_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071581749318,
      "name": "hmm_invalidate_range_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier * mn, const struct mmu_notifier_range * nrange)
```

```json
{
  "name": "hmm_invalidate_range_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581814544,
      "name": "hmm_invalidate_range_start",
      "external": false,
      "loc": "mm/hmm.c:97",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581814544,
      "name": "hmm_invalidate_range_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier * mn, const struct mmu_notifier_range * nrange)
```

```json
{
  "name": "hmm_invalidate_range_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493280792,
      "name": "hmm_invalidate_range_start",
      "external": false,
      "loc": "mm/hmm.c:97",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493280792,
      "name": "hmm_invalidate_range_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier * mn, const struct mmu_notifier_range * nrange)
```

```json
{
  "name": "hmm_invalidate_range_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226883676,
      "name": "hmm_invalidate_range_start",
      "external": false,
      "loc": "mm/hmm.c:97",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226883676,
      "name": "hmm_invalidate_range_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier * mn, const struct mmu_notifier_range * nrange)
```

```json
{
  "name": "hmm_invalidate_range_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286811040,
      "name": "hmm_invalidate_range_start",
      "external": false,
      "loc": "mm/hmm.c:97",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286811040,
      "name": "hmm_invalidate_range_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier * mn, const struct mmu_notifier_range * nrange)
```

```json
{
  "name": "hmm_invalidate_range_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273028822,
      "name": "hmm_invalidate_range_start",
      "external": false,
      "loc": "mm/hmm.c:97",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273028822,
      "name": "hmm_invalidate_range_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier * mn, const struct mmu_notifier_range * nrange)
```

```json
{
  "name": "hmm_invalidate_range_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581783280,
      "name": "hmm_invalidate_range_start",
      "external": false,
      "loc": "mm/hmm.c:97",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581783280,
      "name": "hmm_invalidate_range_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier * mn, const struct mmu_notifier_range * nrange)
```

```json
{
  "name": "hmm_invalidate_range_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581721440,
      "name": "hmm_invalidate_range_start",
      "external": false,
      "loc": "mm/hmm.c:97",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721440,
      "name": "hmm_invalidate_range_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier * mn, const struct mmu_notifier_range * nrange)
```

```json
{
  "name": "hmm_invalidate_range_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581774592,
      "name": "hmm_invalidate_range_start",
      "external": false,
      "loc": "mm/hmm.c:97",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774592,
      "name": "hmm_invalidate_range_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier * mn, const struct mmu_notifier_range * nrange)
```

```json
{
  "name": "hmm_invalidate_range_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581843552,
      "name": "hmm_invalidate_range_start",
      "external": false,
      "loc": "mm/hmm.c:97",
      "file": "mm/hmm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581843552,
      "name": "hmm_invalidate_range_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    }
  ]
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void hmm_invalidate_range_start(struct mmu_notifier * mn, struct mm_struct * mm, long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct mmu_notifier_range * range</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int end</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct mmu_notifier_range * nrange</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct mmu_notifier_range * range</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier * mn, const struct mmu_notifier_range * nrange)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
