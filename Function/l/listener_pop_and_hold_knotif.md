# Function: <code>listener_pop_and_hold_knotif</code>

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
struct aa_knotif * listener_pop_and_hold_knotif(struct aa_listener * listener)
```

```json
{
  "name": "listener_pop_and_hold_knotif",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586100488,
      "name": "listener_pop_and_hold_knotif",
      "external": true,
      "loc": "security/apparmor/notify.c:230",
      "file": "security/apparmor/notify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/notify.c:aa_listener_unotif_recv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586097312,
      "name": "listener_pop_and_hold_knotif",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct aa_knotif * listener_pop_and_hold_knotif(struct aa_listener * listener)
```

```json
{
  "name": "listener_pop_and_hold_knotif",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586339335,
      "name": "listener_pop_and_hold_knotif",
      "external": true,
      "loc": "security/apparmor/notify.c:291",
      "file": "security/apparmor/notify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/notify.c:aa_listener_unotif_recv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586334528,
      "name": "listener_pop_and_hold_knotif",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "listener_pop_and_hold_knotif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586606087,
      "name": "listener_pop_and_hold_knotif",
      "external": false,
      "loc": "security/apparmor/notify.c:294",
      "file": "security/apparmor/notify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/notify.c:aa_listener_unotif_recv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
struct aa_knotif * listener_pop_and_hold_knotif(struct aa_listener * listener)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct aa_knotif * listener_pop_and_hold_knotif(struct aa_listener * listener)
```
</details>
</li>
</ul>
