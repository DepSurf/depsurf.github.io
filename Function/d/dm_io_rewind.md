# Function: <code>dm_io_rewind</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void dm_io_rewind(struct dm_io * io, struct bio_set * bs)
```

```json
{
  "name": "dm_io_rewind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_io_rewind",
      "external": true,
      "loc": "drivers/md/dm-io-rewind.c:145",
      "file": "drivers/md/dm-io-rewind.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_wq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596312552,
      "name": "dm_io_rewind.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071592606960,
      "name": "dm_io_rewind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
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
void dm_io_rewind(struct dm_io * io, struct bio_set * bs)
```

```json
{
  "name": "dm_io_rewind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_io_rewind",
      "external": true,
      "loc": "drivers/md/dm-io-rewind.c:143",
      "file": "drivers/md/dm-io-rewind.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_wq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596841466,
      "name": "dm_io_rewind.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071593037536,
      "name": "dm_io_rewind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 775
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
void dm_io_rewind(struct dm_io * io, struct bio_set * bs)
```

```json
{
  "name": "dm_io_rewind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_io_rewind",
      "external": true,
      "loc": "drivers/md/dm-io-rewind.c:143",
      "file": "drivers/md/dm-io-rewind.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_wq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597766478,
      "name": "dm_io_rewind.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071593788960,
      "name": "dm_io_rewind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 775
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
void dm_io_rewind(struct dm_io * io, struct bio_set * bs)
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
