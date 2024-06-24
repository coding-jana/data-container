# data-container
Create a generic class names DataContainer that can store any type of data.  

This class should provide methods to add, remove and retrieve data from a private collection. 

 

Requirements: 

1. Generic base class: implement a base generic class DataContainer that can store data. Use an ArrayList for internal storage. 

2. Decorator classes: create generic decorators to extend functionality of DataContainer :o  

    a) LoggingDataContainer: Adds logging functionality to add, get and remove operations. 

    b) SynchronizedDataContainer: add threads safety to the container using synchronization. 

3. Methods in base class and decorators: 

    a) Add an item to the container 

    b) T get(int index): returns the item at a specified index 

    c) Void remove(int index): removes the item at the specified index 

    d) Int size(): returns the number of items in the container 

4. Error handling: handle index out-of-bound scenarios gracefully 

5. Testing: demonstrate the usage of both the base container and decorated container in a main methof 
