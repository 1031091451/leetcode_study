# 1. hash表

```java
//初始化
HashMap<Integer, Integer> hashMap = new HashMap<Integer, Integer>();
// 查询key
hashMap.containsKey();
// 根据key查值
hashMap.get();
hashMap.getOrDefault();
//
```



# 2. 数组

```java
// 数组初始化
int ans[] = new int[length];
//计算数组长度
int length = ans.length;
```



# 3. 可变长度数组

```java
//初始化
List<List<Integer>> ans = new ArrayList<List<Integer>>();

//ArrayList转换为Array
List<int[]> ans = new ArrayList<int[]>();
ans.toArray(new int[ans.size()][2]);

```



# 4. 哈希表

```java
// 初始化
Map<Integer, Set<Integer>> map = new HashMap<Integer, Set<Integer>>();

//add
map.put(key, value);

//get
map.get(key);

//search
map.contains(key)
```



# 5. 集合

```java
// 初始化
Set<Integer> set = new HashSet<Integer>();

//add
set.add(value);

//search
seat.contains(value);
```



# 6. Arrays方法

```java
//排序,传入匿名的Comparator类
Arrays.sort(intervals, new Comparator<int[]>() {
            public int compare(int[] a, int[] b) {
                return a[0] - b[0];
            }
        });

//Arrays类排序
Arrays.sort(nums);

//将数组转换为list
Arrays.asList(nums[i], nums[left], nums[right]);

```



# 7. Deque（栈或者队列）

```java
// 初始化
private Deque<T> queue = new LinkedList<T>();

//栈的入栈和出栈
queue.offerFirst(T a); //入栈
queue.pollFirst();  //出栈

//队列的入对和出队
queue.offerLast(T a); //入队
queue.pollFirst();   //出队

//清空
queue.clear();

//顶部元素
queue.peekFirst();
```

