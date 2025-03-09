# Struct: <code>rtnl_link_stats64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
    __u64 rx_otherhost_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
    __u64 rx_otherhost_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
    __u64 rx_otherhost_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
    __u64 rx_otherhost_dropped;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rtnl_link_stats64 {
    __u64 rx_packets;
    __u64 tx_packets;
    __u64 rx_bytes;
    __u64 tx_bytes;
    __u64 rx_errors;
    __u64 tx_errors;
    __u64 rx_dropped;
    __u64 tx_dropped;
    __u64 multicast;
    __u64 collisions;
    __u64 rx_length_errors;
    __u64 rx_over_errors;
    __u64 rx_crc_errors;
    __u64 rx_frame_errors;
    __u64 rx_fifo_errors;
    __u64 rx_missed_errors;
    __u64 tx_aborted_errors;
    __u64 tx_carrier_errors;
    __u64 tx_fifo_errors;
    __u64 tx_heartbeat_errors;
    __u64 tx_window_errors;
    __u64 rx_compressed;
    __u64 tx_compressed;
    __u64 rx_nohandler;
}
```
</details>
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
<b>Field added. </b>
<code>__u64 rx_nohandler</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u64 rx_otherhost_dropped</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
