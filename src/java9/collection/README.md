# Collection Factory Methods
With Java 9, new factory methods are added to List, Set and Map interfaces to create immutable instances.

## Example
#### Local DateTime API
Old way to create collections
```
Set<String> set = new HashSet<>();
set.add("A");
set.add("B");
set.add("C");
set = Collections.unmodifiableSet(set);
System.out.println(set);
List<String> list = new ArrayList<>();
```


