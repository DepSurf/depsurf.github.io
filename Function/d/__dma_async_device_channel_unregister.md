# Function: <code>__dma_async_device_channel_unregister</code>

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
void __dma_async_device_channel_unregister(struct dma_device * device, struct dma_chan * chan)
```

```json
{
  "name": "__dma_async_device_channel_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586211664,
      "name": "__dma_async_device_channel_unregister",
      "external": false,
      "loc": "drivers/dma/dmaengine.c:1109",
      "file": "drivers/dma/dmaengine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_channel_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586211664,
      "name": "__dma_async_device_channel_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
void __dma_async_device_channel_unregister(struct dma_device * device, struct dma_chan * chan)
```

```json
{
  "name": "__dma_async_device_channel_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586331328,
      "name": "__dma_async_device_channel_unregister",
      "external": false,
      "loc": "drivers/dma/dmaengine.c:1106",
      "file": "drivers/dma/dmaengine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_channel_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586331328,
      "name": "__dma_async_device_channel_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void __dma_async_device_channel_unregister(struct dma_device * device, struct dma_chan * chan)
```

```json
{
  "name": "__dma_async_device_channel_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586204976,
      "name": "__dma_async_device_channel_unregister",
      "external": false,
      "loc": "drivers/dma/dmaengine.c:1107",
      "file": "drivers/dma/dmaengine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_channel_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586204976,
      "name": "__dma_async_device_channel_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void __dma_async_device_channel_unregister(struct dma_device * device, struct dma_chan * chan)
```

```json
{
  "name": "__dma_async_device_channel_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dma_async_device_channel_unregister",
      "external": false,
      "loc": "drivers/dma/dmaengine.c:1107",
      "file": "drivers/dma/dmaengine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_channel_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586711424,
      "name": "__dma_async_device_channel_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071592426909,
      "name": "__dma_async_device_channel_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __dma_async_device_channel_unregister(struct dma_device * device, struct dma_chan * chan)
```

```json
{
  "name": "__dma_async_device_channel_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dma_async_device_channel_unregister",
      "external": false,
      "loc": "drivers/dma/dmaengine.c:1102",
      "file": "drivers/dma/dmaengine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_channel_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587983952,
      "name": "__dma_async_device_channel_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071594295126,
      "name": "__dma_async_device_channel_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __dma_async_device_channel_unregister(struct dma_device * device, struct dma_chan * chan)
```

```json
{
  "name": "__dma_async_device_channel_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dma_async_device_channel_unregister",
      "external": false,
      "loc": "drivers/dma/dmaengine.c:1103",
      "file": "drivers/dma/dmaengine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_channel_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589347568,
      "name": "__dma_async_device_channel_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071596226467,
      "name": "__dma_async_device_channel_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __dma_async_device_channel_unregister(struct dma_device * device, struct dma_chan * chan)
```

```json
{
  "name": "__dma_async_device_channel_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dma_async_device_channel_unregister",
      "external": false,
      "loc": "drivers/dma/dmaengine.c:1103",
      "file": "drivers/dma/dmaengine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_channel_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589646160,
      "name": "__dma_async_device_channel_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071596754095,
      "name": "__dma_async_device_channel_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __dma_async_device_channel_unregister(struct dma_device * device, struct dma_chan * chan)
```

```json
{
  "name": "__dma_async_device_channel_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dma_async_device_channel_unregister",
      "external": false,
      "loc": "drivers/dma/dmaengine.c:1103",
      "file": "drivers/dma/dmaengine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/dmaengine.c:dma_async_device_unregister",
        "drivers/dma/dmaengine.c:dma_async_device_channel_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589956512,
      "name": "__dma_async_device_channel_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071597661849,
      "name": "__dma_async_device_channel_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __dma_async_device_channel_unregister(struct dma_device * device, struct dma_chan * chan)
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
