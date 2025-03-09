# Function: <code>nvm_set_bb_tbl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int nvm_set_bb_tbl(struct nvm_dev * dev, struct sysblk_scan * s, int type)
```

```json
{
  "name": "nvm_set_bb_tbl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584368944,
      "name": "nvm_set_bb_tbl",
      "external": false,
      "loc": "drivers/lightnvm/sysblk.c:214",
      "file": "drivers/lightnvm/sysblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/sysblk.c:nvm_dev_factory",
        "drivers/lightnvm/sysblk.c:nvm_init_sysblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584368944,
      "name": "nvm_set_bb_tbl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
int nvm_set_bb_tbl(struct nvm_dev * dev, struct sysblk_scan * s, int type)
```

```json
{
  "name": "nvm_set_bb_tbl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584703040,
      "name": "nvm_set_bb_tbl",
      "external": false,
      "loc": "drivers/lightnvm/sysblk.c:270",
      "file": "drivers/lightnvm/sysblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/sysblk.c:nvm_dev_factory",
        "drivers/lightnvm/sysblk.c:nvm_init_sysblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584703040,
      "name": "nvm_set_bb_tbl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int nvm_set_bb_tbl(struct nvm_dev * dev, struct ppa_addr * ppas, int nr_ppas, int type)
```

```json
{
  "name": "nvm_set_bb_tbl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584884288,
      "name": "nvm_set_bb_tbl",
      "external": true,
      "loc": "drivers/lightnvm/core.c:198",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/sysblk.c:nvm_dev_factory",
        "drivers/lightnvm/sysblk.c:nvm_init_sysblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584884288,
      "name": "nvm_set_bb_tbl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ppa_addr * ppas</code>
</li>
<li>
<b>Param added. </b>
<code>int nr_ppas</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sysblk_scan * s</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, s, type</code> ➡️ <code>dev, ppas, nr_ppas, type</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int nvm_set_bb_tbl(struct nvm_dev * dev, struct ppa_addr * ppas, int nr_ppas, int type)
```
</details>
</li>
</ul>
