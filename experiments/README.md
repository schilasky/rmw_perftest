experiment 002:

| Paramter               | Setting                                                                                                                   |
|------------------------|---------------------------------------------------------------------------------------------------------------------------|
| RMW Implementations    | `rmw_cyclonedds_cpp`<br>`rmw_fastrtps_cpp`                                                                                |
| QOS                    | Reliability: `BEST_EFFORT`<br>Durability: `VOLATILE`<br>History kind: `KEEP_ALL` (Depth: 1000)<br>Sync. pub/sub: 0        |
| Number of publishers   | 1                                                                                                                         |
| Number of subscribers  | 1 / 5 / 10                                                                                                                |
| Publishing rate        | 10 / 50 / 500 / 1000                                                                                                      |
| Maximum runtime (sec)  | 130                                                                                                                       |
| Ignore time (sec)      | 10                                                                                                                        |

experiment 003:

| Paramter               | Setting                                                                                                                   |
|------------------------|---------------------------------------------------------------------------------------------------------------------------|
| RMW Implementations    | `rmw_cyclonedds_cpp`<br>`rmw_ecal_dynamic_cpp`<br>`rmw_fastrtps_cpp`                                                      |
| QOS                    | Reliability: `BEST_EFFORT`<br>Durability: `VOLATILE`<br>History kind: `KEEP_LAST` (Depth: 1)<br>Sync. pub/sub: 0          |
| Number of publishers   | 1                                                                                                                         |
| Number of subscribers  | 1 / 5 / 10                                                                                                                |
| Publishing rate        | 10 / 50 / 500 / 1000                                                                                                      |
| Maximum runtime (sec)  | 130                                                                                                                       |
| Ignore time (sec)      | 10                                                                                                                        |

experiment 004:

| Paramter               | Setting                                                                                                                   |
|------------------------|---------------------------------------------------------------------------------------------------------------------------|
| RMW Implementations    | `rmw_cyclonedds_cpp (0.7.6-1)`<br>`rmw_fastrtps_cpp (1.2.4-1)`                                                            |
| QOS                    | Reliability: `BEST_EFFORT`<br>Durability: `VOLATILE`<br>History kind: `KEEP_LAST` (Depth: 1)<br>Sync. pub/sub: 0          |
| Number of publishers   | 1                                                                                                                         |
| Number of subscribers  | 1 / 5 / 10                                                                                                                |
| Publishing rate        | 10                                                                                                                        |
| Maximum runtime (sec)  | 130                                                                                                                       |
| Ignore time (sec)      | 10                                                                                                                        |
