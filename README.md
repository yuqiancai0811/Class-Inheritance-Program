# Class-Inheritance-Program

---

###  Overview
This assignment focuses on enhancing your understanding of Java's object-oriented programming concepts like class inheritance, method overriding, and package creation. Importantly, you are not permitted to use Java built-in classes such as ArrayLists or HashMaps.

### Key Concepts
- **Class Inheritance**
- **Constructors** (Default, Parameterized, Copy)
- **Accessors and Mutators**
- **`toString()` and `equals()` Methods**
- **Unique Serial Number Implementation**

### Classes Description
- **`WheeledTransportation`**: Base class with attributes for wheels, maximum speed, and serial number.
- **`Train`**: Inherits `WheeledTransportation`, adds attributes for the number of vehicles, and the start and end stations.
- **`Metro`**: Inherits `Train`, adds total number of stops.
- **`Tram`**: Inherits `Metro`, adds year of creation.
- **`Monowheel`**: Inherits `WheeledTransportation`, adds maximum weight support.
- **`Ferry`**: Standalone class with attributes for maximum speed and load.
- **`Aircraft`**: Standalone class with attributes for price, maximum elevation.
- **`World War II Airplane`**: Inherits `Aircraft`, adds a twin-engine attribute.

### Implementation Details
- Organize classes into 6 different Java packages.
- Implement three types of constructors for each class and ensure proper constructor chaining.
- Include methods like `getNextSerialNumber()`, accessors, mutators, `toString()`, and `equals()`.
- Manage access rights properly to maintain security without compromising usability.

### Driver Programs
1. **Main Driver**: Demonstrates creation and interaction of instances, and tests using `equals()` and `toString()` methods.
2. **`findLeastAndMostExpensiveAircraft()`**: Identifies the least and most expensive aircraft from a mixed array of objects.
3. **Part II Driver**: Features `copyTheObjects()` method to demonstrate deep copying using copy constructors.
