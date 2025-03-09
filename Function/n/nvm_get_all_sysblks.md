# Function: <code>nvm_get_all_sysblks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int nvm_get_all_sysblks(struct nvm_dev * dev, struct sysblk_scan * s, struct ppa_addr * ppas, nvm_bb_update_fn * fn)
```

```json
{
  "name": "nvm_get_all_sysblks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584367936,
      "name": "nvm_get_all_sysblks",
      "external": false,
      "loc": "drivers/lightnvm/sysblk.c:121",
      "file": "drivers/lightnvm/sysblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/sysblk.c:nvm_dev_factory",
        "drivers/lightnvm/sysblk.c:nvm_get_sysblock",
        "drivers/lightnvm/sysblk.c:nvm_update_sysblock",
        "drivers/lightnvm/sysblk.c:nvm_init_sysblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584367936,
      "name": "nvm_get_all_sysblks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int nvm_get_all_sysblks(struct nvm_dev * dev, struct sysblk_scan * s, struct ppa_addr * ppas, int get_free)
```

```json
{
  "name": "nvm_get_all_sysblks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584701936,
      "name": "nvm_get_all_sysblks",
      "external": false,
      "loc": "drivers/lightnvm/sysblk.c:162",
      "file": "drivers/lightnvm/sysblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/sysblk.c:nvm_dev_factory",
        "drivers/lightnvm/sysblk.c:nvm_init_sysblock",
        "drivers/lightnvm/sysblk.c:nvm_update_sysblock",
        "drivers/lightnvm/sysblk.c:nvm_get_sysblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584701936,
      "name": "nvm_get_all_sysblks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int nvm_get_all_sysblks(struct nvm_dev * dev, struct sysblk_scan * s, struct ppa_addr * ppas, int get_free)
```

```json
{
  "name": "nvm_get_all_sysblks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584889520,
      "name": "nvm_get_all_sysblks",
      "external": false,
      "loc": "drivers/lightnvm/sysblk.c:163",
      "file": "drivers/lightnvm/sysblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/sysblk.c:nvm_dev_factory",
        "drivers/lightnvm/sysblk.c:nvm_init_sysblock",
        "drivers/lightnvm/sysblk.c:nvm_update_sysblock",
        "drivers/lightnvm/sysblk.c:nvm_get_sysblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584889520,
      "name": "nvm_get_all_sysblks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
    }
  ]
}
```
</details>
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int get_free</code>
</li>
<li>
<b>Param removed. </b>
<code>nvm_bb_update_fn * fn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int nvm_get_all_sysblks(struct nvm_dev * dev, struct sysblk_scan * s, struct ppa_addr * ppas, int get_free)
```
</details>
</li>
</ul>
