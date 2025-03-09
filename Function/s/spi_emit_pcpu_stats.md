# Function: <code>spi_emit_pcpu_stats</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
ssize_t spi_emit_pcpu_stats(struct spi_statistics * stat, char * buf, size_t offset)
```

```json
{
  "name": "spi_emit_pcpu_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591598864,
      "name": "spi_emit_pcpu_stats",
      "external": false,
      "loc": "drivers/spi/spi.c:120",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_device_transfers_split_maxsize_show",
        "drivers/spi/spi.c:spi_controller_transfers_split_maxsize_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo16_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo15_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo14_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo13_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo12_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo11_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo10_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo9_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo8_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo7_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo6_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo5_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo4_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo3_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo2_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo1_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo0_show",
        "drivers/spi/spi.c:spi_device_bytes_tx_show",
        "drivers/spi/spi.c:spi_controller_bytes_tx_show",
        "drivers/spi/spi.c:spi_device_bytes_rx_show",
        "drivers/spi/spi.c:spi_controller_bytes_rx_show",
        "drivers/spi/spi.c:spi_device_bytes_show",
        "drivers/spi/spi.c:spi_controller_bytes_show",
        "drivers/spi/spi.c:spi_device_spi_async_show",
        "drivers/spi/spi.c:spi_controller_spi_async_show",
        "drivers/spi/spi.c:spi_device_spi_sync_immediate_show",
        "drivers/spi/spi.c:spi_controller_spi_sync_immediate_show",
        "drivers/spi/spi.c:spi_device_spi_sync_show",
        "drivers/spi/spi.c:spi_controller_spi_sync_show",
        "drivers/spi/spi.c:spi_device_timedout_show",
        "drivers/spi/spi.c:spi_controller_timedout_show",
        "drivers/spi/spi.c:spi_device_errors_show",
        "drivers/spi/spi.c:spi_controller_errors_show",
        "drivers/spi/spi.c:spi_device_transfers_show",
        "drivers/spi/spi.c:spi_controller_transfers_show",
        "drivers/spi/spi.c:spi_device_messages_show",
        "drivers/spi/spi.c:spi_controller_messages_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591598864,
      "name": "spi_emit_pcpu_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
ssize_t spi_emit_pcpu_stats(struct spi_statistics * stat, char * buf, size_t offset)
```

```json
{
  "name": "spi_emit_pcpu_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592330080,
      "name": "spi_emit_pcpu_stats",
      "external": false,
      "loc": "drivers/spi/spi.c:120",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_device_transfers_split_maxsize_show",
        "drivers/spi/spi.c:spi_controller_transfers_split_maxsize_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo16_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo15_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo14_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo13_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo12_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo11_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo10_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo9_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo8_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo7_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo6_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo5_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo4_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo3_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo2_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo1_show",
        "drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show",
        "drivers/spi/spi.c:spi_controller_transfer_bytes_histo0_show",
        "drivers/spi/spi.c:spi_device_bytes_tx_show",
        "drivers/spi/spi.c:spi_controller_bytes_tx_show",
        "drivers/spi/spi.c:spi_device_bytes_rx_show",
        "drivers/spi/spi.c:spi_controller_bytes_rx_show",
        "drivers/spi/spi.c:spi_device_bytes_show",
        "drivers/spi/spi.c:spi_controller_bytes_show",
        "drivers/spi/spi.c:spi_device_spi_async_show",
        "drivers/spi/spi.c:spi_controller_spi_async_show",
        "drivers/spi/spi.c:spi_device_spi_sync_immediate_show",
        "drivers/spi/spi.c:spi_controller_spi_sync_immediate_show",
        "drivers/spi/spi.c:spi_device_spi_sync_show",
        "drivers/spi/spi.c:spi_controller_spi_sync_show",
        "drivers/spi/spi.c:spi_device_timedout_show",
        "drivers/spi/spi.c:spi_controller_timedout_show",
        "drivers/spi/spi.c:spi_device_errors_show",
        "drivers/spi/spi.c:spi_controller_errors_show",
        "drivers/spi/spi.c:spi_device_transfers_show",
        "drivers/spi/spi.c:spi_controller_transfers_show",
        "drivers/spi/spi.c:spi_device_messages_show",
        "drivers/spi/spi.c:spi_controller_messages_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592330080,
      "name": "spi_emit_pcpu_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
ssize_t spi_emit_pcpu_stats(struct spi_statistics * stat, char * buf, size_t offset)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
