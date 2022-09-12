# HashMap

* Map's type argument cannot be of primitive type.

  ```java
    // Incorrect
    Map<int, int> nums = new HashMap<>();

    // Correct
    Map<Integer, Integer> nums = new HashMap<>();
  ```
* There is no sorting available in HashMap. Refer to [this article](https://www.baeldung.com/java-hashmap-sort) on how to sort hashmaps.
