**Table of Contents** _generated_ with [Doctoc](https://github.com/thlorenz/doctoc)

-  [General Concepts](#general-concepts)
   -  [Motions](#motions)
      -  [`servo`](#servo)
      -  [`interpolate`](interpolate)
      -  [`move`](#move)
   -  [Naming convention](#naming-conventions)
      -  [Query commands](#query-commands)
      -  [Motion commands](#motion-commands)
      -  [Data Validity](#data-validity)
   -  [Overview](#overview)
 -   [Detailed API](#detailed-api)
   -  [General requirements](#general-requirements)
   -  [Query commands](#query-commands)
      -  [`measured_js`,measured joint state](#measured_js-measured-joint-state)
      -  [`measured_cp`, measured cartesian position](#measured_cp-measured-cartesian-position)
      
# **General Concepts**
## Motions
We identified blah blah blah
### **`servo`**
Direct access blah blah:
- **Use cases:**
   -  User has blah blah
   
### **`interpolate`**
Direct access blah blah:
- **Use cases:**
   -  User has blah blah

## **Naming Conventions**
Command names blah blah. The prefix control levele(`servo`, `interpolate` or `move`).
### Query commands
-  Space: `j` asd

## Overview
### Table
| |**Syntax**|
|-|----------|
|Control level | `servo`: direct real time <br> `interpolate`: interpolated <br> `move`: plan trajectory |
|Feedback | `measured`: direct real time <br> `measuredN`: interpolated <br> `setpoint`: plan trajectory  <br> `goal`: plan trajectory `interpolate` |

### Diagram
![Common API overview](https://www.sideshow.com/storage/product-images/903749/iron-man-mark-xlvi-concept-art-version_marvel_gallery_5c4ba7f0147d1.jpg)


