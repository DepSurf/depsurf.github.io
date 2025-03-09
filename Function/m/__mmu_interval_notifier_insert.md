# Function: <code>__mmu_interval_notifier_insert</code>

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
int __mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, struct mmu_notifier_subscriptions * subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```

```json
{
  "name": "__mmu_interval_notifier_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581801616,
      "name": "__mmu_interval_notifier_insert",
      "external": false,
      "loc": "mm/mmu_notifier.c:897",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_notifier.c:mmu_interval_notifier_insert_locked",
        "mm/mmu_notifier.c:mmu_interval_notifier_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581801616,
      "name": "__mmu_interval_notifier_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int __mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, struct mmu_notifier_subscriptions * subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```

```json
{
  "name": "__mmu_interval_notifier_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581849232,
      "name": "__mmu_interval_notifier_insert",
      "external": false,
      "loc": "mm/mmu_notifier.c:913",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_notifier.c:mmu_interval_notifier_insert_locked",
        "mm/mmu_notifier.c:mmu_interval_notifier_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581849232,
      "name": "__mmu_interval_notifier_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int __mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, struct mmu_notifier_subscriptions * subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```

```json
{
  "name": "__mmu_interval_notifier_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581879824,
      "name": "__mmu_interval_notifier_insert",
      "external": false,
      "loc": "mm/mmu_notifier.c:913",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_notifier.c:mmu_interval_notifier_insert_locked",
        "mm/mmu_notifier.c:mmu_interval_notifier_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879824,
      "name": "__mmu_interval_notifier_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int __mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, struct mmu_notifier_subscriptions * subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```

```json
{
  "name": "__mmu_interval_notifier_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582174240,
      "name": "__mmu_interval_notifier_insert",
      "external": false,
      "loc": "mm/mmu_notifier.c:913",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_notifier.c:mmu_interval_notifier_insert_locked",
        "mm/mmu_notifier.c:mmu_interval_notifier_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582174240,
      "name": "__mmu_interval_notifier_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int __mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, struct mmu_notifier_subscriptions * subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```

```json
{
  "name": "__mmu_interval_notifier_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582632720,
      "name": "__mmu_interval_notifier_insert",
      "external": false,
      "loc": "mm/mmu_notifier.c:913",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_notifier.c:mmu_interval_notifier_insert_locked",
        "mm/mmu_notifier.c:mmu_interval_notifier_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582632720,
      "name": "__mmu_interval_notifier_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int __mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, struct mmu_notifier_subscriptions * subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```

```json
{
  "name": "__mmu_interval_notifier_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583153936,
      "name": "__mmu_interval_notifier_insert",
      "external": false,
      "loc": "mm/mmu_notifier.c:913",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_notifier.c:mmu_interval_notifier_insert_locked",
        "mm/mmu_notifier.c:mmu_interval_notifier_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583153936,
      "name": "__mmu_interval_notifier_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int __mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, struct mmu_notifier_subscriptions * subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```

```json
{
  "name": "__mmu_interval_notifier_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583364288,
      "name": "__mmu_interval_notifier_insert",
      "external": false,
      "loc": "mm/mmu_notifier.c:913",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_notifier.c:mmu_interval_notifier_insert_locked",
        "mm/mmu_notifier.c:mmu_interval_notifier_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583364288,
      "name": "__mmu_interval_notifier_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int __mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, struct mmu_notifier_subscriptions * subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
```

```json
{
  "name": "__mmu_interval_notifier_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583601056,
      "name": "__mmu_interval_notifier_insert",
      "external": false,
      "loc": "mm/mmu_notifier.c:905",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_notifier.c:mmu_interval_notifier_insert_locked",
        "mm/mmu_notifier.c:mmu_interval_notifier_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583601056,
      "name": "__mmu_interval_notifier_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int __mmu_interval_notifier_insert(struct mmu_interval_notifier * interval_sub, struct mm_struct * mm, struct mmu_notifier_subscriptions * subscriptions, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops * ops)
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
