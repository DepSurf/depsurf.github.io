# Function: <code>kfence_guarded_free</code>

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
void kfence_guarded_free(void * addr, struct kfence_metadata * meta, bool zombie)
```

```json
{
  "name": "kfence_guarded_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582237232,
      "name": "kfence_guarded_free",
      "external": false,
      "loc": "mm/kfence/core.c:355",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:__kfence_free",
        "mm/kfence/core.c:kfence_shutdown_cache",
        "mm/kfence/core.c:rcu_guarded_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582237232,
      "name": "kfence_guarded_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
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
void kfence_guarded_free(void * addr, struct kfence_metadata * meta, bool zombie)
```

```json
{
  "name": "kfence_guarded_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582708608,
      "name": "kfence_guarded_free",
      "external": false,
      "loc": "mm/kfence/core.c:459",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:__kfence_free",
        "mm/kfence/core.c:kfence_shutdown_cache",
        "mm/kfence/core.c:rcu_guarded_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582708608,
      "name": "kfence_guarded_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1084
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
void kfence_guarded_free(void * addr, struct kfence_metadata * meta, bool zombie)
```

```json
{
  "name": "kfence_guarded_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583234320,
      "name": "kfence_guarded_free",
      "external": false,
      "loc": "mm/kfence/core.c:458",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:__kfence_free",
        "mm/kfence/core.c:kfence_shutdown_cache",
        "mm/kfence/core.c:rcu_guarded_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234320,
      "name": "kfence_guarded_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1084
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
void kfence_guarded_free(void * addr, struct kfence_metadata * meta, bool zombie)
```

```json
{
  "name": "kfence_guarded_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583454384,
      "name": "kfence_guarded_free",
      "external": false,
      "loc": "mm/kfence/core.c:486",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:__kfence_free",
        "mm/kfence/core.c:kfence_shutdown_cache",
        "mm/kfence/core.c:rcu_guarded_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583454384,
      "name": "kfence_guarded_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
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
void kfence_guarded_free(void * addr, struct kfence_metadata * meta, bool zombie)
```

```json
{
  "name": "kfence_guarded_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583647568,
      "name": "kfence_guarded_free",
      "external": false,
      "loc": "mm/kfence/core.c:490",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:__kfence_free",
        "mm/kfence/core.c:kfence_shutdown_cache",
        "mm/kfence/core.c:rcu_guarded_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583647568,
      "name": "kfence_guarded_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 629
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
void kfence_guarded_free(void * addr, struct kfence_metadata * meta, bool zombie)
```
</details>
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
