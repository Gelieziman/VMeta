# VMeta 
# QoS  Dataset
## Dataset Description

### File Inventory
- `virtual.csv`: Virtual scene QoS data；type = 1
- `meta.csv`: actual demand service QoS data ；type = 0


## Field Specification
7 monitoring dimensions included:

| Field Name            | Type  | Unit     | Description                     |
|-----------------------|-------|----------|---------------------------------|
| CPU clock(MHZ)        | int   | MHz      | Processor base frequency        |
| CPU usage(%)          | int   | Percent  | Real-time CPU utilization       |
| video memory(MB)      | int   | MB       | Graphics memory allocation      |
| GPU usage(%)          | int   | Percent  | Graphics processor utilization  |
| memory(MB)            | int   | MB       | System memory consumption       |
| FPS                   | int   | FPS      | Frame refresh rate              |
| Type                  | int   | -        | Service type identifier (fixed:1)|

## Use Cases
1. ​**Advancing Metaverse Research**​  
   - Empowering data-driven approaches for virtual ecosystem development
   - Facilitating predictive modeling of mixed-reality environments

2. ​**QoS Innovation Framework**​  
   - Providing novel multidimensional evaluation perspectives
   - Enabling cross-platform performance benchmarking

3. ​**User Behavior Analytics**​  
   - Supporting behavioral pattern mining through QoS metrics
   - Enabling correlation analysis between system performance and user engagement

4. ​**Privacy Protection Catalyst**​  
   - Revealing potential data exposure risks through resource monitoring
   - Inspiring new authentication paradigms for virtual asset protection

## Data Samples
### virtual.csv
```csv
CPU clock(MHZ),CPU usage(%),video memory(MB),GPU usage(%),memory(MB),FPS,Type
3012,37,2345,28,6543,98,1
2889,42,1987,15,6321,88,1

