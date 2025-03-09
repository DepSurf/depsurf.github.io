# Function: <code>execute_with_initialized_rng</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int execute_with_initialized_rng(struct notifier_block * nb)
```

```json
{
  "name": "execute_with_initialized_rng",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589942256,
      "name": "execute_with_initialized_rng",
      "external": true,
      "loc": "drivers/char/random.c:152",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:vsprintf_init_hashval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589942256,
      "name": "execute_with_initialized_rng",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int execute_with_initialized_rng(struct notifier_block * nb)
```

```json
{
  "name": "execute_with_initialized_rng",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590251536,
      "name": "execute_with_initialized_rng",
      "external": true,
      "loc": "drivers/char/random.c:152",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:vsprintf_init_hashval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590251536,
      "name": "execute_with_initialized_rng",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int execute_with_initialized_rng(struct notifier_block * nb)
```

```json
{
  "name": "execute_with_initialized_rng",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590592480,
      "name": "execute_with_initialized_rng",
      "external": true,
      "loc": "drivers/char/random.c:152",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:vsprintf_init_hashval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590592480,
      "name": "execute_with_initialized_rng",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int execute_with_initialized_rng(struct notifier_block * nb)
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
