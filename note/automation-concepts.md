# Automation Concepts

## Glossary
**FDS**: Functional Design Specification
> FDS is a document that describes how a process or a control system will operate. It does not contain any highly technical detail, rather, it describes how the proposed system will operate, how people will interact with it and what to expect when different operational scenarios occur.

## "USA": Understand, Simplify, Automate
1. **U**nderstand Process
2. **S**implify Process
3. **A**utomate Process

## "3AMS": Automation Migration Strategy (MP/AP/AIP)
- **Phase 1:** **M**anual **P**roduction
  - *Quick and low-cost tooling.*
- **Phase 2:** **A**utomated **P**roduction
  - *Single automated cells with manual handling of the product between workstations.*
- **Phase 3:** **A**utomated **I**ntegrated **P**roduction
  - *Multi station automated system with automated material handling between stations.*

## 10 Strategies for Automation and Production Systems
### 1. Specialization of operations
> The first strategy involves the use of special-purpose equipment designed to perform one operation with the greatest possible efficiency. 

This is analogous to the concept of labor specialization, which is employed to improve labor
productivity.

### 2. Combined operations
> Production occurs as a sequence of operations.

Complex parts may require dozens, or even hundreds, of processing steps. The strategy of combined operations involves reducing the number of distinct production machines or workstations through which the part must be routed.

This is accomplished by performing more than one operation at a given machine , thereby reducing the number of separate machines needed. Since each machine typically involves a setup, setup time can usually be saved as a consequence of this strategy. Material handling effort and non-operation time are also reduced. Manufacturing lead time is reduced for better customer service.

### 3. Simultaneous operations
> A logical extension of the combined operations strategy is to simultaneously perform the operations that are combined at one workstation.

In effect, two or more processing (or assembly) operations are being performed
simultaneously on the same workpart, thus reducing total processing time.

### 4. Integration of operations
> Another strategy is to link several workstations together into a single integrated mechanism, using automated work handling devices to transfer parts between stations.

In effect, this reduces the number of separate machines through which the product must be scheduled. With more than one workstation, several parts can be processed simultaneously, thereby increasing
the overall output of the system

### 5. Increased flexibility
> This strategy attempts to achieve maximum utilization of equipment for job shop and medium volume situations by using the same equipment for a variety of parts or products.

It involves the use of the flexible automation concepts. Prime objectives are to reduce setup time and programming time for the production machine.This normally
translates into lower manufacturing lead time and less work-in-process.

### 6. Improved material handling and storage
> A great opportunity for reducing nonpro-ductive time exists in the use of automated material handling and storage systems.

Typical benefits include reduced work-in-process and shorter manufacturing lead times.

### 7. On-line inspection
> Inspection for quality of work is traditionally performed after the process is completed. 

This means that any poor quality product has already been produced by the time it is inspected. Incorporating inspection into the manufacturing process permits corrections to the process as the product is being made. This reduces scrap and brings the overall quality of product closer to the nominal specifications intended by the designer.

### 8. Process control and optimization
> This includes a wide range of control schemes intended to operate the individual processes and associated equipment more efficiently.

By this strategy, the individual process times can be reduced and product quality
improved.

### 9. Plant operations control
> Whereas the previous strategy was concerned with the control of the individual manufacturing process, this strategy is concerned with control at the plant level.

It attempts to manage and coordinate the aggregate operations in the plant more efficiently. Its implementation usually involves a high level of computer networking within the factory.

### 10. Computer-integrated manufacturing (CIM)
> Taking the previous strategy one level higher, we have the integration of factory operations with engineering design and the business functions of the firm.

**CIM** involves extensive use of:
1. Computer applications,
2. Computer data bases, and
3. Computer networking throughout the enterprise.

## Manufacturing Operations
> Converting a raw material into a finished product require several steps and processes.

For example, a plant engaged in making discrete products has following activities going on:
- Processing and assembly operations
- Material handling
- Inspection and test
- Coordination and control

### Constinuous Production (Mass Production)
> Used when raw material doesn't change & the process is carried out continuously to produce the output.

Manufacturing operation is carried out on a continuous input of raw material to produce a batch of output products, manufacturing operations do not vary and should produce similar products. Production must fully stop to retool if the product is to change.

### Cellular Production
> The goal of cellular manufacturing is to move as quickly as possible, make a wide variety of similar products, while making as little waste as possible.

Cellular manufacturing involves the use of multiple "cells" in an assembly line fashion. Each of these cells is composed of one or multiple different machines which accomplish a certain task. The product moves from one cell to the next, each station completing part of the manufacturing process. 

Often the cells are arranged in a "U-shape" design because this allows for the overseer to move less and have the ability to more readily watch over the entire process.

One of the biggest advantages of cellular manufacturing is the amount of flexibility that it has. Since most of the machines are automatic, simple changes can be made very rapidly.

This allows for a variety of scaling for a product, minor changes to the overall design, and in extreme cases, entirely changing the overall design. These changes, although tedious, can be accomplished extremely quickly and precisely.

### Batch Production (Batch Mode)
> Used when there is some variation between the final products to be manufactured.

Manufacturing operation is carried out on a batch of raw material to produce a batch of output products, manufacturing operations may vary from batch to batch to produce different products. Production regularly stops to retool whenever there is a new batch.

### Processing and Assembly Operations
> A **Processing Operation** *transforms a work material*
> from one state of completion to a more advanced state
> that is closer to the final desired *part* or *product*.
> 
> An **Assembly Operation** *joins two or more components*
> to create a new entity, called *assembly* or *subassembly*.

- Other Factory Operations
  - Material Handling and Storage
    - Moving and storing materials between processing and/or assembly operations are usually required.
  - Inspection and Testing
    - These are quality control activities.
  - Coordination and Control
    - Regulation of individual processing and assembly operations and the management of plant-level activities.

### Production Facilities
> A manufacturing company attempts to organize its facilities in the most efficient way to serve the mission of each plant.

Production quantity is the most important factor when organization of the manufacturing facilities is considered.

**Low Production (Manual Production):**
- Quantities in the range of **1 to 100** units
- High Variety because it's easy to change the manufacturing system when few units are produced.
- Humans are best used at this stage, they are dextrous, can task switch very quickly, & excell at variety.

**Medium Production (Batch or Cellular Production):**
- Quantities in the range of **100 to 10,000** units
- Medium Variety because it's somewhat difficult to change the manufacturing system when an moderate amount units are produced.
- Humans & Machines or minor automation are best used at this stage to increase productivity beyond human capabilities.

**High Production (Mass Production):**
- Quantities **above 10,000** units (*not achievable via manual labor*)
- Low Variety because it's hard to change the manufacturing system when many units are produced.
- Full automation with machines and a continuous stream is best used at this stage, to maximize productivity.