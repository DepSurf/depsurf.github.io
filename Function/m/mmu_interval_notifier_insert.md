# Function: <code>mmu_interval_notifier_insert</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```

```json
{
  "name": "mmu_interval_notifier_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581803760,
      "name": "mmu_interval_notifier_insert",
      "external": true,
      "loc": "mm/mmu_notifier.c:978",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803760,
      "name": "mmu_interval_notifier_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```

```json
{
  "name": "mmu_interval_notifier_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581851472,
      "name": "mmu_interval_notifier_insert",
      "external": true,
      "loc": "mm/mmu_notifier.c:995",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581851472,
      "name": "mmu_interval_notifier_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```

```json
{
  "name": "mmu_interval_notifier_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581881600,
      "name": "mmu_interval_notifier_insert",
      "external": true,
      "loc": "mm/mmu_notifier.c:995",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581881600,
      "name": "mmu_interval_notifier_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```

```json
{
  "name": "mmu_interval_notifier_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmu_interval_notifier_insert",
      "external": true,
      "loc": "mm/mmu_notifier.c:995",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592216563,
      "name": "mmu_interval_notifier_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582175456,
      "name": "mmu_interval_notifier_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```

```json
{
  "name": "mmu_interval_notifier_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmu_interval_notifier_insert",
      "external": true,
      "loc": "mm/mmu_notifier.c:995",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593995444,
      "name": "mmu_interval_notifier_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582634912,
      "name": "mmu_interval_notifier_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```

```json
{
  "name": "mmu_interval_notifier_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmu_interval_notifier_insert",
      "external": true,
      "loc": "mm/mmu_notifier.c:995",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596044901,
      "name": "mmu_interval_notifier_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583156272,
      "name": "mmu_interval_notifier_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```

```json
{
  "name": "mmu_interval_notifier_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmu_interval_notifier_insert",
      "external": true,
      "loc": "mm/mmu_notifier.c:995",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596567335,
      "name": "mmu_interval_notifier_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583366640,
      "name": "mmu_interval_notifier_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```

```json
{
  "name": "mmu_interval_notifier_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmu_interval_notifier_insert",
      "external": true,
      "loc": "mm/mmu_notifier.c:987",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597472777,
      "name": "mmu_interval_notifier_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583603488,
      "name": "mmu_interval_notifier_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
