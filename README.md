<article class="markdown-body entry-content" itemprop="text">

# [](#后端架构师技术图谱)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Backend Architect Technical Atlas</font></font>

[![Knowledge Sharing Agreement (CC Agreement)](https://camo.githubusercontent.com/95c3d7ef0b5da8445087e462514063675f79321d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4372656174697665253230436f6d6d6f6e732d4443334432342e737667)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)

**<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Last updated on 20180502</font></font>**

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">data structure</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">queue</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E9%98%9F%E5%88%97)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">set</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E9%9B%86%E5%90%88)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Lists, arrays</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E9%93%BE%E8%A1%A8%E6%95%B0%E7%BB%84)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Dictionary, associative array</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%AD%97%E5%85%B8%E5%85%B3%E8%81%94%E6%95%B0%E7%BB%84)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Stack</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%A0%88)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">tree</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%A0%91)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Binary tree</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%BA%8C%E5%8F%89%E6%A0%91)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Complete Binary Tree</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%AE%8C%E5%85%A8%E4%BA%8C%E5%8F%89%E6%A0%91)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Balanced binary tree</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%B9%B3%E8%A1%A1%E4%BA%8C%E5%8F%89%E6%A0%91)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Binary Search Tree (BST)</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%BA%8C%E5%8F%89%E6%9F%A5%E6%89%BE%E6%A0%91bst)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Red black tree</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%BA%A2%E9%BB%91%E6%A0%91)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">B-, B+, B* trees</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#b-bb%E6%A0%91)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LSM tree</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#lsm-%E6%A0%91)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BitSet</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#bitset)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Common algorithms</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%B8%B8%E7%94%A8%E7%AE%97%E6%B3%95)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sorting, finding algorithm</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%8E%92%E5%BA%8F%E6%9F%A5%E6%89%BE%E7%AE%97%E6%B3%95)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Select sort</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E9%80%89%E6%8B%A9%E6%8E%92%E5%BA%8F)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bubble Sort</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%86%92%E6%B3%A1%E6%8E%92%E5%BA%8F)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Insert sort</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%8F%92%E5%85%A5%E6%8E%92%E5%BA%8F)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Quick sort</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%BF%AB%E9%80%9F%E6%8E%92%E5%BA%8F)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Merge sort</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%BD%92%E5%B9%B6%E6%8E%92%E5%BA%8F)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hill Sort</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%B8%8C%E5%B0%94%E6%8E%92%E5%BA%8F)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Heap sort</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%A0%86%E6%8E%92%E5%BA%8F)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Counting sort</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%AE%A1%E6%95%B0%E6%8E%92%E5%BA%8F)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bucket sort</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%A1%B6%E6%8E%92%E5%BA%8F)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cardinal sort</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%9F%BA%E6%95%B0%E6%8E%92%E5%BA%8F)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Binary search</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%BA%8C%E5%88%86%E6%9F%A5%E6%89%BE)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sorting tools in Java</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#java-%E4%B8%AD%E7%9A%84%E6%8E%92%E5%BA%8F%E5%B7%A5%E5%85%B7)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bloom filter</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%B8%83%E9%9A%86%E8%BF%87%E6%BB%A4%E5%99%A8)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">String comparison</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%AD%97%E7%AC%A6%E4%B8%B2%E6%AF%94%E8%BE%83)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KMP algorithm</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#kmp-%E7%AE%97%E6%B3%95)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Depth first, breadth first</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%B7%B1%E5%BA%A6%E4%BC%98%E5%85%88%E5%B9%BF%E5%BA%A6%E4%BC%98%E5%85%88)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">how are you</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Backtracking algorithm</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%9B%9E%E6%BA%AF%E7%AE%97%E6%B3%95)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pruning algorithm</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%89%AA%E6%9E%9D%E7%AE%97%E6%B3%95)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Dynamic planning</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Naive Bayes</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%9C%B4%E7%B4%A0%E8%B4%9D%E5%8F%B6%E6%96%AF)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Recommended algorithm</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%8E%A8%E8%8D%90%E7%AE%97%E6%B3%95)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Minimum spanning tree algorithm</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%9C%80%E5%B0%8F%E7%94%9F%E6%88%90%E6%A0%91%E7%AE%97%E6%B3%95)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Shortest path algorithm</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%9C%80%E7%9F%AD%E8%B7%AF%E5%BE%84%E7%AE%97%E6%B3%95)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Concurrent</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%B9%B6%E5%8F%91)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Multithreading</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%A4%9A%E7%BA%BF%E7%A8%8B)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Thread safety</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%BA%BF%E7%A8%8B%E5%AE%89%E5%85%A8)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Consistency, transaction</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%B8%80%E8%87%B4%E6%80%A7%E4%BA%8B%E5%8A%A1)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Transaction ACID features</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%BA%8B%E5%8A%A1-acid-%E7%89%B9%E6%80%A7)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Transaction isolation level</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%BA%8B%E5%8A%A1%E7%9A%84%E9%9A%94%E7%A6%BB%E7%BA%A7%E5%88%AB)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MVCC</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#mvcc)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">lock</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E9%94%81)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Locks and synchronization classes in Java</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#java%E4%B8%AD%E7%9A%84%E9%94%81%E5%92%8C%E5%90%8C%E6%AD%A5%E7%B1%BB)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Fair lock & non-fair lock</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%85%AC%E5%B9%B3%E9%94%81--%E9%9D%9E%E5%85%AC%E5%B9%B3%E9%94%81)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pessimistic lock</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%82%B2%E8%A7%82%E9%94%81)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Optimistic Lock & CAS</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%B9%90%E8%A7%82%E9%94%81--cas)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ABA issues</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#aba-%E9%97%AE%E9%A2%98)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CopyOnWrite container</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#copyonwrite%E5%AE%B9%E5%99%A8)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RingBuffer</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#ringbuffer)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reentrant Locks & Non-Reentrant Locks</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%8F%AF%E9%87%8D%E5%85%A5%E9%94%81--%E4%B8%8D%E5%8F%AF%E9%87%8D%E5%85%A5%E9%94%81)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mutexes & shared locks</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%BA%92%E6%96%A5%E9%94%81--%E5%85%B1%E4%BA%AB%E9%94%81)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Deadlock</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%AD%BB%E9%94%81)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">operating system</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Principle of computer</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%8E%9F%E7%90%86)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CPU</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#cpu)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Multi-level cache</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%A4%9A%E7%BA%A7%E7%BC%93%E5%AD%98)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">process</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%BF%9B%E7%A8%8B)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Threads</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%BA%BF%E7%A8%8B)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Correspondence</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%8D%8F%E7%A8%8B)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#linux)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Design Patterns</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Six principles of design patterns</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F%E7%9A%84%E5%85%AD%E5%A4%A7%E5%8E%9F%E5%88%99)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">23 common design patterns</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#23%E7%A7%8D%E5%B8%B8%E8%A7%81%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Application scenario</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%BA%94%E7%94%A8%E5%9C%BA%E6%99%AF)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Singleton mode</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%8D%95%E4%BE%8B%E6%A8%A1%E5%BC%8F)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Chain of responsibility model</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%B4%A3%E4%BB%BB%E9%93%BE%E6%A8%A1%E5%BC%8F)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MVC</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#mvc)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IOC</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#ioc)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AOP</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#aop)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">UML</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#uml)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Microservice idea</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%BE%AE%E6%9C%8D%E5%8A%A1%E6%80%9D%E6%83%B3)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Conway Law</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%BA%B7%E5%A8%81%E5%AE%9A%E5%BE%8B)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Operation & Statistics & Technical Support</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%BF%90%E7%BB%B4--%E7%BB%9F%E8%AE%A1--%E6%8A%80%E6%9C%AF%E6%94%AF%E6%8C%81)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">General monitoring</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%B8%B8%E8%A7%84%E7%9B%91%E6%8E%A7)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">APM</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#apm)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Statistical Analysis</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%BB%9F%E8%AE%A1%E5%88%86%E6%9E%90)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Continuous Integration (CI/CD)</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%8C%81%E7%BB%AD%E9%9B%86%E6%88%90cicd)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jenkins</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#jenkins)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Environmental separation</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%8E%AF%E5%A2%83%E5%88%86%E7%A6%BB)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Automation operation and maintenance</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%87%AA%E5%8A%A8%E5%8C%96%E8%BF%90%E7%BB%B4)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ansible</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#ansible)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Puppet</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#puppet)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Chef</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#chef)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">test</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%B5%8B%E8%AF%95)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TDD theory</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#tdd-%E7%90%86%E8%AE%BA)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">unit test</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%8D%95%E5%85%83%E6%B5%8B%E8%AF%95)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pressure test</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%8E%8B%E5%8A%9B%E6%B5%8B%E8%AF%95)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Full-link pressure test</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%85%A8%E9%93%BE%E8%B7%AF%E5%8E%8B%E6%B5%8B)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">A/B, grayscale, blue-green test</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#ab-%E7%81%B0%E5%BA%A6%E8%93%9D%E7%BB%BF%E6%B5%8B%E8%AF%95)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Virtualization</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%99%9A%E6%8B%9F%E5%8C%96)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KVM</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#kvm)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Xen</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#xen)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenVZ</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#openvz)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Container technology</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%AE%B9%E5%99%A8%E6%8A%80%E6%9C%AF)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#docker)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cloud technology</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%BA%91%E6%8A%80%E6%9C%AF)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenStack</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#openstack)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DevOps</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#devops)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Document management</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%96%87%E6%A1%A3%E7%AE%A1%E7%90%86)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Middleware</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%B8%AD%E9%97%B4%E4%BB%B6)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Web Server</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#web-server)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nginx</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#nginx)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenResty</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#openresty)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apache Httpd</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#apache-httpd)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tomcat</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#tomcat)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Architecture principle</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%9E%B6%E6%9E%84%E5%8E%9F%E7%90%86)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tuning plan</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%B0%83%E4%BC%98%E6%96%B9%E6%A1%88)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jetty</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#jetty)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Caching</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%BC%93%E5%AD%98)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Local cache</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%9C%AC%E5%9C%B0%E7%BC%93%E5%AD%98)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Client Cache</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%AE%A2%E6%88%B7%E7%AB%AF%E7%BC%93%E5%AD%98)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Server cache</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%9C%8D%E5%8A%A1%E7%AB%AF%E7%BC%93%E5%AD%98)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Memcached</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#memcached)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Redis</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#redis)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Structure</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%9E%B6%E6%9E%84)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Recovery strategy</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%9B%9E%E6%94%B6%E7%AD%96%E7%95%A5)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tair</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#tair)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">message queue</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%B6%88%E6%81%AF%E9%98%9F%E5%88%97)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Message bus</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%B6%88%E6%81%AF%E6%80%BB%E7%BA%BF)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Order of messages</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%B6%88%E6%81%AF%E7%9A%84%E9%A1%BA%E5%BA%8F)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RabbitMQ</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#rabbitmq)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RocketMQ</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#rocketmq)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ActiveMQ</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#activemq)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kafka</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#kafka)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Redis message push</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#redis-%E6%B6%88%E6%81%AF%E6%8E%A8%E9%80%81)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ZeroMQ</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#zeromq)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scheduled scheduling</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%AE%9A%E6%97%B6%E8%B0%83%E5%BA%A6)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Stand-alone scheduled scheduling</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%8D%95%E6%9C%BA%E5%AE%9A%E6%97%B6%E8%B0%83%E5%BA%A6)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed timing scheduling</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%88%86%E5%B8%83%E5%BC%8F%E5%AE%9A%E6%97%B6%E8%B0%83%E5%BA%A6)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RPC</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#rpc)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Dubbo</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#dubbo)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Thrift</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#thrift)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gRPC</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#grpc)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Database middleware</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%95%B0%E6%8D%AE%E5%BA%93%E4%B8%AD%E9%97%B4%E4%BB%B6)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sharding Jdbc</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#sharding-jdbc)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Log system</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%97%A5%E5%BF%97%E7%B3%BB%E7%BB%9F)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Log collection</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%97%A5%E5%BF%97%E6%90%9C%E9%9B%86)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Configuration Center</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E9%85%8D%E7%BD%AE%E4%B8%AD%E5%BF%83)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API Gateway</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#api-%E7%BD%91%E5%85%B3)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The internet</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%BD%91%E7%BB%9C)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">protocol</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%8D%8F%E8%AE%AE)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OSI Layer 7 Protocol</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#osi-%E4%B8%83%E5%B1%82%E5%8D%8F%E8%AE%AE)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TCP/IP</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#tcpip)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HTTP</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#http)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HTTP2.0</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#http20)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HTTPS</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#https)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Network model</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%BD%91%E7%BB%9C%E6%A8%A1%E5%9E%8B)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Epoll</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#epoll)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java NIO</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#java-nio)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kqueue</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#kqueue)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Connections and short connections</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%BF%9E%E6%8E%A5%E5%92%8C%E7%9F%AD%E8%BF%9E%E6%8E%A5)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">frame</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%A1%86%E6%9E%B6)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zero-copy</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E9%9B%B6%E6%8B%B7%E8%B4%9Dzero-copy)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Serialization (binary protocol)</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%BA%8F%E5%88%97%E5%8C%96%E4%BA%8C%E8%BF%9B%E5%88%B6%E5%8D%8F%E8%AE%AE)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hessian</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#hessian)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Protobuf</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#protobuf)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">database</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%95%B0%E6%8D%AE%E5%BA%93)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Basic theory</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%9F%BA%E7%A1%80%E7%90%86%E8%AE%BA)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Three paradigms of database design</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%95%B0%E6%8D%AE%E5%BA%93%E8%AE%BE%E8%AE%A1%E7%9A%84%E4%B8%89%E5%A4%A7%E8%8C%83%E5%BC%8F)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MySQL</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#mysql)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">principle</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%8E%9F%E7%90%86)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InnoDB</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#innodb)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">optimization</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%BC%98%E5%8C%96)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">index</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%B4%A2%E5%BC%95)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Clustered index, non-clustered index</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%81%9A%E9%9B%86%E7%B4%A2%E5%BC%95-%E9%9D%9E%E8%81%9A%E9%9B%86%E7%B4%A2%E5%BC%95)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Composite index</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%A4%8D%E5%90%88%E7%B4%A2%E5%BC%95)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Adaptive Hash Index (AHI)</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%87%AA%E9%80%82%E5%BA%94%E5%93%88%E5%B8%8C%E7%B4%A2%E5%BC%95ahi)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Explain</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#explain)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NoSQL</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#nosql)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MongoDB</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#mongodb)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hbase</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#hbase)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">search engine</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%90%9C%E7%B4%A2%E5%BC%95%E6%93%8E)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Search Engine Principle</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%90%9C%E7%B4%A2%E5%BC%95%E6%93%8E%E5%8E%9F%E7%90%86)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Lucene</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#lucene)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Elasticsearch</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#elasticsearch)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Solr</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#solr)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sphinx</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#sphinx)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">performance</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%80%A7%E8%83%BD)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Performance Optimization Methodology</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95%E8%AE%BA)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Capacity assessment</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%AE%B9%E9%87%8F%E8%AF%84%E4%BC%B0)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CDN network</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#cdn-%E7%BD%91%E7%BB%9C)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">connection pool</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%BF%9E%E6%8E%A5%E6%B1%A0)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Performance tuning</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%80%A7%E8%83%BD%E8%B0%83%E4%BC%98)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Big Data</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%A4%A7%E6%95%B0%E6%8D%AE)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flow calculation</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%B5%81%E5%BC%8F%E8%AE%A1%E7%AE%97)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Storm</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#storm)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flink</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#flink)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kafka Stream</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#kafka-stream)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Application scenario</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%BA%94%E7%94%A8%E5%9C%BA%E6%99%AF-1)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hadoop</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#hadoop)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HDFS</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#hdfs)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MapReduce</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#mapreduce)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Yarn</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#yarn)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Spark</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#spark)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Safety</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%AE%89%E5%85%A8)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Web security</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#web-%E5%AE%89%E5%85%A8)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">XSS</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#xss)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CSRF</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#csrf)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SQL injection</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#sql-%E6%B3%A8%E5%85%A5)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hash Dos</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#hash-dos)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Script injection</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%84%9A%E6%9C%AC%E6%B3%A8%E5%85%A5)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Vulnerability Scan Tool</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%BC%8F%E6%B4%9E%E6%89%AB%E6%8F%8F%E5%B7%A5%E5%85%B7)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Verification code</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E9%AA%8C%E8%AF%81%E7%A0%81)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DDoS protection</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#ddos-%E9%98%B2%E8%8C%83)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">User privacy protection</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%94%A8%E6%88%B7%E9%9A%90%E7%A7%81%E4%BF%A1%E6%81%AF%E4%BF%9D%E6%8A%A4)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Serialization vulnerability</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">encrypt and decode</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%8A%A0%E5%AF%86%E8%A7%A3%E5%AF%86)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Symmetric encryption</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%AF%B9%E7%A7%B0%E5%8A%A0%E5%AF%86)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hash algorithm</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%93%88%E5%B8%8C%E7%AE%97%E6%B3%95)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Asymmetric encryption</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E9%9D%9E%E5%AF%B9%E7%A7%B0%E5%8A%A0%E5%AF%86)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Server security</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%9C%8D%E5%8A%A1%E5%99%A8%E5%AE%89%E5%85%A8)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Data Security</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%95%B0%E6%8D%AE%E5%AE%89%E5%85%A8)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">data backup</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%95%B0%E6%8D%AE%E5%A4%87%E4%BB%BD)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Network isolation</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%BD%91%E7%BB%9C%E9%9A%94%E7%A6%BB)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Internal and external network separation</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%86%85%E5%A4%96%E7%BD%91%E5%88%86%E7%A6%BB)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Login board</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%99%BB%E5%BD%95%E8%B7%B3%E6%9D%BF%E6%9C%BA)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Authorization, certification</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%8E%88%E6%9D%83%E8%AE%A4%E8%AF%81)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RBAC</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#rbac)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OAuth2.0</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#oauth20)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Two-factor authentication (2FA)</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%8F%8C%E5%9B%A0%E7%B4%A0%E8%AE%A4%E8%AF%812fa)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Single sign-on (SSO)</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%8D%95%E7%82%B9%E7%99%BB%E5%BD%95sso)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Common open source framework</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%B8%B8%E7%94%A8%E5%BC%80%E6%BA%90%E6%A1%86%E6%9E%B6)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open Source Agreement</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%BC%80%E6%BA%90%E5%8D%8F%E8%AE%AE)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Logging framework</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%97%A5%E5%BF%97%E6%A1%86%E6%9E%B6)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Log4j, Log4j2</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#log4jlog4j2)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Logback</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#logback)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ORM</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#orm)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Network framework</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%BD%91%E7%BB%9C%E6%A1%86%E6%9E%B6)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Web framework</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#web-%E6%A1%86%E6%9E%B6)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Spring family</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#spring-%E5%AE%B6%E6%97%8F)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tool frame</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%B7%A5%E5%85%B7%E6%A1%86%E6%9E%B6)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed design</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%88%86%E5%B8%83%E5%BC%8F%E8%AE%BE%E8%AE%A1)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scalable design</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%89%A9%E5%B1%95%E6%80%A7%E8%AE%BE%E8%AE%A1)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Stability & High Availability</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%A8%B3%E5%AE%9A%E6%80%A7--%E9%AB%98%E5%8F%AF%E7%94%A8)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hardware load balancing</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%A1%AC%E4%BB%B6%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Software load balancing</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%BD%AF%E4%BB%B6%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Limiting</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E9%99%90%E6%B5%81)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Application layer disaster recovery</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%BA%94%E7%94%A8%E5%B1%82%E5%AE%B9%E7%81%BE)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cross-room disaster recovery</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%B7%A8%E6%9C%BA%E6%88%BF%E5%AE%B9%E7%81%BE)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Disaster recovery drill process</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%AE%B9%E7%81%BE%E6%BC%94%E7%BB%83%E6%B5%81%E7%A8%8B)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Smooth start</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%B9%B3%E6%BB%91%E5%90%AF%E5%8A%A8)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Database expansion</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%95%B0%E6%8D%AE%E5%BA%93%E6%89%A9%E5%B1%95)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Read-write separation mode</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%AF%BB%E5%86%99%E5%88%86%E7%A6%BB%E6%A8%A1%E5%BC%8F)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Fragmentation mode</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%88%86%E7%89%87%E6%A8%A1%E5%BC%8F)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Service governance</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%9C%8D%E5%8A%A1%E6%B2%BB%E7%90%86)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Service Registration and Discovery</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%9C%8D%E5%8A%A1%E6%B3%A8%E5%86%8C%E4%B8%8E%E5%8F%91%E7%8E%B0)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Service Routing Control</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%9C%8D%E5%8A%A1%E8%B7%AF%E7%94%B1%E6%8E%A7%E5%88%B6)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed consensus</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%88%86%E5%B8%83%E5%BC%8F%E4%B8%80%E8%87%B4)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CAP and BASE theory</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#cap-%E4%B8%8E-base-%E7%90%86%E8%AE%BA)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed lock</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%88%86%E5%B8%83%E5%BC%8F%E9%94%81)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed consensus algorithm</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%88%86%E5%B8%83%E5%BC%8F%E4%B8%80%E8%87%B4%E6%80%A7%E7%AE%97%E6%B3%95)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PAXOS</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#paxos)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zab</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#zab)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Raft</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#raft)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gossip</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#gossip)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Two-phase commit, multi-phase commit</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%B8%A4%E9%98%B6%E6%AE%B5%E6%8F%90%E4%BA%A4%E5%A4%9A%E9%98%B6%E6%AE%B5%E6%8F%90%E4%BA%A4)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Idempotent</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%B9%82%E7%AD%89)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed consensus solution</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%88%86%E5%B8%83%E5%BC%8F%E4%B8%80%E8%87%B4%E6%96%B9%E6%A1%88)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed Leader node election</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%88%86%E5%B8%83%E5%BC%8F-leader-%E8%8A%82%E7%82%B9%E9%80%89%E4%B8%BE)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TCC (Try/Confirm/Cancel) Flexible Transactions</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#tcctryconfirmcancel-%E6%9F%94%E6%80%A7%E4%BA%8B%E5%8A%A1)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed File System</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%88%86%E5%B8%83%E5%BC%8F%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Unique ID generation</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%94%AF%E4%B8%80id-%E7%94%9F%E6%88%90)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Globally unique ID</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%85%A8%E5%B1%80%E5%94%AF%E4%B8%80id)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Consistent hashing algorithm</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%B8%80%E8%87%B4%E6%80%A7hash%E7%AE%97%E6%B3%95)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Design Ideas & Development Models</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%AE%BE%E8%AE%A1%E6%80%9D%E6%83%B3--%E5%BC%80%E5%8F%91%E6%A8%A1%E5%BC%8F)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DDD (Domain-driven Design - Domain Driven Design)</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#ddddomain-driven-design---%E9%A2%86%E5%9F%9F%E9%A9%B1%E5%8A%A8%E8%AE%BE%E8%AE%A1)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Command Query Separation of Duties (CQRS)</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%91%BD%E4%BB%A4%E6%9F%A5%E8%AF%A2%E8%81%8C%E8%B4%A3%E5%88%86%E7%A6%BBcqrs)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Anemia, congestive model</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%B4%AB%E8%A1%80%E5%85%85%E8%A1%80%E6%A8%A1%E5%9E%8B)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Actor mode</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#actor-%E6%A8%A1%E5%BC%8F)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reactive programming</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%93%8D%E5%BA%94%E5%BC%8F%E7%BC%96%E7%A8%8B)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reactor</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#reactor)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RxJava</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#rxjava)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Vert.x</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#vertx)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DODAF2.0</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#dodaf20)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Serverless</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#serverless)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Service Mesh</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#service-mesh)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Project management</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E9%A1%B9%E7%9B%AE%E7%AE%A1%E7%90%86)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Architecture review</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%9E%B6%E6%9E%84%E8%AF%84%E5%AE%A1)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reconstruction</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E9%87%8D%E6%9E%84)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Code specification</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%BB%A3%E7%A0%81%E8%A7%84%E8%8C%83)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Code Review</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%BB%A3%E7%A0%81-review)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RUP</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#rup)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kanban Management</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%9C%8B%E6%9D%BF%E7%AE%A1%E7%90%86)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SCRUM</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#scrum)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Agile development</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%95%8F%E6%8D%B7%E5%BC%80%E5%8F%91)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Extreme Programming (XP)</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%9E%81%E9%99%90%E7%BC%96%E7%A8%8Bxp)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pair programming</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%BB%93%E5%AF%B9%E7%BC%96%E7%A8%8B)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FMEA management model</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#fmea%E7%AE%A1%E7%90%86%E6%A8%A1%E5%BC%8F)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">General Business Terms</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E9%80%9A%E7%94%A8%E4%B8%9A%E5%8A%A1%E6%9C%AF%E8%AF%AD)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Technical trends</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%8A%80%E6%9C%AF%E8%B6%8B%E5%8A%BF)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Policies and regulations</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%94%BF%E7%AD%96%E6%B3%95%E8%A7%84)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">legal</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%B3%95%E5%BE%8B)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Strictly abide by Article 253 of the Criminal Law</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%B8%A5%E6%A0%BC%E9%81%B5%E5%AE%88%E5%88%91%E6%B3%95253%E6%B3%95%E6%9D%A1)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Architect quality</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%9E%B6%E6%9E%84%E5%B8%88%E7%B4%A0%E8%B4%A8)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Team management</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%9B%A2%E9%98%9F%E7%AE%A1%E7%90%86)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Recruitment</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%8B%9B%E8%81%98)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Information</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%B5%84%E8%AE%AF)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Industry information</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%A1%8C%E4%B8%9A%E8%B5%84%E8%AE%AF)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Public number list</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%85%AC%E4%BC%97%E5%8F%B7%E5%88%97%E8%A1%A8)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Blog</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%8D%9A%E5%AE%A2)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Team blog</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%9B%A2%E9%98%9F%E5%8D%9A%E5%AE%A2)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">personal blog</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Integrated portal, community</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%BB%BC%E5%90%88%E9%97%A8%E6%88%B7%E7%A4%BE%E5%8C%BA)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Q&A, discussion community</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E9%97%AE%E7%AD%94%E8%AE%A8%E8%AE%BA%E7%B1%BB%E7%A4%BE%E5%8C%BA)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Industry data analysis</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E8%A1%8C%E4%B8%9A%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Special website</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%B8%93%E9%A1%B9%E7%BD%91%E7%AB%99)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">other</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%85%B6%E4%BB%96%E7%B1%BB)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Recommended reference book</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%8E%A8%E8%8D%90%E5%8F%82%E8%80%83%E4%B9%A6)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Online eBooks</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%9C%A8%E7%BA%BF%E7%94%B5%E5%AD%90%E4%B9%A6)
        *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Paper book</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%BA%B8%E8%B4%A8%E4%B9%A6)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Development aspects</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%BC%80%E5%8F%91%E6%96%B9%E9%9D%A2)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Architecture aspects</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%9E%B6%E6%9E%84%E6%96%B9%E9%9D%A2)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Technical management</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%8A%80%E6%9C%AF%E7%AE%A1%E7%90%86%E6%96%B9%E9%9D%A2)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Basic theory</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%9F%BA%E7%A1%80%E7%90%86%E8%AE%BA-1)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tools</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%B7%A5%E5%85%B7%E6%96%B9%E9%9D%A2)
            *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Big data</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%A4%A7%E6%95%B0%E6%8D%AE%E6%96%B9%E9%9D%A2)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Technical resources</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%8A%80%E6%9C%AF%E8%B5%84%E6%BA%90)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open source resources</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%BC%80%E6%BA%90%E8%B5%84%E6%BA%90)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Manuals, Documents, Tutorials</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%89%8B%E5%86%8C%E6%96%87%E6%A1%A3%E6%95%99%E7%A8%8B)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Online class</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%9C%A8%E7%BA%BF%E8%AF%BE%E5%A0%82)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">conference</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%BC%9A%E8%AE%AE%E6%B4%BB%E5%8A%A8)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Common APP</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%B8%B8%E7%94%A8app)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">find a job</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%89%BE%E5%B7%A5%E4%BD%9C)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">tool</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E5%B7%A5%E5%85%B7)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Code hosting</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E4%BB%A3%E7%A0%81%E6%89%98%E7%AE%A1)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">File service</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E6%96%87%E4%BB%B6%E6%9C%8D%E5%8A%A1)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Comprehensive cloud service provider</font></font>](https://github.com/ironmanMA/architect-awesome/blob/master/README.md#%E7%BB%BC%E5%90%88%E4%BA%91%E6%9C%8D%E5%8A%A1%E5%95%86)

**<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(Toc generated by</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">simple-php-github-toc</font></font>](https://github.com/xingshaocheng/simple-php-github-toc)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">)</font></font>**

# [](#数据结构)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">data structure</font></font>

## [](#队列)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">queue</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"java queue - detailed analysis of queue"</font></font>](https://www.cnblogs.com/lemon-flm/p/7877898.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Non-blocking queue: ConcurrentLinkedQueue (unbounded thread safe), using CAS mechanism (compareAndSwapObject atomic operation).</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Blocking queues: ArrayBlockingQueue (bounded), LinkedBlockingQueue (unbounded), DelayQueue, PriorityBlockingQueue, using lock mechanism; use ReentrantLock lock.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"LinkedList, ConcurrentLinkedQueue, LinkedBlockingQueue Comparative Analysis"</font></font>](https://www.cnblogs.com/mantu/p/5802393.html)

## [](#集合)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">set</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Details of Java Set Collection"</font></font>](https://blog.csdn.net/qq_33642117/article/details/52040345)

## [](#链表数组)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Lists, arrays</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Java Collection Detailed - What is a List"</font></font>](https://blog.csdn.net/wz249863091/article/details/52853360)

## [](#字典关联数组)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Dictionary, associative array</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Java map details - usage, traversal, sorting, common APIs, etc."</font></font>](https://baike.xsoftlab.net/view/250.html)

## [](#栈)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Stack</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Stack design and implementation of java data structure and algorithm"</font></font>](https://blog.csdn.net/javazejian/article/details/53362993)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java Stack Class</font></font>](http://www.runoob.com/java/java-stack-class.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Detailed Implementation Analysis of Java Stack"</font></font>](https://blog.csdn.net/f2006116/article/details/51375225)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Stack is thread-safe.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Internal use array to save data, double when not enough.</font></font>

## [](#树)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">tree</font></font>

### [](#二叉树)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Binary tree</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Each node has a maximum of two leaf nodes.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Binary Tree</font></font>](https://blog.csdn.net/cai2016/article/details/52589952)

### [](#完全二叉树)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Complete Binary Tree</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Complete Binary Tree</font></font>](https://baike.baidu.com/item/%E5%AE%8C%E5%85%A8%E4%BA%8C%E5%8F%89%E6%A0%91/7773232?fr=aladdin)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The leaf nodes can only appear at the bottom and sub-lower levels, and the nodes at the bottom level are all concentrating on the binary tree at the leftmost position of the layer.</font></font>

### [](#平衡二叉树)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Balanced binary tree</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The absolute value of the height difference between the left and right two subtrees does not exceed one, and both the left and right subtrees are balanced binary trees.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"On Data Structure - Balanced Binary Tree"</font></font>](http://www.cnblogs.com/polly333/p/4798944.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"On the algorithm and data structure: eight balanced tree search 2-3 tree"</font></font>](http://www.cnblogs.com/yangecnu/p/Introduce-2-3-Search-Tree.html)

### [](#二叉查找树bst)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Binary Search Tree (BST)</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Binary Search Trees, also called ordered binary trees, are sorted binary trees.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"On the algorithm and data structure: seven binary search tree"</font></font>](http://www.cnblogs.com/yangecnu/p/Introduce-Binary-Search-Tree.html)

### [](#红黑树)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Red black tree</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Easiest to understand red and black trees"</font></font>](https://blog.csdn.net/sun_tttt/article/details/65445754)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">After the addition phase, left-handed or right-handed to reach equilibrium again.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"On Algorithms and Data Structures: Nine Balanced Search Trees for Red and Black Trees"</font></font>](http://www.cnblogs.com/yangecnu/p/Introduce-Red-Black-Tree.html)

### [](#b-bb树)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">B-, B+, B* trees</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MySQL is based on the B+ tree clustered index organization table</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"B-tree, B+ tree, B* tree"</font></font>](https://blog.csdn.net/aqzwss/article/details/53074186)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Comparison of the advantages and disadvantages of B-trees, B+ trees and B* trees"</font></font>](https://blog.csdn.net/bigtree_3721/article/details/73632405)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The tree structure of the leaf nodes of the B+ tree is more convenient than the B-tree for scanning and range retrieval.</font></font>

### [](#lsm-树)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LSM tree</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Compared with B+ trees, LSM (Log-Structured Merge-Trees) sacrifices partial read performance in exchange for write performance (through batch writes) and achieves read and write.</font> <font style="vertical-align: inherit;">Hbase, LevelDB, Tair (Long DB), and nessDB use the structure of the LSM tree.</font> <font style="vertical-align: inherit;">LSM can quickly establish an index.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LSM Tree vs B+ Tree</font></font>](https://blog.csdn.net/dbanote/article/details/8897599)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The B+ tree read performance is good, but due to the need for an orderly structure, the disk seeks frequently when the keys are scattered, resulting in write performance.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LSM divides a large tree into N small trees, first writes to memory (without seeking problems, high performance), and constructs an ordered small tree (ordered tree) in memory. The bigger the memory tree is flushed to disk.</font> <font style="vertical-align: inherit;">When reading, because it does not know which tree the data is on, it is necessary to traverse (bi-search) all the small trees, but the data is ordered inside each small tree.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LSM Tree (Log-Structured Merge Tree Storage Engine)</font></font>](https://blog.csdn.net/u014774781/article/details/52105708)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">In extreme terms, the write performance of HBase based on the LSM tree is an order of magnitude higher than that of MySQL, and the read performance is an order of magnitude lower.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Optimization method: Bloom filter replaces binary search; compact decimal tree, improves query performance.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">In Hbase, when the memory reaches a certain threshold, the entire flush flushes to disk and forms a file (B+ number). HDFS does not support the update operation. Therefore, Hbase does an overall flush instead of a merge update.</font> <font style="vertical-align: inherit;">Flush to the small tree on the disk, periodically merged into a big tree.</font></font>

## [](#bitset)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BitSet</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">It is often used for checking the weight of large-scale data.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Java Bitset Class"</font></font>](http://www.runoob.com/java/java-bitset-class.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java BitSet (bit set)</font></font>](https://blog.csdn.net/caiandyong/article/details/51581160)

# [](#常用算法)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Common algorithms</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Common sorting algorithms and their corresponding time complexity and space complexity"</font></font>](https://blog.csdn.net/gane_cheng/article/details/52652705)

## [](#排序查找算法)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sorting, finding algorithm</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Common sorting algorithms and their corresponding time complexity and space complexity"</font></font>](https://blog.csdn.net/gane_cheng/article/details/52652705)

### [](#选择排序)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Select sort</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Selection Sort of Classic Algorithms in Java"</font></font>](https://www.cnblogs.com/shen-hua/p/5424059.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Each tick selects the smallest element from the records to be sorted, and the order is placed at the end of the sorted sequence until all records are sorted.</font></font>

### [](#冒泡排序)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bubble Sort</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Two kinds of writing bubble sorting"</font></font>](https://blog.csdn.net/shuaizai88/article/details/73250615)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Exchange adjacent elements before and after, the largest row to the end.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Time complexity O(n2)</font></font>

### [](#插入排序)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Insert sort</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Sorting algorithm summary insertion sort"</font></font>](https://www.cnblogs.com/hapjin/p/5517667.html)

### [](#快速排序)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Quick sort</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sitting on the toilet looking algorithm: quick sort</font></font>](http://developer.51cto.com/art/201403/430986.htm)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">One side is larger or smaller than the other.</font></font>

### [](#归并排序)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Merge sort</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Image Sorting Algorithm (4) Merge and Sorting"</font></font>](http://www.cnblogs.com/chengxiao/p/6194356.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Divide and conquer, sort into small parts and merge (recreate a new space for copying).</font></font>

### [](#希尔排序)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hill Sort</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

### [](#堆排序)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Heap sort</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Graphical sorting algorithm (three) of the heap sort"</font></font>](https://www.cnblogs.com/chengxiao/p/6129630.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The sorting process is the process of building a maximum heap. The maximum heap: The value of each node is greater than or equal to the value of its child nodes, and the top element is the maximum value.</font></font>

### [](#计数排序)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Counting sort</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Counting and Bucket Sorting</font></font>](https://www.cnblogs.com/suvllian/p/5495780.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Compared to the bucket sorting process, the difference lies in the number of buckets.</font></font>

### [](#桶排序)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bucket sort</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"[Aha!</font> <font style="vertical-align: inherit;">Algorithms] The Fastest and Simplest Sorting - Bucket Sorting</font></font>](http://blog.51cto.com/ahalei/1362789)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Sort Algorithm (3): Counting and Bucket Sorting"</font></font>](https://blog.csdn.net/sunjinshengli/article/details/70738527)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bucket sorting divides the [0,1) interval into n sub-intervals of the same size, which are called buckets.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Each bucket is sorted individually and then it traverses each bucket.</font></font>

### [](#基数排序)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cardinal sort</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sort by rank, ten, hundred, ...</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sort Algorithm Series: Cardinal Sorting</font></font>](https://blog.csdn.net/lemon_tree12138/article/details/51695211)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cardinal Sort</font></font>](https://www.cnblogs.com/skywang12345/p/3603669.html)

### [](#二分查找)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Binary search</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Two-point search (java implementation)"</font></font>](https://www.cnblogs.com/coderising/p/5708632.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The sequence to be searched is ordered.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Time complexity O(logN).</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"java realize binary search - two ways"</font></font>](https://blog.csdn.net/maoyuanming0806/article/details/78176957)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">While + recursively.</font></font>

### [](#java-中的排序工具)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sorting tools in Java</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Analysis of Arrays.sort and Collections.sort Implementation Principles</font></font>](https://blog.csdn.net/u011410529/article/details/56668545?locationnum=6&fps=1)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The Collections.sort algorithm calls the merge sort.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Arrays.sort() uses two sorting algorithms -- basic sort data using quick sorting, and object arrays using merge sorting.</font></font>

## [](#布隆过滤器)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bloom filter</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Commonly used for big data, such as email, url, etc.</font> <font style="vertical-align: inherit;">Core principle: Generate a fingerprint (a byte or bytes, but certainly a lot less than the original data) by calculating each piece of data, each of which is obtained by random calculation, mapping the fingerprint to a large The bitwise storage space.</font> <font style="vertical-align: inherit;">Note: There will be a certain error rate.</font> <font style="vertical-align: inherit;">Advantages: High space and time efficiency.</font> <font style="vertical-align: inherit;">Disadvantages: As the number of deposited elements increases, the miscalculation rate increases.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bloom Filter - Spatially Efficient Data Structure</font></font>](https://segmentfault.com/a/1190000002729689)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Large Data Deduplication: Bitmap and Bloom Filters"</font></font>](https://blog.csdn.net/zdxiq000/article/details/57626464)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The Implementation of Bloom Filter Based on Redis"</font></font>](https://blog.csdn.net/qq_30242609/article/details/71024458)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Redis-based Bitmap data structure.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Web crawler: Use of Bloom filter for URL deduplication policy"</font></font>](https://blog.csdn.net/lemon_tree12138/article/details/47973715)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Use the BitSet class and weighted hashing algorithm in Java.</font></font>

## [](#字符串比较)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">String comparison</font></font>

### [](#kmp-算法)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KMP algorithm</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KMP: The core principle of the Knuth-Morris-Pratt algorithm (abbreviated as KMP) is to use a "partial match table" to skip over elements that have already been matched.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">String Matching KMP Algorithm</font></font>](http://www.ruanyifeng.com/blog/2013/05/Knuth%E2%80%93Morris%E2%80%93Pratt_algorithm.html)

## [](#深度优先广度优先)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Depth first, breadth first</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Breadth First Search BFS and Depth First Search DFS</font></font>](https://www.cnblogs.com/0kk470/p/7555033.html)

## [](#贪心算法)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">how are you</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Algorithm: Fundamentals of Greedy Algorithm"</font></font>](https://www.cnblogs.com/MrSaver/p/8641971.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Common Algorithms and Problem Scenarios - Greedy Algorithm"</font></font>](https://blog.csdn.net/a345017062/article/details/52443781)

## [](#回溯算法)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Backtracking algorithm</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Five commonly used algorithms: Backtracking method"</font></font>](https://blog.csdn.net/qfikh/article/details/51960331)

## [](#剪枝算法)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pruning algorithm</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"α-β Pruning Algorithm"</font></font>](https://blog.csdn.net/luningcsdn/article/details/50930276)

## [](#动态规划)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Dynamic planning</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Detailed Explanation of Dynamic Planning - Zou Bo Talks about Dynamic Planning"</font></font>](https://www.cnblogs.com/little-YTMM/p/5372680.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Personal Understanding of Dynamic Programming Algorithms"</font></font>](https://blog.csdn.net/yao_zi_jie/article/details/54580283)

## [](#朴素贝叶斯)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Naive Bayes</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Take You Through the Naive Bayes Classification Algorithm"</font></font>](https://blog.csdn.net/amds123/article/details/70173402)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">P(B|A)=P(A|B)P(B)/P(A)</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bayesian Inference and Internet Applications 1</font></font>](http://www.ruanyifeng.com/blog/2011/08/bayesian_inference_part_one.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bayesian Inference and Internet Applications 2</font></font>](http://www.ruanyifeng.com/blog/2011/08/bayesian_inference_part_two.html)

## [](#推荐算法)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Recommended algorithm</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Recommendation algorithm review"</font></font>](http://www.infoq.com/cn/articles/recommendation-algorithm-overview-part01)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Introduction to TOP 10 Open Source Recommendation System"</font></font>](https://www.oschina.net/news/51297/top-10-open-source-recommendation-systems)

## [](#最小生成树算法)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Minimum spanning tree algorithm</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Introduction to Algorithms - Minimum Spanning Tree (Kruskal and Prim Algorithms)"</font></font>](https://blog.csdn.net/luoshixian099/article/details/51908175)

## [](#最短路径算法)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Shortest path algorithm</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Dijkstra Algorithm Detailed"</font></font>](https://blog.csdn.net/qq_35644234/article/details/60870719)

# [](#并发)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Concurrent</font></font>

1.  **<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Basic knowledge</font></font>**

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.1</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">advantages and disadvantages of concurrent programming</font></font>](https://juejin.im/post/5ae6c3ef6fb9a07ab508ac85)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) Why use concurrency?</font> <font style="vertical-align: inherit;">(Advantages); (2) Disadvantages of concurrent programming; (3) Confusing concept</font></font>

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.2</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Thread Status and Basic Operations</font></font>](https://juejin.im/post/5ae6cf7a518825670960fcc2)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) how to create new threads; (2) thread state transitions; (3) basic thread operations; (4) daemon threads;</font></font>

2.  **<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Concurrency Theory (JMM)</font></font>**

    [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java memory model and happens-before rules</font></font>](https://juejin.im/post/5ae6d309518825673123fd0e)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) JMM memory structure; (2) reordering; (3) happens-before rules</font></font>

3.  **<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Concurrent Keyword</font></font>**

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3.1</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Let you thoroughly understand Synchronized</font></font>](https://juejin.im/post/5ae6dc04f265da0ba351d3ff)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) how to use synchronized; (2) monitor mechanism; (3) synchronized happens-before relationship; (4) synchronized memory semantics; (5) lock optimization; (6) lock escalation strategy</font></font>

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3.2</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Let you thoroughly understand volatile</font></font>](https://juejin.im/post/5ae9b41b518825670b33e6c4)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) implementation principle; (2) derivation of happens-before relations; (3) memory semantics; (4) realization of memory semantics</font></font>

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3.3</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Do you think you really understand final?</font></font>](https://juejin.im/post/5ae9b82c6fb9a07ac3634941)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) how to use; (2) final reordering rules; (3) final implementation principles; (4) final references cannot "overflow" (this escape) from constructors</font></font>

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3.4</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Summary of the three major properties: atomicity, orderliness, visibility</font></font>](https://juejin.im/post/5aeb022cf265da0b722af7b8)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) atomicity: synchronized; (2) visibility: synchronized, volatile; (3) orderliness: synchronized, volatile</font></font>

4.  **<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Lock system</font></font>**

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.1</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Meet Lock and AbstractQueuedSynchronizer (AQS)</font></font>](https://juejin.im/post/5aeb055b6fb9a07abf725c8c)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) Lock and synchronized comparisons; (2) AQS design intent; (3) How to implement custom synchronization components using AQS; (4) Rewritable methods; (5) Template methods provided by AQS;</font></font>

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.2 In-</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">depth understanding of AbstractQueuedSynchronizer (AQS)</font></font>](https://juejin.im/post/5aeb07ab6fb9a07ac36350c8)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) AQS synchronization queue data structure; (2) exclusive lock; (3) shared lock;</font></font>

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.3</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Understanding ReentrantLock Again</font></font>](https://juejin.im/post/5aeb0a8b518825673a2066f0)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) implementation principle of reentrant locks; (2) implementation principle of fair locks; (3) implementation principle of non-fair locks; (4) comparison of fair locks and non-fair locks</font></font>

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.4 In-</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">depth understanding of the read-write lock ReentrantReadWriteLock</font></font>](https://juejin.im/post/5aeb0e016fb9a07ab7740d90)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) How to represent read/write status; (2) WriteLock acquisition and release; (3) ReadLock acquisition and release; (4) lock downgrading strategy; (5) Generation of Condition wait queues; (6) Application scenarios</font></font>

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.5</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Detailed conditions await and signal wait / notification mechanism</font></font>](https://juejin.im/post/5aeea5e951882506a36c67f0)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) Features that are comparable to the wait/notify mechanism of Object; (2) Methods corresponding to wait/notify of Object; (3) Underlying data structures; (4) Await implementation principles; (5) Signal/signalAll implementation principle; (6) combination of await and signal/signalAll;</font></font>

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.6</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LockSupport Tool</font></font>](https://juejin.im/post/5aeed27f51882567336aa0fa)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) main functions; (2) characteristics compared to synchronized blocking wake-up;</font></font>

5.  **<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Concurrent container</font></font>**

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5.1</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">concurrent containers ConcurrentHashMap (JDK 1.8 version)</font></font>](https://juejin.im/post/5aeeaba8f265da0b9d781d16)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) key attributes; (2) important internal classes; (3) CAS operations involved; (4) construction methods; (5) put execution flow; (6) get execution flow; (7) expansion mechanism (8) Execution flow of method for counting size; (9) Comparison of ConcurrentHashMap version 1.8 with previous version</font></font>

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5.2</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CopyOnWriteArrayList of Concurrent Containers</font></font>](https://juejin.im/post/5aeeb55f5188256715478c21)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) realization principle; (2) difference between COW and ReentrantReadWriteLock; (3) application scenario; (4) why there is weak consistency; (5) shortcomings of COW;</font></font>

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5.3</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ConcurrentLinkedQueue for Concurrent Containers</font></font>](https://juejin.im/post/5aeeae756fb9a07ab11112af)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) implementation principle; (2) data structure; (3) core method; (4) design intent of delayed update of HOPS</font></font>

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5.4</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">concurrent container ThreadLocal</font></font>](https://juejin.im/post/5aeeb22e6fb9a07aa213404a)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) implementation principle; (2) set method principle; (3) get method principle; (4) remove method principle; (5) ThreadLocalMap</font></font>

    [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">An article, from the source code in-depth detailed ThreadLocal memory leak problem</font></font>](https://www.jianshu.com/p/dde92ec37bd1)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) ThreadLocal memory leak principle; (2) ThreadLocal best practices; (3) application scenarios</font></font>

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5.5</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Concurrent Container BlockingQueue</font></font>](https://juejin.im/post/5aeebd02518825672f19c546)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) Basic operation of BlockingQueue; (2) Commonly used BlockingQueue;</font></font>

    [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Concurrent container ArrayBlockingQueue and LinkedBlockingQueue implementation principle explained</font></font>](https://juejin.im/post/5aeebdb26fb9a07aa83ea17e)

6.  **<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Thread pool (Executor system)</font></font>**

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">6.1</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Thread Pool Implementation Principle</font></font>](https://juejin.im/post/5aeec0106fb9a07ab379574f)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) Why use a thread pool?</font> <font style="vertical-align: inherit;">(2) execution flow; (3) the meaning of each parameter of the constructor; (4) how to close the thread pool; (5) how to configure the thread pool;</font></font>

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">6.2</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Thread Pool ScheduledThreadPoolExecutor</font></font>](https://juejin.im/post/5aeec106518825670a10328a)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) class structure; (2) common methods; (3) ScheduledFutureTask; (3) DelayedWorkQueue;</font></font>

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">6.3</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FutureTask Basic Operation Summary</font></font>](https://juejin.im/post/5aeec249f265da0b886d5101)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) Several states of FutureTask; (2) get method; (3) cancel method; (4) application scenario; (5) implementation of Runnable interface</font></font>

7.  **<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Atomic operations</font></font>**

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">7.1</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Atomic Operation Classes in Atomic Packages in Java</font></font>](https://juejin.im/post/5aeec351518825670a103292)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge points: (1) implementation principle; (2) atomic update basic types; (3) atomic update array types; (4) atomic update reference types; (5) atomic update field types</font></font>

8.  **<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Concurrency tools</font></font>**

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8.1</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Big vernacular Java Concurrency Tool - CountDownLatch, CyclicBarrier</font></font>](https://juejin.im/post/5aeec3ebf265da0ba76fa327)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge Points: (1) CountDownLatch, (2) CyclicBarrier, and (3) Comparison between CountDownLatch and CyclicBarrier</font></font>

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8.2</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Big vernacular Java Concurrency Tools - Semaphore, Exchanger</font></font>](https://juejin.im/post/5aeec49b518825673614d183)

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge Points: (1) Resource Access Control Semaphore; (2) Data Exchange Exchanger</font></font>

9.  **<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Concurrent practice</font></font>**

    <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">9.1</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">An article that lets you thoroughly understand the producer-consumer problem</font></font>](https://juejin.im/post/5aeec675f265da0b7c072c56)

> <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JAVA concurrent knowledge map</font></font>

**<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Move to a new window, zoom in to see better results or view originals</font></font>**

[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Knowledge map artwork link, if useful, can be cloned for use</font></font>](https://www.processon.com/view/5ab5a979e4b0a248b0e026b3?fromnew=1)

[![JAVA concurrency knowledge map.png](https://github.com/CL0610/Java-concurrency/raw/master/Java%E5%B9%B6%E5%8F%91%E7%9F%A5%E8%AF%86%E5%9B%BE%E8%B0%B1.png)](https://github.com/CL0610/Java-concurrency/blob/master/Java%E5%B9%B6%E5%8F%91%E7%9F%A5%E8%AF%86%E5%9B%BE%E8%B0%B1.png)

## [](#多线程)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Multithreading</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Summary of 40 Java Multithreading Problems"</font></font>](http://www.importnew.com/18459.html)

## [](#线程安全)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Thread safety</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Concurrent Java Programming - Introduction to Thread Safety and Solution Mechanisms"</font></font>](https://www.cnblogs.com/zhanht/p/5450325.html)

## [](#一致性事务)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Consistency, transaction</font></font>

### [](#事务-acid-特性)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Transaction ACID features</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Database ACID Features"</font></font>](https://blog.csdn.net/u012440687/article/details/52116108)

### [](#事务的隔离级别)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Transaction isolation level</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Uncommitted read: A transaction can read another uncommitted data and is prone to dirty reads.</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Read submission: A transaction can read data only after another transaction has been submitted, but a non-repeatable read situation occurs (the read data is inconsistent), and an UPDATE operation occurs during the read process.</font> <font style="vertical-align: inherit;">(The default level for most databases is RC, such as SQL Server, Oracle), which cannot be changed when reading.</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Repeatable reading: The same transaction ensures that the same data is obtained for each read, but does not guarantee that the original data is updated (phantom read) by other transactions. Mysql InnoDB is this level.</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Serialization: serial processing of all things (sacrificing efficiency)</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Understanding the Four Isolation Levels of a Business</font></font>](https://blog.csdn.net/qq_33290787/article/details/51924963)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Four characteristics of database transactions and transaction isolation levels</font></font>](https://www.cnblogs.com/z-sm/p/7245981.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"InnoDB's phantom reading problem"</font></font>](http://blog.sina.com.cn/s/blog_499740cb0100ugs7.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The example of phantom reading is very clear.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Solve with SELECT ... FOR UPDATE.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"An article with you to read MySQL and InnoDB"</font></font>](http://database.51cto.com/art/201804/570101.htm)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Graphical dirty reading, non-repeatable reading, phantom reading problems.</font></font>

### [](#mvcc)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MVCC</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"[mysql] some understanding of MVCC in innodb"</font></font>](https://www.cnblogs.com/chenpingzhao/p/5065316.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The MVCC in innodb is used at the Repeatable-Read isolation level.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MVCC produces phantom issues (updated exceptions.)</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Easy understanding MYSQL MVCC implementation mechanism"</font></font>](https://blog.csdn.net/whoamiyang/article/details/51901888)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MVCC control is achieved by hiding the version column, a record creation time, a record deletion time, and the time</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Only operate on lines that are smaller (or equal) than the current version.</font></font>

## [](#锁)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">lock</font></font>

### [](#java中的锁和同步类)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Locks and synchronization classes in Java</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Lock Classification in Java"</font></font>](https://www.cnblogs.com/qifengshi/p/6831055.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mainly includes synchronized, ReentrantLock, and ReadWriteLock.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Java Concurrency AQS Detailed"</font></font>](https://www.cnblogs.com/waterystone/p/4920797.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Signal Semaphore in Java"</font></font>](http://cuisuqiang.iteye.com/blog/2020146)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Quantity control</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apply with acquire, apply for not blocked; release with release.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Mutex vs Semaphore in Java Development"</font></font>](https://www.cnblogs.com/davidwang456/p/6094947.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Simply put, Mutex is exclusive. Only one resource can be obtained. Semaphore is also exclusive, but it can define multiple objects that can be accessed.</font></font>

### [](#公平锁--非公平锁)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Fair lock & non-fair lock</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The role of the fair lock is to execute in strict accordance with the order in which the threads are started, and no other thread is allowed to queue execution; non-fair locks are allowed to be queued.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Fair and Unfair Locks</font></font>](https://blog.csdn.net/EthanWhite/article/details/55508357)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReentrantLock and synchronized are both non-fair locks by default.</font> <font style="vertical-align: inherit;">ReentrantLock can be set to fair lock.</font></font>

### [](#悲观锁)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pessimistic lock</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pessimistic locking, if used improperly (with too many locks), can cause large areas of service to wait.</font> <font style="vertical-align: inherit;">It is recommended to use optimistic locking + retries first.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"[MySQL] Pessimistic Lock & Optimistic Lock"</font></font>](https://www.cnblogs.com/zhiqian-ali/p/6200874.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Optimistic locking method: version number + retry method</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pessimistic locking: row locking via select ... for update (unreadable, non-writable, and share lock read-unreadable).</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Mysql query statement using select.. for update database deadlock analysis"</font></font>](https://www.cnblogs.com/Lawson/p/5008741.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Although the innodb storage engine oracle's intrinsic lock is a lock line, it is internally locked.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Different index conditions that lock the same data can cause deadlocks.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Mysql concurrent classic deadlock causes and solutions"</font></font>](https://www.cnblogs.com/zejin2008/p/5262751.html)

### [](#乐观锁--cas)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Optimistic Lock & CAS</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"An Optimistic Lock Implementation - CAS"</font></font>](http://www.importnew.com/20472.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">It is similar to the MySQL optimistic lock method, but it is compared with the original value.</font></font>

### [](#aba-问题)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ABA issues</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Due to high concurrency, under CAS, this A may not be A after updating.</font> <font style="vertical-align: inherit;">It can be solved by the version number, similar to the optimistic lock mentioned in Mysql above.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java CAS and ABA Issues</font></font>](https://www.cnblogs.com/549294286/p/3766717.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"ABA Problems and Avoidance in Java"</font></font>](https://blog.csdn.net/li954644351/article/details/50511879)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AtomicStampedReference and AtomicStampedReference.</font></font>

### [](#copyonwrite容器)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CopyOnWrite container</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Concurrent reads can be made to the CopyOnWrite container without the need for locking.</font> <font style="vertical-align: inherit;">The CopyOnWrite concurrent container is used to read multiple writes and fewer concurrent scenes.</font> <font style="vertical-align: inherit;">For example, whitelists, blacklists, and visits and update scenarios for product categories are not suitable for scenarios that require strong data consistency.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Copy-On-Write Map Implementation in JAVA"</font></font>](https://www.cnblogs.com/hapjin/p/4840107.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reading and writing are separated, reading occurs on the original data, and writing occurs on the copy.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Without locking, consistency is finally achieved through consistency.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Chat Concurrency - Copy-On-Write Container in Java</font></font>](https://blog.csdn.net/a494303877/article/details/53404623)

### [](#ringbuffer)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RingBuffer</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Thread-safe, lock-free RingBuffer implementation [a read thread, a write thread]"</font></font>](http://www.cnblogs.com/l00l/p/4115001.html)

### [](#可重入锁--不可重入锁)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reentrant Locks & Non-Reentrant Locks</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reentrant and Non-Reentrant Locks</font></font>](https://www.cnblogs.com/dj3839/p/6580765.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Examples of reentrant locks and non-reentrant locks are illustrated by simple code.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reentrant locks mean that the same thread can regain previously acquired locks.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reentrant locks allow users to avoid deadlocks.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reentrant locks in Java: synchronized and java.util.concurrent.locks.ReentrantLock</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"ReenTrantLock reentrant lock (and the difference between synchronized) summary"</font></font>](https://www.cnblogs.com/baizhanshi/p/7211802.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Synchronized easy to use, the compiler to lock, is a non-fair lock.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReenTrantLock is flexible and lock fairness can be customized.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">In the same locked scenario, it is recommended to use synchronized.</font></font>

### [](#互斥锁--共享锁)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mutexes & shared locks</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mutexes: Only one thread can acquire a lock at the same time.</font> <font style="vertical-align: inherit;">For example, ReentrantLock is a mutex, and write locks in ReadWriteLock are mutexes.</font> <font style="vertical-align: inherit;">Shared locks: There can be multiple or simultaneous locks.</font> <font style="vertical-align: inherit;">For example, Semaphore, CountDownLatch are shared locks, and read locks in ReadWriteLock are shared locks.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"ReadWriteLock Scene Application"</font></font>](https://www.cnblogs.com/liang1101/p/6475555.html)

### [](#死锁)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Deadlock</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Reasonable explanation of the four necessary conditions for "deadlock"</font></font>](https://blog.csdn.net/yunfenglw/article/details/45950305)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mutually exclusive, held, inalienable, inalienable.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">How can Java view the deadlock?</font></font>](https://blog.csdn.net/u014039577/article/details/52351626)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JConsole recognizes deadlocks.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java multi-threaded series: deadlock and detection</font></font>](https://blog.csdn.net/bohu83/article/details/51135061)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jstack can display deadlocks.</font></font>

# [](#操作系统)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">operating system</font></font>

## [](#计算机原理)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Principle of computer</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Basic knowledge of operating system - principle, type and structure of operating system"</font></font>](https://segmentfault.com/a/1190000003692840)

## [](#cpu)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CPU</font></font>

### [](#多级缓存)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Multi-level cache</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">A typical CPU has three levels of cache. The closer it is to the core, the faster and the smaller the space.</font> <font style="vertical-align: inherit;">L1 is generally 32k, L2 is generally 256k, and L3 is generally 12M.</font> <font style="vertical-align: inherit;">The memory speed requires 200 CPU cycles and the CPU cache requires 1 CPU cycle.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Understanding CPU Cache and Pseudo Sharing from a Java Perspective"</font></font>](https://blog.csdn.net/zero__007/article/details/54089730)

## [](#进程)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">process</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

## [](#线程)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Threads</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Thread life cycle and state transition details"</font></font>](https://blog.csdn.net/asdf_1024/article/details/78978437)

## [](#协程)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Correspondence</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Terminating Python Coroutines--Implementation from Yield to actor Model"</font></font>](https://www.thinksaas.cn/group/topic/839375/)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Thread scheduling is the responsibility of the operating system. Coroutine scheduling is the responsibility of the program.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Compared with threads, coroutines reduce unnecessary operating system switching.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">In fact, when switching to an IO operation is more meaningful, (because the IO operation does not occupy the CPU), if no IO operation is encountered, switch according to the time slice.</font></font>

## [](#linux)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux Command Encyclopedia</font></font>](http://www.runoob.com/linux/linux-command-manual.html)

# [](#设计模式)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Design Patterns</font></font>

## [](#设计模式的六大原则)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Six principles of design patterns</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The Six Principles of Design Patterns</font></font>](https://blog.csdn.net/q291611265/article/details/48465113)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The principle of opening and closing: open to the extension, close to the modification, use more abstract classes and interfaces.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Lie substitution principle: the base class can be replaced by subclasses, use abstract class inheritance, do not use concrete class inheritance.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Relying on the principle of reversal: to rely on abstraction, not relying on the specific, programming for the interface, not for programming.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Interface isolation principle: Using multiple isolated interfaces is better than using a single interface to establish a minimal interface.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Dimit's Law: A software entity should interact with other entities as little as possible and establish links through intermediate classes.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Synthetic reuse principles: Use synthetic/aggregate as much as possible instead of using inheritance.</font></font>

## [](#23种常见设计模式)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">23 common design patterns</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Design Patterns"</font></font>](http://www.runoob.com/design-pattern/design-pattern-tutorial.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"23 kinds of design patterns full analysis"</font></font>](https://www.cnblogs.com/susanws/p/5510229.html)

## [](#应用场景)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Application scenario</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Detailed Design Patterns in the JDK"</font></font>](http://blog.jobbole.com/62314/)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Structural mode:</font></font>

        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Adapter: Used to convert an interface to another interface, such as java.util.Arrays#asList().</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bridge mode: This mode decouples the implementation of abstract and abstract operations, so that the abstraction and implementation can be independently changed, such as JDBC;</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Combined mode: Makes the client seem to have the same combination of individual objects and objects.</font> <font style="vertical-align: inherit;">In other words, a certain type of method also accepts its own type as parameters, such as Map.putAll, List.addAll, Set.addAll.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Decorator pattern: Dynamically adds an extra function to an object, which is an alternative to subclasses, such as java.util.Collections#checkedList|Map|Set|SortedSet|SortedMap.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Fragmentation mode: use caching to speed up the access time of a large number of small objects, such as valueOf(int).</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Proxy mode: The proxy mode is to replace a complex or time-consuming object with a simple object, such as java.lang.reflect.Proxy</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Create mode:</font></font>

        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Abstract factory pattern: The abstract factory pattern provides a protocol to generate a series of related or independent objects without specifying the concrete object type, such as java.util.Calendar#getInstance().</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Builder: A new class is defined to build an instance of another class to simplify the creation of complex objects such as: java.lang.StringBuilder#append().</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Factory method: that</font> </font>**<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">a return</font></font>**<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">* back to the specific object methods, rather than several, such as java.lang.Object # toString (), java.lang.Class # newInstance ().</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Prototype mode: Makes an instance of a class generate its own copy, such as: java.lang.Object#clone().</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Singleton mode: There is only one instance globally, such as java.lang.Runtime#getRuntime().</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Behavior pattern:</font></font>

        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Chain of Responsibility: By delegating requests from an object to the next object in the chain until the request is processed, decoupling between objects is achieved.</font> <font style="vertical-align: inherit;">Such as javax.servlet.Filter#doFilter().</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Command mode: encapsulates operations into objects for storage, delivery, and return, such as: java.lang.Runnable.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Interpreter mode: defines the syntax of a language, and then parses the corresponding syntax statement, such as java.text.Format, java.text.Normalizer.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Iterator mode: Provides a consistent method for sequentially accessing objects in a collection, such as java.util.Iterator.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mediator pattern: java.lang.reflect.Method#invoke() by using an intermediate object for message distribution and reducing the direct dependency between classes.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Empty object patterns: such as java.util.Collections#emptyList().</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Observer pattern: It allows an object to send messages to interested objects flexibly, such as java.util.EventListener.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Template method pattern: Allows subclasses to override part of the method instead of the entire rewrite, such as java.util.Collections#sort().</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Spring-related design patterns summary"</font></font>](https://www.cnblogs.com/hwaggLee/p/4510687.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Design Patterns Used by Mybatis"</font></font>](https://blog.csdn.net/u012387062/article/details/54719114)

## [](#单例模式)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Singleton mode</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Three Implementations of the Singleton Model and Their Advantages and Disadvantages</font></font>](https://blog.csdn.net/YECrazy/article/details/79481964)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Singleton Pattern - Reflection - Preventing Serialization from Destroying Singleton Patterns</font></font>](https://www.cnblogs.com/ttylinux/p/6498822.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Use enumeration types.</font></font>

## [](#责任链模式)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Chain of responsibility model</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

## [](#mvc)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MVC</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"MVC Mode"</font></font>](http://www.runoob.com/design-pattern/mvc-pattern.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Model - view - controller</font></font>

## [](#ioc)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IOC</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Understanding the IOC</font></font>](https://www.zhihu.com/question/23277575)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"ICO Understanding and Interpretation"</font></font>](https://www.cnblogs.com/NancyStartOnce/p/6813162.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Positive control: Tradition through new.</font> <font style="vertical-align: inherit;">Reverse control, inject the object through the container.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Role: For module decoupling.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DI: Dependency Injection, that is, dependency injection, is only concerned with resource usage and does not care about the source of resources.</font></font>

## [](#aop)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AOP</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Easy to understand AOP (face-oriented programming)</font></font>](https://my.oschina.net/yanquan345/blog/203415)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Spring AOP Detailed"</font></font>](https://www.cnblogs.com/hongwz/p/5764917.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Spring AOP Implementation Principles"</font></font>](http://www.importnew.com/24305.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The dynamic proxy used by Spring AOP is mainly in two ways: JDK dynamic proxy and CGLIB dynamic proxy.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Spring AOP Implementation Principles and CGLIB Applications</font></font>](https://www.ibm.com/developerworks/cn/java/j-lo-springaopcglib/)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The principle of handling the AOP proxy class in the Spring AOP framework is: If the target object's implementation class implements the interface, Spring AOP will use the JDK dynamic proxy to generate the AOP proxy class; if the target object's implementation class does not implement the interface, Spring AOP will Use CGLIB to generate AOP proxy classes</font></font>

## [](#uml)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">UML</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"UML Tutorial"</font></font>](https://www.w3cschool.cn/uml_tutorial/)

## [](#微服务思想)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Microservice idea</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Micro Service Architecture Design"</font></font>](https://www.cnblogs.com/wintersun/p/6219259.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Microservice Architecture Technology Stack Selection Manual"</font></font>](http://www.infoq.com/cn/articles/micro-service-technology-stack)

### [](#康威定律)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Conway Law</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The Theoretical Basis of Microservice Architecture - Conway's Law"</font></font>](https://yq.aliyun.com/articles/8611)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Rule One: Organizational communication methods will be expressed through system design, which means that the layout and organizational structure of the architecture will be similar.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Law 2: Time is not possible to do more perfect one thing, but there is always time to finish one thing.</font> <font style="vertical-align: inherit;">Can't get fat in one go, but you can get it first.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Law 3: There are potentially heterogeneous homomorphic characteristics between linear systems and linear organizational structures.</font> <font style="vertical-align: inherit;">Get melons and become independent autonomous subsystems to reduce communication costs.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Law 4: Large system organizations are always more decomposed than small systems.</font> <font style="vertical-align: inherit;">All the time will be divided, divide and rule.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Microservice Architecture Core 20"</font></font>](https://static.geekbang.org/PDF-%E4%BF%AE%E6%94%B9%E7%89%88-%E6%9E%81%E5%AE%A2%E6%97%B6%E9%97%B4-%E5%9B%BE%E7%89%87-%E6%9D%A8%E6%B3%A2-%E5%BE%AE%E6%9C%8D%E5%8A%A1%E6%9E%B6%E6%9E%84.pdf)

# [](#运维--统计--技术支持)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Operation & Statistics & Technical Support</font></font>

## [](#常规监控)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">General monitoring</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Tencent Business System Monitoring Practice Road"</font></font>](https://blog.csdn.net/enweitech/article/details/77849205)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Monitoring methods: active, passive, bypass (such as public opinion monitoring)</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Monitoring type: Basic monitoring, server monitoring, client monitoring, monitoring, customer monitoring</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Monitoring objectives: full, block, accurate</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Core indicators: request volume, success rate, time-consuming</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Open source or commercial?</font> <font style="vertical-align: inherit;">Top Ten Yunyunwei Monitoring Tools Hengping Review</font></font>](https://www.oschina.net/news/67525/monitoring-tools)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zabbix, Nagios, Ganglia, Zenoss, Open-falcon, Monitor Po, 360 Website Service Monitoring, Alibaba Cloud Monitoring, Baidu Cloud Observation, Little Bee Website Monitoring, etc.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Monitoring alarm system construction and secondary development experience"</font></font>](http://developer.51cto.com/art/201612/525373.htm)

**<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Command line monitoring tool</font></font>**

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Common command line monitoring tool"</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/44-an-quan-yu-yun-wei/445-fu-wu-qi-zhuang-tai-jian-ce/4451-ming-ling-xing-gong-ju.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Top, sar, tsar, nload</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">20 Command Line Tools to Monitor Linux System Performance</font></font>](http://blog.jobbole.com/96846/)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Detailed Usage of JVM Performance Tuning Monitoring Tools jps, jstack, jmap, jhat, jstat, hprof"</font></font>](https://my.oschina.net/feichexia/blog/196575)

## [](#apm)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">APM</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">APM — Application Performance Management</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Dapper, Tracking System for Large-Scale Distributed Systems</font></font>](http://bigbully.github.io/Dapper-translation/)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CNCF OpenTracing</font></font>](http://opentracing.io)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">,</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Chinese version</font></font>](https://github.com/opentracing-contrib/opentracing-specification-zh)

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The main open source software, alphabetically sort</font></font>

    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apache SkyWalking</font></font>](https://github.com/apache/incubator-skywalking)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CAT</font></font>](https://github.com/dianping/cat)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CNCF jaeger</font></font>](https://github.com/jaegertracing/jaeger)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pinpoint</font></font>](https://github.com/naver/pinpoint)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zipkin</font></font>](https://github.com/openzipkin/zipkin)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Open source APM technology selection and actual combat"</font></font>](http://www.infoq.com/cn/articles/apm-Pinpoint-practice)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mainly based on Google's Dapper (large-scale distributed system tracking system) idea.</font></font>

## [](#统计分析)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Statistical Analysis</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The basis of traffic statistics: buried point"</font></font>](https://zhuanlan.zhihu.com/p/25195217)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Common metrics: visits and visitors, length of stay, bounce rate, exit rate, conversion rate, engagement</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Statistical tools, buried targets and buried contents commonly used by APP sites"</font></font>](http://www.25xt.com/company/17066.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Third-party statistics: UFIDA, Baidu Mobile, Rubik's Cube, App Annie, talking data, and other data.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The United States Mission Review front-end no trace buried practice"</font></font>](https://tech.meituan.com/mt-mobile-analytics-practice.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The so-called no trace, that is, the acquisition node is configured through a visualization tool, and the front end automatically analyzes the configuration and reports buried data, instead of hard coding.</font></font>

## [](#持续集成cicd)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Continuous Integration (CI/CD)</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">What is Continuous Integration?</font> <font style="vertical-align: inherit;">》</font></font>](http://www.ruanyifeng.com/blog/2015/09/continuous-integration.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8 Popular Continuous Integration Tools</font></font>](https://www.testwo.com/article/1170)

### [](#jenkins)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jenkins</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Using Jenkins for Continuous Integration"</font></font>](https://www.liaoxuefeng.com/article/001463233913442cdb2d1bd1b1b42e3b0b29eb1ba736c5e000)

### [](#环境分离)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Environmental separation</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Development, testing, and production environment separation.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Basic understanding and area of ​​development environment, production environment, and test environment"</font></font>](https://my.oschina.net/sancuo/blog/214904)

## [](#自动化运维)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Automation operation and maintenance</font></font>

### [](#ansible)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ansible</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ansible Chinese Authoritative Guide</font></font>](http://www.ansible.com.cn/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Ansible Basic Configuration and Enterprise Project Practical Cases"</font></font>](https://www.cnblogs.com/heiye123/articles/7855890.html)

### [](#puppet)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Puppet</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Automatic maintenance tools - detailed puppet"</font></font>](https://www.cnblogs.com/keerya/p/8040071.html)

### [](#chef)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Chef</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Chef Installation and Use"</font></font>](https://www.ibm.com/developerworks/cn/cloud/library/1407_caomd_chef/)

## [](#测试)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">test</font></font>

### [](#tdd-理论)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TDD theory</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Deep Interpretation - TDD (Test Driven Development)</font></font>](https://www.jianshu.com/p/62f16cd4fef3)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Based on test case coding function code, XP (Extreme Programming) core practice.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Benefits: Focus on one point at a time, reduce the burden of thinking; meet changes in demand or improve code design; clarify requirements in advance;</font></font>

### [](#单元测试)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">unit test</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Java Unit Testing JUnit"</font></font>](https://www.cnblogs.com/happyzm/p/6482886.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Compare JUnit 4 with TestNG"</font></font>](https://blog.csdn.net/hotdust/article/details/53406086)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TestNG overrides JUnit features for more complex scenarios.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Unit test major test function point"</font></font>](https://blog.csdn.net/wqetfg/article/details/50900512)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Module interface testing, local data structure testing, path testing, error handling testing, and boundary condition testing.</font></font>

### [](#压力测试)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pressure test</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Apache ab test user guide"</font></font>](https://blog.csdn.net/blueheart20/article/details/52170790)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Large Website Stress Testing and Optimization Program"</font></font>](https://www.cnblogs.com/binyue/p/6141088.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"10 mainstream pressure / load / performance test tool recommended"</font></font>](http://news.chinabyte.com/466/14126966.shtml)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"True traffic pressure measurement tool tcpcopy application analysis"</font></font>](http://quentinxxz.iteye.com/blog/2249799)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"nGrinder Easy-to-use tutorial"</font></font>](https://www.cnblogs.com/jwentest/p/7136727.html)

### [](#全链路压测)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Full-link pressure test</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Jingdong 618: Upgrade full-link pressure test program to create ForceBot for military exercises"</font></font>](http://www.infoq.com/cn/articles/jd-618-upgrade-full-link-voltage-test-program-forcebot)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Hungry? Exploration and Practice of Full Link Pressure Measurement"</font></font>](https://zhuanlan.zhihu.com/p/30306892)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Four languages, eight frameworks | Drip drop full-link pressure measurement solution"</font></font>](https://zhuanlan.zhihu.com/p/28355759)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Full-Link Pressure Test Experience"</font></font>](https://www.jianshu.com/p/27060fd61f72)

### [](#ab-灰度蓝绿测试)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">A/B, grayscale, blue-green test</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Technical Dry Goods | AB Testing and Grayscale Distribution Exploration and Practice</font></font>](https://testerhome.com/topics/11165)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"nginx grayscale publishing based on IP"</font></font>](http://blog.51cto.com/purplegrape/1403123)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Blue Green Deployment, A/B Testing, and Grayscale Publishing</font></font>](https://www.v2ex.com/t/344341)

## [](#虚拟化)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Virtualization</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Comparison of the advantages and disadvantages of three VPS virtualization technologies, OpenVZ, Xen and KVM"</font></font>](https://blog.csdn.net/enweitech/article/details/52910082)

### [](#kvm)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KVM</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"KVM Detailed, too detailed and in-depth, classic"</font></font>](http://blog.chinaunix.net/uid-20201831-id-5775661.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"[text]KVM virtual machine installation explain"</font></font>](https://www.coderxing.com/kvm-install.html)

### [](#xen)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Xen</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Xen Virtualization Fundamentals"</font></font>](https://www.cnblogs.com/sddai/p/5931201.html)

### [](#openvz)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenVZ</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open Source Linux OpenVZ Quick Start Guide</font></font>](https://blog.csdn.net/longerzone/article/details/44829255)

## [](#容器技术)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Container technology</font></font>

### [](#docker)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Several Diagrams Help You Understand Docker Fundamentals and Quick Start"</font></font>](https://www.cnblogs.com/SzeCheng/p/6822905.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker Core Technology and Implementation Principles</font></font>](https://draveness.me/docker)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker Tutorial</font></font>](http://www.runoob.com/docker/docker-tutorial.html)

## [](#云技术)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cloud technology</font></font>

### [](#openstack)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenStack</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"OpenStack architecture knowledge combing"</font></font>](https://www.cnblogs.com/klb561/p/8660264.html)

## [](#devops)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DevOps</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"What tells you exactly what DevOps is?</font> <font style="vertical-align: inherit;">》</font></font>](https://www.cnblogs.com/jetzhang/p/6068773.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DevOps Explained</font></font>](http://www.infoq.com/cn/articles/detail-analysis-of-devops)

## [](#文档管理)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Document management</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Confluence - Charge Document Management System</font></font>](http://www.confluence.cn/)
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitLab?</font></font>
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Wiki</font></font>

# [](#中间件)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Middleware</font></font>

## [](#web-server)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Web Server</font></font>

### [](#nginx)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nginx</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Basic Learning of Ngnix - Comparison of Multiple Processes and Apache"</font></font>](https://blog.csdn.net/qq_25797077/article/details/52200722)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nginx achieves high concurrency through asynchronous non-blocking event handling mechanisms.</font> <font style="vertical-align: inherit;">Apache monopolizes one thread per request and consumes system resources.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Event-driven is suitable for IO intensive services (Nginx), multi-process or thread-adapted to CPU-intensive services (Apache), so Nginx is suitable for reverse proxy, not web server use.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Comparisons and advantages and disadvantages of nginx and Apache"</font></font>](https://www.cnblogs.com/cunkouzh/p/5410154.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nginx is only suitable for static and reverse proxies and is not suitable for handling dynamic requests.</font></font>

### [](#openresty)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenResty</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Official website</font></font>](http://openresty.org/cn/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"On OpenResty"</font></font>](http://www.linkedkeeper.com/detail/blog.action?bid=1034)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The Lua module can be developed on Nginx.</font></font>

### [](#apache-httpd)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apache Httpd</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Official website</font></font>](http://httpd.apache.org/)

### [](#tomcat)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tomcat</font></font>

#### [](#架构原理)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Architecture principle</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Detailed TOMCAT Principles and Request Process"</font></font>](https://www.cnblogs.com/hggen/p/6264475.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The detailed Tomcat server principle"</font></font>](https://www.cnblogs.com/crazylqy/p/4706223.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Tomcat System Architecture and Design Patterns, Part 1: How It Works"</font></font>](https://www.ibm.com/developerworks/cn/java/j-lo-tomcat1/)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Four Diagrams Take You Through Tomcat System Architecture"</font></font>](https://blog.csdn.net/xlgen157387/article/details/79006434)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"JBoss vs. Tomcat: Choosing A Java Application Server"</font></font>](https://www.futurehosting.com/blog/jboss-vs-tomcat-choosing-a-java-application-server/)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tomcat is a lightweight Serverlet container that does not implement all JEE features (such as persistence and transaction processing) but can be replaced by other components such as Srping.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jboss implements all JEE features, free software open source, and documentation fees.</font></font>

#### [](#调优方案)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tuning plan</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tomcat Tuning Solution</font></font>](https://www.cnblogs.com/sunfenqing/p/7339058.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Start NIO mode (or APR); adjust thread pool; disable AJP connector (Nginx+tomcat architecture, no AJP required);</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"tomcat http protocol and ajp protocol"</font></font>](http://blog.chinaunix.net/uid-20662363-id-3012760.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AJP vs. HTTP Comparison and Analysis</font></font>](http://dmouse.iteye.com/blog/1354527)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The AJP protocol (port 8009) is used to reduce the number of connections (front-end) to the front-end Server (such as Apache, which also needs to support the AJP protocol), and to increase performance through long connections.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">When concurrency is high, the AJP protocol is better than the HTTP protocol.</font></font>

### [](#jetty)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jetty</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"How Jetty Works and Comparison with Tomcat"</font></font>](https://www.ibm.com/developerworks/cn/java/j-lo-jetty/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Compared advantages of jetty and tomcat"</font></font>](https://blog.csdn.net/doutao6677/article/details/51957288)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Architecture comparison: Jetty's architecture is much simpler than Tomcat's.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Performance comparison: Jetty and Tomcat have little difference in performance. Jetty uses NIO to end up with more advantages in handling I/O requests. Tomcat uses BIO to handle I/O requests by default. Tomcat is suitable for handling a few very busy links and handles static resources. Poor performance.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Other aspects: The application of Jetty is faster, simpler to modify, and better supported by the new Servlet specification; Tomcat supports JEE and Servlet more comprehensively.</font></font>

## [](#缓存)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Caching</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Cache invalidation strategy (the difference between FIFO, LRU, LFU algorithm)"</font></font>](https://blog.csdn.net/clementad/article/details/48229243)

### [](#本地缓存)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Local cache</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HashMap Local Cache</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/421-ying-yong-ceng-ben-di-huan-cun/4211.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EhCache Local Cache</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/421-ying-yong-ceng-ben-di-huan-cun/4212-ehcache.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">On-heap, off-heap, disk level 3 cache.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Can be set according to the amount of cache space.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">According to time, number of times and other expiration strategies.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Guava Cache</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/421-ying-yong-ceng-ben-di-huan-cun/4213-guava-cache.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Simple and lightweight, no heap, disk cache.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nginx Local Cache</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/422-fu-wu-duan-ben-di-huan-cun/nginx-ben-di-huan-cun.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Pagespeed - lazy tool, server-side acceleration"</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/422-fu-wu-duan-ben-di-huan-cun/4222-pagespeed.html)

## [](#客户端缓存)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Client Cache</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Browser Side Cache</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-er-pian-ff1a-feng-kuang-yuan-shi-ren/42-xing-neng-zhi-ben-di-huan-cun/423-ke-hu-duan-huan-cun.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mainly using the Cache-Control parameter.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"H5 and Mobile WebView Cache Mechanism Analysis and Combat"</font></font>](https://mp.weixin.qq.com/s/qHm_dJBhVbv0pJs8Crp77w)

## [](#服务端缓存)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Server cache</font></font>

### [](#web缓存)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Web Cache</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nuster</font></font>](https://github.com/jiangwenyuan/nuster)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">- nuster cache</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Varnish</font></font>](https://github.com/varnishcache/varnish-cache)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">- varnish cache</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Squid</font></font>](https://github.com/squid-cache/squid)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">- squid cache</font></font>

### [](#memcached)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Memcached</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Memcached Tutorial</font></font>](http://www.runoob.com/Memcached/Memcached-tutorial.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"In-depth understanding of the principle of Memcached"</font></font>](https://blog.csdn.net/chenleixing/article/details/47035453)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Use multiplexing techniques to increase concurrency.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The slab allocation algorithm: memcached allocates memory space for Slab, the default is 1MB.</font> <font style="vertical-align: inherit;">After allocating to Slab, the slab of the slab is divided into chunks of the same size. Chunk is the memory space used to cache the records. The chunk size is incremented by 1.25 times by default.</font> <font style="vertical-align: inherit;">The advantage is that it will not frequently apply for memory and improve IO efficiency. The disadvantage is that there will be a certain amount of memory waste.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"How Memcached Software Works"</font></font>](https://www.jianshu.com/p/36e5cd400580)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Memcache Technology Sharing: Introduction, Usage, Storage, Algorithms, Optimization, Hit Rate"</font></font>](http://zhihuzeye.com/archives/2361)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Differences between add, set, and replace in memcache</font></font>](https://blog.csdn.net/liu251890347/article/details/37690045)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The difference is that when the key exists or does not exist, the return value is true and false.</font></font>
*   [**<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Comprehensive Analysis of Memcached"</font></font>**](https://pan.baidu.com/s/1qX00Lti?errno=0&errmsg=Auth%20Login%20Sucess&&bduss=&ssnerror=0&traceid=)

### [](#redis)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Redis</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Redis Tutorial</font></font>](http://www.runoob.com/redis/redis-tutorial.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The principle of redis bottom"</font></font>](https://blog.csdn.net/wcf373722432/article/details/78678504)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Using ziplists to store linked lists, ziplists are a kind of compressed list, which has the advantage of saving more memory because everything it stores is in a contiguous area of ​​memory.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Skiplist is used to store ordered collection objects, search on high level, complexity of time and red-black tree, implementation is easy, lock-free and concurrency is good.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Redis Persistence Method"</font></font>](http://doc.redisfans.com/topic/persistence.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RDB mode: Periodically backs up snapshots and is commonly used for disaster recovery.</font> <font style="vertical-align: inherit;">Advantages: Backing up through the fork process does not affect the speed of the main process and RDB when recovering large data sets faster than AOF recovery.</font> <font style="vertical-align: inherit;">Disadvantages: Will lose data.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AOF mode: Save the operation log mode.</font> <font style="vertical-align: inherit;">Advantages: Less data loss during recovery, disadvantages: large files, slow response.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">It can also be used in combination.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Distributed Cache - Sequence 3 - Atomic Operations and CAS Optimistic Locking"</font></font>](https://blog.csdn.net/chunlongyu/article/details/53346436)

#### [](#架构)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Structure</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Redis Single-threaded Architecture</font></font>](https://blog.csdn.net/sunhuiliang85/article/details/73656830)

#### [](#回收策略)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Recovery strategy</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Redis Recovery Strategy"</font></font>](https://blog.csdn.net/qq_29108585/article/details/63251491)

### [](#tair)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tair</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Official website</font></font>](https://github.com/alibaba/tair)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The Comparison of Tair and Redis"</font></font>](http://blog.csdn.net/farphone/article/details/53522383)
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Features: You can configure the number of backup nodes, asynchronously to the backup node</font></font>
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Consistent hashing algorithm.</font></font>
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Architecture: Similar to the design concept of Hadoop, Configserver, DataServer, and Configserver are used to detect heartbeats. Configserver also has a master/slave relationship.</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Several storage engines:</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MDB, full memory, can be used to store data such as Session.</font></font>
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Rdb (similar to Redis), lightweight, removes operations like aof, supports Restfull operations</font></font>
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LDB (LevelDB storage engine), persistent storage, LDB as a persistence of rdb, google implementation, more efficient, theoretical basis is the LSM (Log-Structured-Merge Tree) algorithm, now modify the data in memory, reach a certain amount (and Memory aggregated old data is written to disk together. Write to disk and storage is more efficient. The county compares the hash algorithm.</font></font>
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tair uses shared memory to store data. If the service goes down (not the server), the data is still available after the service is restarted.</font></font>

## [](#消息队列)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">message queue</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Message Queue - Push/Pull Mode Learning & ActiveMQ and JMS Learning</font></font>](https://www.cnblogs.com/charlesblc/p/6045238.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The RabbitMQ consumer defaults to push mode (also supports pull mode).</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kafka defaults to pull mode.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Push mode: The advantage is that the message can be sent to the consumer as soon as possible. The disadvantage is that if the consumer's processing power cannot keep up, the consumer's buffer may overflow.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pull: The advantage is that the consumer can pull it off according to its processing power. The disadvantage is that it will increase the message delay.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Comparison of Kafka, RabbitMQ, RocketMQ and Other Message Middleware - Message Sending Performance and Difference"</font></font>](https://blog.csdn.net/yunfeng482/article/details/72856762)

### [](#消息总线)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Message bus</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The message bus is equivalent to a layer of encapsulation on the message queue, unified entrance, unified management and control, simplifying the access cost.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Message Bus VS Message Queue</font></font>](https://blog.csdn.net/yanghua_kobe/article/details/43877281)

### [](#消息的顺序)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Order of messages</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">How to ensure the order of consumers to receive messages</font></font>](https://www.cnblogs.com/cjsblog/p/8267892.html)

### [](#rabbitmq)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RabbitMQ</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Supports transactions, push and pull modes are all supported, and are suitable for scenarios requiring reliable message transmission.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"RabbitMQ Application Scenarios and Introduction to Basic Principles"</font></font>](https://blog.csdn.net/whoamiyang/article/details/54954780)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Message Queue RabbitMQ</font></font>](https://www.jianshu.com/p/79ca08116d57)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"RabbitMQ message confirmation mechanism (transaction + Confirm)"</font></font>](https://blog.csdn.net/u013256816/article/details/55515234)

### [](#rocketmq)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RocketMQ</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java implementation, push and pull modes are all supported, and the throughput is lower than Kafka.</font> <font style="vertical-align: inherit;">The order of messages can be guaranteed.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RocketMQ Reality Quick Start</font></font>](https://www.jianshu.com/p/824066d70da8)

### [](#activemq)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ActiveMQ</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pure Java implementation, compatible with JMS, can be embedded in Java applications.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Introduction to ActiveMQ Message Queue"</font></font>](https://www.cnblogs.com/wintersun/p/3962302.html)

### [](#kafka)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kafka</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">High throughput, pull mode.</font> <font style="vertical-align: inherit;">Suitable for high IO scenarios, such as log synchronization.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Official website</font></font>](http://kafka.apache.org/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Compared with the message queues, Kafka's in-depth analysis, everyone's recommendation, wonderful good!</font> <font style="vertical-align: inherit;">》</font></font>](https://blog.csdn.net/allthesametome/article/details/47362451)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Introduction and Example of Kafka Partitioning Mechanism"</font></font>](http://lxw1234.com/archives/2015/10/538.htm)

### [](#redis-消息推送)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Redis message push</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Producer and consumer patterns are completely client-side behaviors, list and pull modes are implemented, blocking waits for blpop instructions.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Redis Study Notes 10: Redis Used as Message Queue"</font></font>](https://blog.csdn.net/qq_34212276/article/details/78455004)

### [](#zeromq)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ZeroMQ</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

## [](#定时调度)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scheduled scheduling</font></font>

### [](#单机定时调度)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Stand-alone scheduled scheduling</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Linux regular task cron configuration"</font></font>](https://www.cnblogs.com/shuaiqing/p/7742382.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Linux cron operation principle"</font></font>](https://my.oschina.net/daquan/blog/483305)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Fork process + sleep poll</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Quartz Usage Summary</font></font>](https://www.cnblogs.com/drift-ice/p/3817269.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Quartz source code analysis ---- trigger start principle"</font></font>](https://blog.csdn.net/wenniuwuren/article/details/42082981/)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"quartz principle secret and source code interpretation"</font></font>](https://www.jianshu.com/p/bab8e4e32952)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scheduled scheduling In the QuartzSchedulerThread code, while() loops indefinitely, every time the loop retrieves the trigger that the time will reach, and the corresponding job is fired until the scheduler thread is closed.</font></font>

### [](#分布式定时调度)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed timing scheduling</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"These excellent domestic distributed task scheduling system, you used a few?</font> <font style="vertical-align: inherit;">》</font></font>](https://blog.csdn.net/qq_16216221/article/details/70314337)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Opencron, LTS, XXL-JOB, Elastic-Job, Uncode-Schedule, Antares</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The Basic Principles of Quartz Task Scheduling"</font></font>](https://www.cnblogs.com/zhenyuyaodidiao/p/4755649.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Quartz cluster, independent Quartz node does not communicate with another node or management node, but through the same database table to another Quartz application</font></font>

## [](#rpc)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RPC</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Implementing the RPC Framework from scratch - Principles and realization of RPC"</font></font>](https://blog.csdn.net/top_code/article/details/54615853)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Core roles: Server: The service provider exposing the service, Client: The service consumer calling the remote service, Registry: The registration center for service registration and discovery.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Performance Comparison of Distributed RPC Framework Performance Competition dubbo, motan, rpcx, gRPC, thrift"</font></font>](https://blog.csdn.net/testcs_dn/article/details/78050590)

### [](#dubbo)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Dubbo</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Official website</font></font>](http://dubbo.apache.org/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The dubbo implementation principle is briefly introduced</font></font>](https://www.cnblogs.com/steven520213/p/7606598.html)

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">** SPI ** TODO</font></font>

### [](#thrift)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Thrift</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Official website</font></font>](http://thrift.apache.org/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Thrift RPC Explained"</font></font>](https://blog.csdn.net/kesonyk/article/details/50924489)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Supports multiple languages, defining interfaces through intermediate languages.</font></font>

### [](#grpc)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gRPC</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The server can be authenticated and encrypted. In an external network environment, data security can be guaranteed.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Official website</font></font>](https://grpc.io/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"RPC Principles You Should Know"</font></font>](https://www.cnblogs.com/LBSer/p/4853234.html)

## [](#数据库中间件)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Database middleware</font></font>

### [](#sharding-jdbc)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sharding Jdbc</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Official website</font></font>](http://shardingjdbc.io/)

## [](#日志系统)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Log system</font></font>

### [](#日志搜集)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Log collection</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Build an ELKB Log Collection System from scratch"</font></font>](http://cjting.me/misc/build-log-system-with-elkb/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Establish a Simple Log Collection and Analysis System with ELK"</font></font>](https://blog.csdn.net/lzw_2006/article/details/51280058)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Log Collection System - Inquiry"</font></font>](https://www.cnblogs.com/beginmind/p/6058194.html)

## [](#配置中心)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Configuration Center</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apollo - Ctrip's Configuration Center Application</font></font>](https://github.com/ctripcorp/apollo)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Spring Boot and Spring Cloud</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Support push and pull mode update configuration</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Supports multiple languages</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Using zookeeper to achieve unified configuration management"</font></font>](https://blog.csdn.net/u011320740/article/details/78742625)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Spring Cloud Config Distributed Configuration Center Tutorial</font></font>](https://www.cnblogs.com/shamo89/p/8016908.html)

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Servlet 3.0 Asynchronous Feature Available to Configuration Center Clients</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"New Features in servlet 3.0 - Asynchronous Processing"</font></font>](https://www.cnblogs.com/dogdogwang/p/7151866.html)

## [](#api-网关)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API Gateway</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Main responsibilities: request forwarding, security authentication, protocol conversion, disaster recovery.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API Gateway Those</font></font>](http://yunlzheng.github.io/2017/03/14/the-things-about-api-gateway/)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"About the background, architecture and landing plan of API gateway"</font></font>](http://www.infoq.com/cn/news/2016/07/API-background-architecture-floo)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Using Zuul to Build an API Gateway</font></font>](https://blog.csdn.net/zhanglh046/article/details/78651993)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Kong Introduction to One of the HTTP API Gateway Selections"</font></font>](https://mp.weixin.qq.com/s/LIq2CiXJQmmjBC0yvYLY5A)

# [](#网络)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The internet</font></font>

## [](#协议)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">protocol</font></font>

### [](#osi-七层协议)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OSI Layer 7 Protocol</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"OSI seven-layer protocol model, TCP/IP four-layer model study notes"</font></font>](https://www.cnblogs.com/Robin-YB/p/6668762.html)

### [](#tcpip)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TCP/IP</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Instantly explain TCP/IP protocol"</font></font>](https://www.cnblogs.com/onepixel/p/7092302.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Three-way handshake and four waves in TCP protocol"</font></font>](https://blog.csdn.net/whuslei/article/details/6667471/)

### [](#http)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HTTP</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Details of the http protocol (super detailed)"</font></font>](https://www.cnblogs.com/wangning528/p/6388464.html)

### [](#http20)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HTTP2.0</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Detailed Analysis of HTTP 2.0 Principles"</font></font>](https://blog.csdn.net/zhuyiquan/article/details/69257126)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The basic unit of HTTP2.0 is binary frame"</font></font>](https://blog.csdn.net/u012657197/article/details/77877840)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Use binary frames for transmission.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Multiplexing.</font></font>

### [](#https)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HTTPS</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"https Principles of Popular Understanding"</font></font>](https://www.cnblogs.com/zhangshitong/p/6478721.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Using asymmetric encryption to negotiate encryption algorithms</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Use symmetric encryption to transfer data</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Use a certificate issued by a third party to encrypt the public key for secure transmission of the public key and prevent it from being altered by an intermediary.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Eight Free SSL Certificates - Adding Https Security to Your Website for Free</font></font>](https://blog.csdn.net/enweitech/article/details/53213862)

## [](#网络模型)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Network model</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The principles of web optimization must understand the five models of the I/O and the three working modes of the web."</font></font>](http://blog.51cto.com/litaotao/1289790)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Five I/O models: Blocking I/O, Non-blocking I/O, I/O Multiplexing, Event (Signal) Driven I/O, Asynchronous I/O, and the first four I/Os are synchronous operations, I/O The first stage of O is the same and the second stage is the same. The last one belongs to asynchronous operation.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Three kinds of Web Server work methods: Prefork (multi-process), Worker mode (thread mode), Event mode.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Summary of differences between select, poll, and epoll</font></font>](http://www.cnblogs.com/Anker/p/3265058.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Select, poll, and epoll are essentially synchronous I/O because they all need to be responsible for reading and writing after the read/write event is ready. This means that the read/write process is blocked.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Select has a limit on the number of open file descriptors, the default is 1024 (2048 for x64), 1 million concurrent, 1000 processes will be used, and the switching overhead is large; poll uses the linked list structure, and there is no limit to the number.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Select, poll "wake up" when iterating over the entire fd collection, and epoll "wake up" as long as the judgment is ready list is empty, through the callback mechanism to save a lot of CPU time; select, poll call every time To copy the fd set from the user state to the kernel state, epoll only needs to copy once.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">With the increase of concurrent poll, the performance gradually declines. Epoll adopts the red-black tree structure and has stable performance. It will not decrease as the number of connections increases.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"select, poll, epoll comparison"</font></font>](http://xingyunbaijunwei.blog.163.com/blog/static/76538067201241685556302/)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">In situations where the number of connections is small and the connections are very active, the performance of select and poll may be better than epoll. After all, the epoll notification mechanism requires a lot of function callbacks.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"In-depth understanding of Java NIO"</font></font>](https://www.cnblogs.com/geason/p/5774096.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NIO is a synchronous non-blocking IO model.</font> <font style="vertical-align: inherit;">Synchronization means that the thread continuously polls for IO events. Non-blocking means that the thread can wait for IO and can do other tasks at the same time.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The difference between BIO and NIO, AIO"</font></font>](https://blog.csdn.net/skiof007/article/details/52873421)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Two Efficient Server Design Models: Reactor and Proactor Models"</font></font>](https://blog.csdn.net/u013074465/article/details/46276967)

### [](#epoll)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Epoll</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"epoll use detailed (essential)"</font></font>](https://www.cnblogs.com/fnlingnzb-learner/p/5835573.html)

### [](#java-nio)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java NIO</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"In-depth understanding of Java NIO"</font></font>](https://www.cnblogs.com/geason/p/5774096.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"An example of a Java NIO writing Socket server"</font></font>](https://blog.csdn.net/xidianliuy/article/details/51612676)

### [](#kqueue)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kqueue</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kqueue usage introduction</font></font>](http://www.cnblogs.com/luminocean/p/5631336.html)

## [](#连接和短连接)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Connections and short connections</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"TCP/IP Series - Difference between Long and Short Connections"</font></font>](https://www.cnblogs.com/pangguoping/p/5571422.html)

## [](#框架)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">frame</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Netty principle analysis"</font></font>](https://blog.csdn.net/excellentyuxiao/article/details/53390408)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reactor mode introduction.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Netty is an implementation of Reactor mode.</font></font>

## [](#零拷贝zero-copy)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zero-copy</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Understanding of Zero Copy for Netty ByteBuf</font></font>](https://www.cnblogs.com/xys1228/p/6088805.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Multiple physically separate buffers are logically merged into one, thus avoiding data copying between memory.</font></font>

## [](#序列化二进制协议)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Serialization (binary protocol)</font></font>

### [](#hessian)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hessian</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Hessian Principle Analysis"</font></font>](https://www.cnblogs.com/happyday56/p/4268249.html)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">Binary-RPC; not just serialization</font></font>

### [](#protobuf)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Protobuf</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Java application example of Protobuf protocol"</font></font>](https://blog.csdn.net/antgan/article/details/52103966)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">Goolge produced, occupied space and efficiency outperformed other serialization libraries such as Hessian; need to write .proto file.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Protocol Buffers Serialization Protocol and Application"</font></font>](https://worktile.com/tech/share/prototol-buffers)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Explain about the agreement; Disadvantages: poor readability;</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Simple use of protobuf and protostuff"</font></font>](https://blog.csdn.net/eric520zenobia/article/details/53766571)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The advantage of protostuff is that instead of writing .proto files, Java objects can be serialized directly.</font></font>

# [](#数据库)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">database</font></font>

## [](#基础理论)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Basic theory</font></font>

### [](#数据库设计的三大范式)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Three paradigms of database design</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Three Paradigms of Database and Five Constraints"</font></font>](https://www.cnblogs.com/waj6511988/p/7027127.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The first normal form: each column (each field) in the data table must be the smallest unit that cannot be split, that is, to ensure the atomicity of each column;</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Second Normal Form (2NF): After satisfying 1NF, all the columns in the table must be dependent on the primary key. No column can be related to the primary key. That is, a table describes only one thing.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The third paradigm: must meet the second paradigm (2NF), requirements: each column in the table is only directly related to the primary key and not indirectly, (each column in the table can only rely on the primary key);</font></font>

## [](#mysql)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MySQL</font></font>

### [](#原理)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">principle</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"InnoDB indexing principle of MySQL"</font></font>](http://www.admin10000.com/document/5372.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"MySQL Storage Engine - Difference between MyISAM and InnoDB"</font></font>](https://blog.csdn.net/xifeijian/article/details/20316775)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The main difference between the two types is that Innodb supports transaction processing and foreign key and row-level locking</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The difference between myisam and innodb index implementation"</font></font>](https://www.2cto.com/database/201211/172380.html)

### [](#innodb)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InnoDB</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"An article with you read Mysql and InnoDB"</font></font>](https://my.oschina.net/kailuncen/blog/1504217)

### [](#优化)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">optimization</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MySQL36 Rules</font></font>](http://vdisk.weibo.com/s/muWOT)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The best 20+ experience of MYSQL performance optimization"</font></font>](https://www.cnblogs.com/zhouyusheng/p/8038224.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"SQL Optimization"</font></font>](https://blog.csdn.net/when_less_is_more/article/details/70187459)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The cause of the mysql database deadlock and the solution"</font></font>](https://www.cnblogs.com/sivkun/p/7518540.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Possibility of causing index failure"</font></font>](https://blog.csdn.net/monkey_d_feilong/article/details/52291556)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"MYSQL paging limit speed is too slow optimization method"</font></font>](https://blog.csdn.net/zy_281870667/article/details/51604540)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">In principle, it is to narrow the scanning range.</font></font>

### [](#索引)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">index</font></font>

#### [](#聚集索引-非聚集索引)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Clustered index, non-clustered index</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"MySQL Clustered Index/Non-Clustered Indexes"</font></font>](https://blog.csdn.net/no_endless/article/details/77073549)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"MyISAM and InnoDB Index Implementation"</font></font>](https://www.cnblogs.com/zlcxbb/p/5757245.html)

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MyISAM is non-clustered, InnoDB is aggregated</font></font>

#### [](#复合索引)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Composite index</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Comprehensive Index Advantages and Precautions"</font></font>](https://www.cnblogs.com/summer0space/p/7247778.html)

#### [](#自适应哈希索引ahi)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Adaptive Hash Index (AHI)</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InnoDB Storage Engine - Adaptive Hash Index</font></font>](https://blog.csdn.net/Linux_ever/article/details/62043708)

### [](#explain)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Explain</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"MySQL Performance Optimizer Explain Use Analysis"</font></font>](https://segmentfault.com/a/1190000008131735)

## [](#nosql)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NoSQL</font></font>

### [](#mongodb)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MongoDB</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MongoDB Tutorial</font></font>](http://www.runoob.com/mongodb/mongodb-tutorial.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The Advantages and Disadvantages of Mongodb vs. Relational Databases"</font></font>](http://mxdxm.iteye.com/blog/2093603)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Advantages: weak consistency (eventually consistent), better guarantee user access speed; built-in GridFS, support for large-capacity storage; Schema-less database, no pre-defined structure; built-in Sharding; compared to other NoSQL, third-party support is rich Superior performance;</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Disadvantages: mongodb does not support transaction operations; mongodb takes up too much space; MongoDB does not have mature maintenance tools such as MySQL, which is a noteworthy area for development and IT operations;</font></font>

### [](#hbase)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hbase</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Concise HBase Primer (Opening)"</font></font>](http://www.thebigdata.cn/HBase/35831.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"In-depth study of the principle of HBase architecture"</font></font>](https://www.cnblogs.com/qiaoyihang/p/6246424.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The difference between traditional row storage and (HBase) column storage"</font></font>](https://blog.csdn.net/youzhouliu/article/details/67632882)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The difference between Hbase and traditional database"</font></font>](https://blog.csdn.net/lifuxiangcaohui/article/details/39891099)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Empty data is not stored, saving space and is suitable for concurrency.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HBase Rowkey Design</font></font>](https://blog.csdn.net/u014091123/article/details/73163088)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Rowkey is arranged in lexicographic order for batch scanning.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hot spots can be avoided by hashing.</font></font>

# [](#搜索引擎)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">search engine</font></font>

## [](#搜索引擎原理)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Search Engine Principle</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Inverted Index - Search Engine Getting Started"</font></font>](https://www.jianshu.com/p/0193dc44135b)

## [](#lucene)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Lucene</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Introduction to Lucene"</font></font>](https://www.cnblogs.com/rodge-run/p/6551152.html)

## [](#elasticsearch)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Elasticsearch</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Elasticsearch learning, please look at this one!</font> <font style="vertical-align: inherit;">》</font></font>](https://blog.csdn.net/laoyang360/article/details/52244917)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Elasticsearch Index Theory</font></font>](https://blog.csdn.net/cyony/article/details/65437708)

## [](#solr)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Solr</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Apache Solr Tutorial"</font></font>](https://blog.csdn.net/u011936655/article/details/51960005)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Comparison between "elasticsearch and solr"</font></font>](https://blog.csdn.net/convict_eva/article/details/53537837)

## [](#sphinx)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sphinx</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Sphinx's Introduction and Theory Exploration"</font></font>](http://blog.jobbole.com/101672/)

# [](#性能)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">performance</font></font>

## [](#性能优化方法论)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Performance Optimization Methodology</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"15-day performance optimization work, 5 aspects of tuning experience"</font></font>](https://blog.csdn.net/huangwenyi1010/article/details/72673447?ref=myread)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Code level, business level, database level, server level, front-end optimization.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Several Aspects of System Performance Optimization"</font></font>](https://blog.csdn.net/tenglizhe/article/details/44563135)

## [](#容量评估)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Capacity assessment</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Methodology and Typical Cases for Network Performance and Capacity Assessment"</font></font>](https://blog.csdn.net/u012528360/article/details/70054156)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Internet architecture, how to design capacity?</font> <font style="vertical-align: inherit;">》</font></font>](https://mp.weixin.qq.com/s?__biz=MjM5ODYxMDA5OQ==&mid=2651959542&idx=1&sn=2494bbea9a855e0e1c3ccd6d2562a600&scene=21#wechat_redirect)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Assess total visits, evaluate average visits QPS, evaluate peak QPS, evaluate systems, stand-alone limit QPS</font></font>

## [](#cdn-网络)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CDN network</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"CDN Acceleration Principle"</font></font>](https://www.cnblogs.com/wxiaona/p/5867685.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">What are the better CDNs in China?</font> <font style="vertical-align: inherit;">》</font></font>](https://www.zhihu.com/question/20536932)

## [](#连接池)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">connection pool</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Mainstream Java Database Connection Pool Comparison and Development Configuration Actual Battle"</font></font>](https://blog.csdn.net/fysuccess/article/details/66972554)

## [](#性能调优)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Performance tuning</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nine Java performance debugging tools, at least one</font></font>](https://blog.csdn.net/yethyeth/article/details/73266455)

# [](#大数据)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Big Data</font></font>

## [](#流式计算)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flow calculation</font></font>

### [](#storm)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Storm</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Official website</font></font>](http://storm.apache.org/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The most detailed Storm tutorial</font></font>](https://blog.csdn.net/uisoul/article/details/77989927)

### [](#flink)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flink</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Flink One Flink Basic Principles Introduction"</font></font>](https://blog.csdn.net/lisi1129/article/details/54844919)

### [](#kafka-stream)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kafka Stream</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kafka Stream Research: A Lightweight Flow Computing Model</font></font>](https://yq.aliyun.com/articles/58382)

### [](#应用场景-1)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Application scenario</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">E.g:</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Advertising related real-time statistics;</font></font>
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Recommended system user image tag updates in real time;</font></font>
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Online service health monitoring in real time;</font></font>
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Real-time rankings;</font></font>
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Real-time statistics.</font></font>

## [](#hadoop)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hadoop</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"What is Hadoop, what can I do in easy-to-understand words?"</font></font>](https://blog.csdn.net/houbin0912/article/details/72967178)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The most detailed Hadoop environment in history"</font></font>](http://gitbook.cn/books/5954c9600326c7705af8a92a/index.html)

### [](#hdfs)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HDFS</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"[Hadoop Learning] HDFS Basic Principles"</font></font>](https://segmentfault.com/a/1190000011575458)

### [](#mapreduce)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MapReduce</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Introducing Map/Reduce Principles in Plain English"</font></font>](https://blog.csdn.net/oppo62258801/article/details/72884633)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Simple map-reduce java example"</font></font>](https://blog.csdn.net/foye12/article/details/78358292)

### [](#yarn)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Yarn</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Preliminary Mastery of Yarn's Architecture and Principles"</font></font>](http://www.cnblogs.com/codeOfLife/p/5492740.html)

## [](#spark)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Spark</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Spark (1): Basic Architecture and Principles"</font></font>](http://www.cnblogs.com/tgzhu/p/5818374.html)

# [](#安全)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Safety</font></font>

## [](#web-安全)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Web security</font></font>

### [](#xss)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">XSS</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"xss Attack Principles and Solutions"</font></font>](https://blog.csdn.net/qq_21956483/article/details/54377947)

### [](#csrf)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CSRF</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"CSRF Principles and Prevention"</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/641-web-an-quan-fang-fan/6412-csrf.html)

### [](#sql-注入)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SQL injection</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SQL Injection</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/641-web-an-quan-fang-fan/6413-sql-zhu-ru.html)

### [](#hash-dos)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hash Dos</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Evil JAVA HASH DOS Attack"</font></font>](http://www.freebuf.com/articles/web/14199.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Using JsonObjet to upload large Json, JsonObject uses HashMap at the bottom; different data produces the same hash value, making the build Hash slower and running out of CPU.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">An Advanced DoS Attack - Hash Collision Attack</font></font>](https://yq.aliyun.com/articles/92194?t=t1)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"About Hash Collision DoS: Parsing and Solution"</font></font>](http://www.iteye.com/news/23939/)

### [](#脚本注入)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Script injection</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The principle and prevention of the vulnerability of uploading files"</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/641-web-an-quan-fang-fan/6414-shang-chuan-wen-jian-guo-lv.html)

### [](#漏洞扫描工具)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Vulnerability Scan Tool</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"DVWA"</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/6421-dvwa.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">W3af</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/w3af.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Detailed OpenVAS</font></font>](https://blog.csdn.net/xygg0801/article/details/53610640)

### [](#验证码)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Verification code</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Verification Code Principle Analysis and Implementation"</font></font>](https://blog.csdn.net/niaonao/article/details/51112686)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Detailed Explanation of the Implementation Principle of Slip Authentication Code"</font></font>](https://my.oschina.net/jiangbianwanghai/blog/1031031)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The sliding verification code evaluates the risk based on the response time, drag speed, time, position, trajectory, number of retries, etc. of the user in the sliding slider.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taobao sliding verification code research</font></font>](https://www.cnblogs.com/xcj26/p/5242758.html)

## [](#ddos-防范)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DDoS protection</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Learning Guide: DDoS Attacks and Defenses"</font></font>](http://netsecurity.51cto.com/art/201601/503799.htm)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Free DDoS Attack Test Tool Collection"</font></font>](http://netsecurity.51cto.com/art/201406/442756.htm)

## [](#用户隐私信息保护)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">User privacy protection</font></font>

1.  <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">User password is not stored in plain text, plus dynamic slat.</font></font>
2.  <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ID number, mobile number If you want to display, replace some of the characters with "*".</font></font>
3.  <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The display of the contact information is controlled by the user himself or herself.</font></font>
4.  <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">What does "Personal Privacy include?"</font></font>](https://zhidao.baidu.com/question/1988017976673661587.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"On the Internet, what is the scope of privacy?</font> <font style="vertical-align: inherit;">》</font></font>](https://www.zhihu.com/question/20137108)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"User password save"</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/642-shu-ju-jia-mi/6425-jia-mi-chang-jing-ff1a-yong-hu-mi-ma-bao-cun.html)

## [](#序列化漏洞)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Serialization vulnerability</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Lib's past?</font> <font style="vertical-align: inherit;">Java Universal Deserialization Vulnerability Analysis</font></font>](https://blog.chaitin.cn/2015-11-11_java_unserialize_rce/)

## [](#加密解密)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">encrypt and decode</font></font>

### [](#对称加密)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Symmetric encryption</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Common symmetric encryption algorithm</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/642-shu-ju-jia-mi/6421-chang-jian-dui-cheng-jia-mi-suan-fa.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DES, 3DES, Blowfish, AES</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DES uses a 56-bit key and Blowfish uses 1- to 448-bit variable keys, AES 128, 192, and 256-bit length keys.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The DES key is too short (56-bit only) algorithm is currently replaced by AES, and AES has hardware acceleration and performs well.</font></font>

### [](#哈希算法)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hash algorithm</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Commonly used hash algorithm</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/642-shu-ju-jia-mi/6422-chang-jian-ha-xi-suan-fa-and-hmac.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MD5 and SHA-1 are no longer secure and have been deprecated.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Currently SHA-256 is relatively safe.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Public Internet URL Signature Verification Design Scheme Based on Hash Digest Signature</font></font>](https://blog.csdn.net/zhangruhong168/article/details/78033202)

### [](#非对称加密)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Asymmetric encryption</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Common Asymmetric Encryption Algorithm</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/642-shu-ju-jia-mi/6424-chang-yong-fei-dui-cheng-jia-mi-suan-fa.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RSA, DSA, ECDSA (Helix Curve Encryption Algorithm)</font></font>

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Unlike RSA, DSA can only be used for digital signatures and cannot encrypt or decrypt data. Its security is comparable to that of RSA, but its performance is faster than that of RSA.</font></font>

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The 256-bit ECC key has the same security as the 3072-bit RSA key.</font></font>

        [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Blockchain encryption technology</font></font>](http://baijiahao.baidu.com/s?id=1578348858092033763&wfr=spider&for=pc)

## [](#服务器安全)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Server security</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux Enforcement: 15 Steps to Build a Secure Linux Server</font></font>](http://www.freebuf.com/articles/system/121540.html)

## [](#数据安全)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Data Security</font></font>

### [](#数据备份)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">data backup</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

## [](#网络隔离)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Network isolation</font></font>

### [](#内外网分离)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Internal and external network separation</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

### [](#登录跳板机)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Login board</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">In the internal and external environment, log in to the online host through the springboard.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Build a simple bastion machine"</font></font>](http://blog.51cto.com/zero01/2062618)

## [](#授权认证)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Authorization, certification</font></font>

### [](#rbac)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RBAC</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Permission Design Based on Role of Organization"</font></font>](https://www.cnblogs.com/zq8024/p/5003050.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Permission System and RBAC Model Overview"</font></font>](https://www.cnblogs.com/shijiaqi1066/p/3793894.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Spring integrates Shiro to do a detailed case analysis of permission control module"</font></font>](https://blog.csdn.net/he90227/article/details/38663553)

### [](#oauth20)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OAuth2.0</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Understanding OAuth 2.0</font></font>](http://www.ruanyifeng.com/blog/2014/05/oauth_2_0.html)

### [](#双因素认证2fa)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Two-factor authentication (2FA)</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2FA - Two-factor authentication for enhanced login authentication</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Common practice is login password + phone verification code (or token key, similar to the USB key with online banking)</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">["Two-Factor Authentication (2FA) Tutorial"] (</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.ruanyifeng.com/blog/2017/11/2fa-tutorial.html</font></font>](http://www.ruanyifeng.com/blog/2017/11/2fa-tutorial.html)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">)</font></font>

### [](#单点登录sso)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Single sign-on (SSO)</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Single Sign-On Principle and Simple Implementation</font></font>](https://www.cnblogs.com/ywlaker/p/6113927.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CAS single sign-on framework</font></font>](https://github.com/apereo/cas)

# [](#常用开源框架)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Common open source framework</font></font>

## [](#开源协议)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open Source Agreement</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Open Source Agreement Selection"</font></font>](https://coderxing.gitbooks.io/architecture-evolution/chapter1/di-yi-zhang-ff1a-zhun-bei-qi-cheng/12-guan-yu-kai-yuan/123-kai-yuan-xie-yi-de-xuan-ze.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">How to choose an open source software agreement</font></font>](http://choosealicense.online/)

## [](#日志框架)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Logging framework</font></font>

### [](#log4jlog4j2)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Log4j, Log4j2</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"log4j explain in detail"</font></font>](https://blog.csdn.net/u012422446/article/details/51199724)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"log4j2 practical use Detailed Explanation"</font></font>](https://blog.csdn.net/vbirdbest/article/details/71751835)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Log4j1, Logback and Log4j2 performance test comparison"</font></font>](https://my.oschina.net/OutOfMemory/blog/789267)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Log4J asynchronous log performance is excellent.</font></font>

### [](#logback)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Logback</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The most comprehensive LogBack detailed, with java case and configuration instructions"</font></font>](https://blog.csdn.net/rulon147/article/details/52620541)

## [](#orm)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ORM</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ORM Framework Uses Advantages and Disadvantages</font></font>](https://blog.csdn.net/sinat_34093604/article/details/53082000)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The main purpose is to improve the development efficiency.</font></font>

**<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MyBatis:</font></font>**

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Mybatis caching mechanism explain"</font></font>](https://www.cnblogs.com/winclpt/articles/7511672.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The first level cache is the SqlSession level cache, the cached data only valid in the SqlSession</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The second-level cache is the mapper-level cache, which is shared by the same namespace, so the SqlSession is shared; the cache is cleared using the LRU mechanism, and is enabled by the cacheEnabled parameter.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"MyBatis Learning Code Generator Generator"</font></font>](https://blog.csdn.net/baidu_32877851/article/details/53959268)

## [](#网络框架)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Network framework</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

## [](#web-框架)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Web framework</font></font>

### [](#spring-家族)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Spring family</font></font>

**<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Spring</font></font>**

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Spring Concise Tutorial</font></font>](https://www.w3cschool.cn/wkspring/)

**<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Spring Boot</font></font>**

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Official website</font></font>](http://projects.spring.io/spring-boot/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Spring Boot Basic Tutorial</font></font>](http://blog.didispace.com/Spring-Boot%E5%9F%BA%E7%A1%80%E6%95%99%E7%A8%8B/)

**<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Spring Cloud</font></font>**

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Spring Boot Chinese Index Station</font></font>](http://springboot.fun/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Spring Cloud Chinese Documentation</font></font>](https://springcloud.cc/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Spring Cloud Basic Tutorial</font></font>](http://blog.didispace.com/Spring-Cloud%E5%9F%BA%E7%A1%80%E6%95%99%E7%A8%8B/)

## [](#工具框架)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tool frame</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Introduction and Simple Use of Apache Commons Tools"</font></font>](https://www.cnblogs.com/crazylqy/p/4872236.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Google guava Chinese Course</font></font>](http://ifeve.com/google-guava/)

# [](#分布式设计)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed design</font></font>

## [](#扩展性设计)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scalable design</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ten Top Ten Scalable Architectures that Architects Must Know</font></font>](https://blog.csdn.net/hemin1003/article/details/53633926)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">In summary, the common routine is distribution, caching, and asynchronous processing.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Scalability Design Data Segmentation"</font></font>](https://yq.aliyun.com/articles/38119)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Horizontal splitting + vertical splitting</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Use middleware for sharding such as MySQL Proxy.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Segmentation is performed using a sharding strategy, such as modulo the ID.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Talk about how to implement scalable large-scale website architecture"</font></font>](https://blog.csdn.net/deniro_li/article/details/78458306)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed Services + Message Queuing.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Large Web Site Technology Architecture (7)--Website Extensibility Framework"</font></font>](https://blog.csdn.net/chaofanwei/article/details/29191073)

## [](#稳定性--高可用)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Stability & High Availability</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"System Design: Some Technical Solutions for High Availability Systems"</font></font>](https://blog.csdn.net/hustspy1990/article/details/78008324)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Scalable: horizontal expansion, vertical expansion.</font> <font style="vertical-align: inherit;">Through redundant deployment, single points of failure are avoided.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Isolation: Avoiding a single business occupies all resources.</font> <font style="vertical-align: inherit;">Avoid business interactions 2\. Computer room isolation avoids single points of failure.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Decoupling: Reduce maintenance costs and reduce coupling risks.</font> <font style="vertical-align: inherit;">Reduce dependence and reduce mutual influence.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Current limiting: sliding window counting, leaky bucket algorithm, token bucket algorithm and other algorithms.</font> <font style="vertical-align: inherit;">When encountering burst traffic, ensure the system is stable.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Degradation: The release of non-core functional resources in an emergency.</font> <font style="vertical-align: inherit;">Sacrifice non-core business to ensure high availability of core business.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Fuse: An abnormal condition exceeds the threshold and enters the blown state and quickly fails.</font> <font style="vertical-align: inherit;">Reduce the impact of unstable external dependencies on core services.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Automated testing: Reduce faults caused by publications through comprehensive testing.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grayscale publishing: Grayscale publishing is a compromise between speed and security that can effectively reduce release failures.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"About Highly Available Systems"</font></font>](https://coolshell.cn/articles/17459.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Design principles: data is not lost (persistent); service is highly available (copy of service); absolute 100% high availability is difficult, the goal is to do as much as 9, such as 99.999% (accrued for only 5 minutes throughout the year).</font></font>

### [](#硬件负载均衡)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hardware load balancing</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"turn!</font> <font style="vertical-align: inherit;">!</font> <font style="vertical-align: inherit;">Comparison of the advantages and disadvantages of the load balancer technology Nginx and F5</font></font>](https://www.cnblogs.com/wuyun-blog/p/6186198.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mainly compared with F5.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">How much do you know about software/hardware load balancing products?</font> <font style="vertical-align: inherit;">》</font></font>](https://www.cnblogs.com/lcword/p/5773296.html)

### [](#软件负载均衡)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Software load balancing</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Several load balancing algorithms"</font></font>](https://www.cnblogs.com/tianzhiliang/articles/2317808.html)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">round robin, weight, load, least connection, QoS</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DNS Load Balancing</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/611-dns-fang-shi.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The configuration is simple and the update speed is slow.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nginx Load Balancing</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/613-nginx-fu-zai-jun-heng.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Simple and lightweight, low learning cost; mainly suitable for web applications.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Load balancing with LVS+Keepalived"</font></font>](https://www.cnblogs.com/edisonchou/p/4281978.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The configuration comparison load only supports up to four layers and the performance is high.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"HAProxy usage details of the entire network of the most detailed Chinese document"</font></font>](http://www.ttlsa.com/linux/haproxy-study-tutorial/)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Support to seven layers (such as HTTP), more comprehensive features, performance is not bad.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Haproxy + Keepalived + MySQL to achieve read-balance load"</font></font>](http://blog.itpub.net/25704976/viewspace-1319781/)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mainly load balancing of user read requests.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"rabbitmq+haproxy+keepalived achieve high availability cluster construction"</font></font>](https://www.cnblogs.com/lylife/p/5584019.html)

### [](#限流)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Limiting</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Talk about the Current Limitations of High Concurrent Systems"</font></font>](https://www.cnblogs.com/haoxinyue/p/6792309.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Counter: Sliding the window counter to control the number of requests per unit time, simple and crude.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Leaky bucket algorithm: Fixed-capacity leaky buckets, which are frequently used when the leaky bucket is full.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Token bucket algorithm: a fixed-capacity token bucket. To add a token at a certain rate, the token needs to be obtained before the request is processed. If the token is not available, the request is discarded or the queue is dropped. The rate of adding the token can be controlled. To control the overall speed.</font> <font style="vertical-align: inherit;">The RateLimiter in Guava is an implementation of a token bucket.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nginx limiting: By</font> </font>`limit_req`<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">limiting the number of concurrent connections module.</font></font>

### [](#应用层容灾)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Application layer disaster recovery</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Avalanche Fighters: Principles and Uses of Fused Hystrix"</font></font>](https://segmentfault.com/a/1190000005988895)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Avalanche effect causes: hardware failures, hardware failures, program bugs, retries to increase traffic, and user requests.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Avalanche countermeasures: current limit, improved cache mode (cache preload, synchronous call change asynchronous), automatic expansion, and degraded.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hystrix Design Principles:</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Resource isolation: Hystrix avoids service avalanche by isolating each dependent service by assigning separate thread pools for resource isolation.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Fuse switch: health status of service = request failures / total number of requests, threshold setting and sliding window control switch.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Command mode: wraps the service invocation logic by inheriting the HystrixCommand.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cache Penetration, Cache Breakdown, Cache Avalanche Solution Analysis</font></font>](https://blog.csdn.net/zeb_perfect/article/details/54135506)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Cache Breakdown, Failure, and Hot Key Problems"</font></font>](https://blog.csdn.net/zeb_perfect/article/details/54135506)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The main strategy: failure instant: stand-alone use of locks; use of distributed lock; not expire;</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hotspot data: Hotspot data is stored separately; use local cache; divided into multiple subkeys;</font></font>

### [](#跨机房容灾)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cross-room disaster recovery</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Distribution Experience of Multi-Room and Multi-Rooms"</font></font>](http://dc.idcquan.com/ywgl/71559.shtml)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Synchronous data synchronization through self-developed middleware.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Disposal of living in different places (remote living) experience"</font></font>](https://blog.csdn.net/jeffreynicole/article/details/48135093)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pay attention to the delay problem. Multiple calls across the room will amplify the delay several times.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">There is a large probability that there will be a large number of building room lines, and fault tolerance will be done at the operation and maintenance level and at the program level.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Can not rely on dual-write data in the program, there must be automatic synchronization program.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The data never considers high delays or poor network quality, considering synchronization quality issues.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The core business and the secondary business are divided and conquered, and even only the core business is considered.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Remote live monitoring deployment and testing should also keep up.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Consider user partitions where business is allowed, especially games and email services.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Control the size of the message body across the room, the smaller the better.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Consider using docker container virtualization technology to improve dynamic scheduling capabilities.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Disaster recovery technology and construction experience</font></font>](https://blog.csdn.net/yoara/article/details/38013751)

### [](#容灾演练流程)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Disaster recovery drill process</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Reliance Governance, Grayscale Distribution, Fault Exercises, Design and Practical Experience of Alibaba.com's Fault Exercise System"</font></font>](https://mp.weixin.qq.com/s?__biz=MjM5MDE0Mjc4MA==&mid=2650996320&idx=1&sn=0ed3be190bbee4a9277886ef88cbb2e5)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Common fault portrait</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Case: Preplan validity, plan validity, fault replication, architecture disaster recovery testing, parameter tuning, parameter tuning, fault raid, and joint drill.</font></font>

### [](#平滑启动)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Smooth start</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Smooth restart application ideas 1\. End-point traffic (such as vip layer), 2\. Flush data (if any), 3, restart the application</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The JVM security exit (how to gracefully shut down the java service)"</font></font>](https://blog.csdn.net/u011001084/article/details/73480432)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">Recommended to introduce: System.exit, Kill SIGTERM; not recommended kill-9; use Runtime.addShutdownHook registration hook.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"How Common Java Applications</font></font>](http://ju.outofmemory.cn/entry/337235)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">Are</font> [<font style="vertical-align: inherit;">Gracefully Closed"</font>](http://ju.outofmemory.cn/entry/337235) <font style="vertical-align: inherit;">Java, Srping, Dubbo gracefully closes.</font></font>

## [](#数据库扩展)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Database expansion</font></font>

### [](#读写分离模式)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Read-write separation mode</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Implementation of Mysql master-slave scheme"</font></font>](https://www.cnblogs.com/houdj/p/6563771.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Build MySQL Master-Slave Replication Classic Architecture"</font></font>](https://www.cnblogs.com/edisonchou/p/4133148.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Haproxy+ Load Balancing with Multiple MySQL Slave Servers"</font></font>](https://blog.csdn.net/nimasike/article/details/48048341)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DRBD+Heartbeat+Mysql High Availability Read/Write Detach Architecture</font></font>](https://www.cnblogs.com/zhangsubai/p/6801764.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DRDB performs disk copying to avoid single points of problems.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"MySQL Cluster Method"</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/62-ke-kuo-zhan-de-shu-ju-ku-jia-gou/621-gao-ke-yong-mysql-de-ji-zhong-fang-an/6214-mysql-cluster-fang-an.html)

### [](#分片模式)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Fragmentation mode</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Sub-tables need to consider the issues and programs"</font></font>](https://www.jianshu.com/p/32b3e91aa22c)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Middleware: Lightweight: sharding-jdbc, TSharding; Heavyweight: Atlas, MyCAT, Vitess, etc.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Problem: transaction, Join, migration, expansion, ID, paging, etc.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Transaction compensation: reconciliation of data; comparison based on logs; regular synchronization with standard data sources.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sub-library strategy: numerical range; modulus; date, etc.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The number of sub-libraries: usually MySQL single library 50 million, Oracle single library 100 million need to sub-library.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"MySql Table and Table Partition Detailed"</font></font>](https://www.2cto.com/database/201503/380348.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Partitioning: It is an internal mechanism of MySQL. It is transparent to the client. Data is stored in different files. On the surface, it is the same table.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Table: Physically create different tables, clients need to manage the sub-table routing.</font></font>

## [](#服务治理)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Service governance</font></font>

### [](#服务注册与发现)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Service Registration and Discovery</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Never lose contact!</font> <font style="vertical-align: inherit;">How to achieve service discovery in microservice architecture?</font> <font style="vertical-align: inherit;">》</font></font>](https://blog.csdn.net/jiaolongdy/article/details/51188798)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Client service discovery mode: The client directly queries the registry and is responsible for load balancing.</font> <font style="vertical-align: inherit;">Eureka uses this approach.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Server-side service discovery mode: The client queries service instances through load balancing.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"SpringCloud Service Registry Comparison: Consul vs Zookeeper vs Etcd vs Eureka"</font></font>](https://blog.csdn.net/u010963948/article/details/71730165)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CAP support: Consul (CA), zookeeper (cp), etcd (cp), Euerka (ap)</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The author thinks Consul's support for Spring cloud is better.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Zookeeper based service registration and discovery"</font></font>](http://mobile.51cto.com/news-502394.htm)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Advantages: API is simple, Pinterest, Airbnb in use, multi-language, through the watcher mechanism to achieve configuration PUSH, can quickly respond to configuration changes.</font></font>

### [](#服务路由控制)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Service Routing Control</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed Services Framework Study Notes 4 Service Routing</font></font>](https://blog.csdn.net/xundh/article/details/59492750)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Principle: Transparent routing</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Load Balancing Policy: Random, Polling, Service Call Latency, Consistent Hash, Sticky Connection</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Local routing has a limited strategy: injvm (preferentially calling jvm internal services) and initial (priority using the same physical machine services), and in principle finding the nearest service.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Configuration method: unified registry, local configuration, and dynamic delivery.</font></font>

## [](#分布式一致)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed consensus</font></font>

### [](#cap-与-base-理论)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CAP and BASE theory</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Discussing CAP Theory, BASE Theory from Distributed Consistency"</font></font>](http://www.cnblogs.com/szlbm/p/5588543.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Consistency classification: strong agreement (immediately consistent); weakly consistent (achievable in units of time, such as seconds); eventually consistent (weakly consistent, eventually consistent within a certain period of time)</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CAP: Consistency, Availability, Partition Fault Tolerance (Cause of Network Failure)</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BASE: Basically Available, Soft state, and Eventually consistent</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The core idea of ​​BASE theory is: Even if it can not achieve strong consistency, but each application can be based on their own business characteristics, using appropriate methods to achieve the final consistency of the system.</font></font>

### [](#分布式锁)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed lock</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Several Implementations of Distributed Locks"</font></font>](http://www.hollischuang.com/archives/1716)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Database-based distributed locks: Advantages: Simple and easy to understand.</font> <font style="vertical-align: inherit;">Disadvantages: There is a single point problem, the database can be a large overhead, not reentrant;</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cache-based distributed locks: Advantages: Non-blocking, good performance.</font> <font style="vertical-align: inherit;">Disadvantages: Operation is not easy to cause the lock can not be released.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zookeeper distributed lock: The lock mechanism is implemented by an orderly temporary node, and its corresponding node needs to be the smallest, and it is considered that the lock is obtained.</font> <font style="vertical-align: inherit;">Advantages: The cluster can solve single problems transparently, avoiding locks from being released, and locks can be reentrant.</font> <font style="vertical-align: inherit;">Disadvantages: Performance is not as good as caching, and throughput decreases as the zk cluster grows in size.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Zookeeper Based Distributed Lock"</font></font>](https://www.tuicool.com/articles/VZJr6fY)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Clear principle description + Java code example.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"jedisLock-redis distributed lock implementation"</font></font>](https://www.cnblogs.com/0201zcr/p/5942748.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Based on setnx(set if ont exists), it returns false, otherwise it returns true.</font> <font style="vertical-align: inherit;">And support expired time.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Memcached and Redis Distributed Locking Scheme</font></font>](https://blog.csdn.net/albertfly/article/details/77412333)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Use the add (as opposed to set) operation of memcached to return false when the key exists.</font></font>

### [](#分布式一致性算法)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed consensus algorithm</font></font>

#### [](#paxos)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PAXOS</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Distributed Series Articles - Principles and Derivation of Paxos Algorithm"</font></font>](https://www.cnblogs.com/linbingdong/p/6253479.html)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Paxos-->Fast Paxos-->Zookeeper Analysis</font></font>](https://blog.csdn.net/u010039929/article/details/70171672)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Distributed" Zookeeper and Paxos</font></font>](https://www.cnblogs.com/leesf456/p/6012777.html)

#### [](#zab)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zab</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Introduction to Distributed Coherence Protocols in Zab:Zookeeper"</font></font>](https://www.jianshu.com/p/fb527a64deee)

#### [](#raft)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Raft</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Why is Raft More Easier to Understand Distributed Consistency Algorithms?</font></font>](http://www.cnblogs.com/mindwind/p/5231986.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Three roles: Leader, Follower, Candidate</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The ballot was sent out by way of random waiting, winning more votes.</font></font>

#### [](#gossip)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gossip</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gossip algorithm</font></font>](http://blog.51cto.com/tianya23/530743)

#### [](#两阶段提交多阶段提交)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Two-phase commit, multi-phase commit</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"About Distributed Transactions, Two-Phase Commit Protocol, Third-Order Commit Protocol"</font></font>](http://blog.jobbole.com/95632/)

### [](#幂等)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Idempotent</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Distributed Systems - Idempotency Design"</font></font>](https://www.cnblogs.com/wxgblogs/p/6639272.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The role of idempotency: The resource is idempotent and the requester doesn't need to worry about repeated calls that can generate errors.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Common means to guarantee idempotency: MVCC (similar to optimistic locking), deduplication table (unique index), pessimistic locking, one-time token, serial number mode.</font></font>

### [](#分布式一致方案)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed consensus solution</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed System Transactional Conformance Solution</font></font>](http://www.infoq.com/cn/articles/solution-of-distributed-system-transaction-consistency)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Six Plans to Guarantee the Consistency of Distributed System Data"</font></font>](https://weibo.com/ttarticle/p/show?id=2309403965965003062676)

### [](#分布式-leader-节点选举)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed Leader node election</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Using zookeeper for distributed leader node elections"</font></font>](https://blog.csdn.net/johnson_moon/article/details/78809995)

### [](#tcctryconfirmcancel-柔性事务)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TCC (Try/Confirm/Cancel) Flexible Transactions</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Traditional and Flexible Affairs"</font></font>](https://www.jianshu.com/p/ab1a1c6b08a1)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Based on BASE theory: basic availability, flexibility, and eventual consistency.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Solution: Record log + compensation (forward supplement or rollback), message retry (requires the program to be exponentiated, etc.); "no lock design", using optimistic locking mechanism.</font></font>

## [](#分布式文件系统)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Distributed File System</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Talk about distributed file storage system - basic architecture</font></font>](https://zhuanlan.zhihu.com/p/27666295)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">?</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Compare the distributed file system"</font></font>](https://blog.csdn.net/gatieme/article/details/44982961)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">?</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HDFS: Read and write large amounts of data for high-throughput scenarios, not for small files.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FastDFS: lightweight, suitable for small files.</font></font>

## [](#唯一id-生成)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Unique ID generation</font></font>

### [](#全局唯一id)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Globally unique ID</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Generating Globally Unique Id Summary in Highly Concurrent Distributed Systems</font></font>](https://www.cnblogs.com/baiwa/p/5318432.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Twitter scheme (Snowflake algorithm): 41-bit timestamp + 10-digit machine identifier (such as IP, server name, etc.) + 12-digit serial number (local counter)</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flicker project: MySQL self-increment ID + "REPLACE INTO XXX:SELECT LAST_INSERT_ID();"</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">UUID: Disadvantages, unordered, too long strings, take up space, affect retrieval performance.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MongoDB Scenario: Use ObjectId.</font> <font style="vertical-align: inherit;">Disadvantages: can not increase.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The TDDL SEQUENCE Principle Under Distributed</font></font>](https://blog.csdn.net/hdu09075340/article/details/79103851)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Create a sequence table in the database to record the maximum value of the id that is currently occupied.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Each client host takes an id interval (such as 1000~2000) cached locally, and updates the id maximum record in the sequence table.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Different id ranges are used between client hosts. After they are used up and fetched, optimistic locking is used to control concurrency.</font></font>

## [](#一致性hash算法)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Consistent hashing algorithm</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The consistent hash algorithm</font></font>](https://coderxing.gitbooks.io/architecture-evolution/di-san-pian-ff1a-bu-luo/631-yi-zhi-xing-ha-xi.html)

# [](#设计思想--开发模式)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Design Ideas & Development Models</font></font>

## [](#ddddomain-driven-design---领域驱动设计)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DDD (Domain-driven Design - Domain Driven Design)</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Talking about my understanding of DDD-driven design"</font></font>](https://www.cnblogs.com/netfocus/p/5548025.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Concept: DDD is mainly proposed for the separation of the various stages of the traditional software development process (Analysis-Design-Code) to avoid undeliverable software (and requirements) due to unclear analysis at first or inconsistent information flow during software development. Assuming inconsistencies).</font> <font style="vertical-align: inherit;">DDD emphasizes that everything is centered on the domain and emphasizes the role of Domain Expert. It emphasizes that the domain model is first defined and then developed, and the domain model can guide the development (the so-called driver).</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Process: Understanding the domain, splitting the domain, refining the domain, the accuracy of the model depends on the depth of understanding of the model.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Design: DDD proposes modeling tools such as aggregations, entities, value objects, factories, warehousing, domain services, and domain events to help with domain modeling.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Summary of Domain Driven Design Basics"</font></font>](https://www.cnblogs.com/butterfly100/p/7827870.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Domain (Doamin) is essentially a problem domain, such as an e-commerce system, a forum system, etc.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bounded Context: Explains the relationship between subdomains and can be simply understood as a subsystem or component module.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Domain Model: The core of DDD is to establish the correct domain model (using universal description language, tools, and domain common language); to reflect the nature of business requirements, including entities and processes; it runs through software analysis, design, and development. Process; commonly used expression field model: diagram, code or text;</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Domain common language: Domain experts, developers and designers can have immediate language or tools.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The classic layered architecture: user interface/presentation layer, application layer, domain layer, and infrastructure layer is a four-tier architecture model.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The mode used:</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Link as little as possible, as far as possible single item, try to reduce the overall complexity.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Entity: The only indication in the domain that an entity has as few attributes as possible and at least as clear.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Value Object: There is no unique identifier, and the property value is immutable. The second is a simple object, such as Date.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Domain Service: Coordinate multiple domain objects, only the method has no state (no data); it can be divided into application layer services, domain layer services, and basic layer services.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Aggregate, Aggregate Root: Aggregate defines a set of related objects with a cohesive relationship; the aggregate root is the only element of the aggregate reference; when modifying an aggregate, it must be at the transaction level; most areas In the model, 70% of aggregates usually have only one entity, and 30% only have 2 to 3 entities; if an aggregate has only one entity, then this entity is the aggregate root; if there are multiple entities, then we can think about which object in the aggregate Has independent significance and can interact with the outside directly;</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Factory: Similar to the factory mode in design mode.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Repository: Persisting to DB, managing objects, and designing storage only for aggregates.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Realm Driven Design (DDD) Road to Realization"</font></font>](http://www.cnblogs.com/Leo_wl/p/3866629.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Aggregation: For example, a Car contains components such as Engine, Wheel, and Tank.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Field-Driven Design Series (2) Analysis of VO, DTO, DO, PO Concepts, Differences, and Uses"</font></font>](http://www.hollischuang.com/archives/553)

### [](#命令查询职责分离cqrs)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Command Query Separation of Duties (CQRS)</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CQRS - Command Query Responsibility Seperation</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Field Driven Design Series (6): CQRS"</font></font>](https://www.cnblogs.com/cnblogsfans/p/4551990.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The core idea: read and write separation (inquiry and update in different methods), different processes are only different design methods, CQ code separation, there will be obvious manifestation in the distributed environment (in the case of redundant data), the purpose is For high performance.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Comparison of advantages and disadvantages of DDD CQRS architecture and traditional architecture"</font></font>](http://www.techweb.com.cn/network/system/2017-07-07/2553563.shtml)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ultimately consistent design concept; depends on highly available message middleware.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Introduction to CQRS Architecture"</font></font>](http://www.cnblogs.com/netfocus/p/4055346.html)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">An abstract case of implementing CQRS.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Depths: My Thoughts on CQRS/EventSourcing Architecture</font></font>](http://www.uml.org.cn/zjjs/201609221.asp)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CQRS Pattern Analysis + 12306 Ticket Picking Cases</font></font>

### [](#贫血充血模型)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Anemia, congestive model</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Anemia, explanation of hyperemia model, and some experience"</font></font>](https://kb.cnblogs.com/page/520743/)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Blood loss model: Lao Tzu and son are defined separately, and they do not know each other. There is no business logic in the entity definition of the two, and they are related through external services.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Anemia model: Laozi knows son, son also knows Laozi; part of the business logic is put into the entity; Advantages: Individual layers of dependent, structural clear, easy to maintain; Disadvantages: does not meet the OO thinking, compared to the congestion model, the service layer is more heavy ;</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Congestion model: Similar to the anemia model, the difference lies in how to divide the business logic.</font> <font style="vertical-align: inherit;">Advantages: The service layer is relatively thin, only acts as a facade, does not deal with DAO, compound OO thinking; disadvantages: non-single dependency, bi-directional dependency between DO and DAO, and logical division of the Service layer is likely to cause confusion.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Swollen mode: It is an extreme situation, cancel the service layer, all the business logic in DO; Advantages: in line with OO ideas, simplification of layering; Disadvantages: too much exposure information, many non-DO logic will be forced into DO.</font> <font style="vertical-align: inherit;">This pattern should be avoided.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The authors advocate using the anemia model.</font></font>

## [](#actor-模式)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Actor mode</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

## [](#响应式编程)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reactive programming</font></font>

### [](#reactor)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reactor</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

### [](#rxjava)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RxJava</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

### [](#vertx)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Vert.x</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

## [](#dodaf20)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DODAF2.0</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"DODAF2.0 Methodology"</font></font>](http://www.360doc.com/content/16/0627/19/33945750_571201779.shtml)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">How DodiF2.0's Capability Perspective Goes?</font></font>](http://blog.51cto.com/xiaoyong/1553164)

## [](#serverless)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Serverless</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

## [](#service-mesh)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Service Mesh</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">What is Service Mesh?</font> <font style="vertical-align: inherit;">》</font></font>](https://time.geekbang.org/article/2355)

# [](#项目管理)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Project management</font></font>

## [](#架构评审)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Architecture review</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"How architecture design reviews architecture design specifications"</font></font>](http://developer.51cto.com/art/201506/478486.htm)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Everyone is an architect: Non-functional requirements"</font></font>](https://blog.csdn.net/wireless_com/article/details/45935591)

## [](#重构)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reconstruction</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Reconstruction of the 12 Military Rules"</font></font>](http://www.infoq.com/cn/articles/architect-12-rules-complete/)

## [](#代码规范)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Code specification</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

## [](#代码-review)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Code Review</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Institution or system! In addition, each company needs to develop its own check list based on its own needs and goals.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Why did you do bad Code Review?</font> <font style="vertical-align: inherit;">》</font></font>](http://www.sohu.com/a/229745352_181657)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The code review does well in institutional building.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"From scratch Code Review"</font></font>](https://blog.csdn.net/uxyheaven/article/details/49773619)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Code Review Checklist</font></font>](https://www.cnblogs.com/zuoping/p/5477047.html)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Java Code Review Checklist"</font></font>](https://dzone.com/articles/java-code-review-checklist)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"How to use gitlab for code review"</font></font>](https://blog.csdn.net/legend0011/article/details/45585575)

## [](#rup)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RUP</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Using RUP 4+1 View Method for Software Architecture Design"</font></font>](https://blog.csdn.net/apanious/article/details/51011946)

## [](#看板管理)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kanban Management</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Talk about the Application of Kanban in Projects"</font></font>](https://blog.csdn.net/tkchen/article/details/51637643)

## [](#scrum)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SCRUM</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SCRUM - Scrimmage</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Three roles: Product Owner (PO) Product Owner; Scrum Master (SM) to promote Scrum execution; Team development team.</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3 artifacts: Product Backlog product TODOLIST, with priority; Sprint Backlog function development TODO LIST; burn down diagram;</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Five Values: Focus, Courage, Openness, Commitment, Respect.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Agile project management process - Scrum framework is the most complete!</font> <font style="vertical-align: inherit;">》</font></font>](https://blog.csdn.net/inny100_100/article/details/54633757)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Agile is actually very simple 3 - scrum agile method"</font></font>](https://blog.csdn.net/superkunkun/article/details/52951142)

## [](#敏捷开发)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Agile development</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

## [](#极限编程xp)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Extreme Programming (XP)</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">XP - eXtreme Programming</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Mainstream Agile Development Method: Extreme Programming XP"</font></font>](http://www.woshipm.com/pmd/406917.html)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">It is a methodology to guide developers.</font></font>

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4 great values:</font></font>

        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Communication: Encourage verbal communication and increase efficiency.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Simple: Just enough.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Feedback: timely feedback, notify relevant people.</font></font>
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Courage: Advocate embrace change, dare to reconstruct.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Five principles: fast feedback, simple assumptions, gradual modification, promotion of change (small step run), high quality work (guarantee the quality of the premise to guarantee small steps run).</font></font>

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5 jobs: Staged sprints; sprint planning meetings; daily standing meetings; sprint review;</font></font>

## [](#结对编程)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pair programming</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Write code, edge review.</font> <font style="vertical-align: inherit;">Can enhance code quality and reduce bugs.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pair Programming</font></font>](http://www.baike.com/wiki/%E7%BB%93%E5%AF%B9%E7%BC%96%E7%A8%8B)

## [](#fmea管理模式)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FMEA management model</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

# [](#通用业务术语)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">General Business Terms</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

# [](#技术趋势)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Technical trends</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

# [](#政策法规)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Policies and regulations</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

## [](#法律)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">legal</font></font>

### [](#严格遵守刑法253法条)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Strictly abide by Article 253 of the Criminal Law</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Article 253 of the Chinese Criminal Law states:</font></font>

> *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Staff of state agencies or units in finance, telecommunications, transportation, education, medical care, etc., who, in violation of state regulations, sell or illegally provide personal information of citizens obtained by the entity in the course of performing its duties or providing services to others, if the circumstances are serious, Departments shall be sentenced to fixed-term imprisonment of not more than 3 years or criminal detention and shall be concurrently executed or a single fine.</font></font>
> *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">If the above information is stolen or otherwise illegally obtained, and the circumstances are serious, it shall be punished in accordance with the provisions of the preceding paragraph.</font></font>
> *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">If a unit guilty of the first two crimes, the unit shall be fined, and the person directly in charge and other persons directly responsible shall be punished in accordance with the provisions of each paragraph.</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The Supreme People's Court and the Supreme People's Procuratorate's Supplementary Provisions (IV) on the enforcement of the "Criminal Law of the People's Republic of China" confirming that the offender violates paragraph 1 of Article 253 of the Criminal Law and constitutes the crime of "selling and illegally providing personal information of citizens"; Infringe the provisions of paragraph 2 of Article 253 of the Criminal Law and constitute the crime of “illegal acquisition of personal information of citizens”</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Illegal Acquisition of Personal Information of Citizens"</font></font>](https://baike.baidu.com/item/%E9%9D%9E%E6%B3%95%E8%8E%B7%E5%8F%96%E5%85%AC%E6%B0%91%E4%B8%AA%E4%BA%BA%E4%BF%A1%E6%81%AF%E7%BD%AA)

# [](#架构师素质)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Architect quality</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Architect Portrait</font></font>](http://hellojava.info/?p=430)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Business understanding and abstraction capabilities</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NB's code capabilities</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Comprehensiveness: 1\. Will there be multiple technical solutions in the minds of architects in the face of business problems; 2\. Do you consider enough aspects in the design of the system? 3\. Do you consider enough in system design? Many aspects;</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Global: Whether to consider the impact on the upstream and downstream systems.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tradeoffs: trade-offs between input-output ratios; priority and rhythm control;</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">What Things Architects Must Know About Architecture Optimization and Design</font></font>](http://www.infoq.com/cn/articles/architecture-optimization-and-design-the-architect-must-know)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The details to consider: Modular, light-coupled, shared-nothing architecture; reduction of dependencies before individual components, attention to dependencies between services, and all the resulting chain failures and effects.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Comprehensive consideration of infrastructure, configuration, testing, development, operation and maintenance.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Consider the influence of people, teams, and organizations.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"How can I really improve myself and become an outstanding architect?</font> <font style="vertical-align: inherit;">》</font></font>](https://www.zhihu.com/question/19841397)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Architect's Essential Quality and Growth Path"</font></font>](https://blog.csdn.net/sanbingyutuoniao123/article/details/54144129)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Quality: business understanding, breadth of technology, depth of technology, rich experience, communication skills, hands-on capabilities, and aesthetic qualities.</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Growth path: 2 years of accumulated knowledge, 4 years of accumulated skills and influence within the group, 7 years of accumulated influence within the sector, and 7 years of accumulated cross-sectoral influence.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Architects - Where are you on the floor?</font> <font style="vertical-align: inherit;">》</font></font>](http://blog.51cto.com/frankfan/1248401)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The first-tier architect sees only the product itself</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The second-tier architect not only saw his own product but also saw the overall solution</font></font>
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Third-tier architects see business value</font></font>

# [](#团队管理)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Team management</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

## [](#招聘)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Recruitment</font></font>

# [](#资讯)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Information</font></font>

## [](#行业资讯)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Industry information</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">36kr</font></font>](http://36kr.com/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Techweb</font></font>](http://www.techweb.com.cn/)

## [](#公众号列表)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Public number list</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

## [](#博客)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Blog</font></font>

### [](#团队博客)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Team blog</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ali Middleware Blog</font></font>](http://jm.taobao.org/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">US Mission Review Technology Team Blog</font></font>](https://tech.meituan.com)

### [](#个人博客)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">personal blog</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Shan Yifeng's Weblog</font></font>](http://www.ruanyifeng.com/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cool Shell - COOLSHELL-Chen Hao</font></font>](https://coolshell.cn/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hellojava - Ali Bixuan</font></font>](http://hellojava.info/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cm's Blog</font></font>](http://cmsblogs.com/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Program 猿 DD - Yongchao Chao - Author of Spring Cloud Microservices Act</font></font>](http://blog.didispace.com/)

## [](#综合门户社区)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Integrated portal, community</font></font>

**<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">domestic:</font></font>**

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CSDN</font></font>](http://csdn.net)<font style="vertical-align: inherit;"> <font style="vertical-align: inherit;">veteran technology community, do not have to explain.</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">51cto.com</font></font>](http://www.51cto.com/)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ITeye</font></font>](http://www.iteye.com/)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Partial Java direction</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Blog Park</font></font>](https://www.cnblogs.com)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ChinaUnix</font></font>](http://www.tom.net/)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Partial Linux direction</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open source Chinese community</font></font>](https://www.oschina.net/)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Deep open source</font></font>](http://www.open-open.com/)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bole Online</font></font>](http://www.jobbole.com/)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Covers IT workplace, Web front end, back end, mobile end, database and other aspects, partial technology.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ITPUB</font></font>](http://www.itpub.net/)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tencent Cloud - Cloud + Community</font></font>](https://cloud.tencent.com/developer/column)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Alibaba Cloud - Yunqi Community</font></font>](https://yq.aliyun.com/)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IBM DeveloperWorks</font></font>](https://www.ibm.com/developerworks/cn/)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Developer headlines</font></font>](https://toutiao.io/)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LinkedKeeper</font></font>](http://www.linkedkeeper.com)

**<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">foreign:</font></font>**

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DZone</font></font>](https://dzone.com)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Reddit</font></font>](https://www.reddit.com)

## [](#问答讨论类社区)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Q&A, discussion community</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Segmentfault</font></font>](https://segmentfault.com)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Q&A + Column</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Know almost</font></font>](https://www.zhihu.com/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Stackoverflow</font></font>](https://stackoverflow.com/)

## [](#行业数据分析)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Industry data analysis</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ereli Net</font></font>](http://report.iresearch.cn/)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">QUEST MOBILE</font></font>](https://www.questmobile.com.cn)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">National data</font></font>](http://data.stats.gov.cn/)

## [](#专项网站)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Special website</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">test:</font></font>

    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pilot Testing International</font></font>](http://www.ltesting.net/)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Test nest</font></font>](https://www.testwo.com/)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TesterHome</font></font>](https://testerhome.com)
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Operation and maintenance:</font></font>

    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Operation and maintenance</font></font>](http://www.yunweipai.com/)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Abcdocker</font></font>](https://www.abcdocker.com/)
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java:</font></font>

    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ImportNew</font></font>](http://www.importnew.com/)
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Focus on Java technology sharing</font></font>
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HowToDoInJava</font></font>](https://howtodoinjava.com/)
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">English blog</font></font>
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Safety</font></font>

    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Red and Black Alliance</font></font>](https://www.2cto.com/)
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FreeBuf</font></font>](http://www.freebuf.com/)
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Big Data</font></font>

    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">China Big Data</font></font>](http://www.thebigdata.cn/)
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Other special websites:</font></font>

    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DockerInfo</font></font>](http://www.dockerinfo.net/)
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Website focused on Docker applications and consulting, tutorials.</font></font>
    *   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux Commune</font></font>](https://www.linuxidc.com/)
        *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux Theme Community</font></font>

## [](#其他类)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">other</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Programmer skills map</font></font>](https://github.com/TeamStuQ/skill-map)

## [](#推荐参考书)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Recommended reference book</font></font>

### [](#在线电子书)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Online eBooks</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Understanding Spring Cloud and Microservice Construction"</font></font>](https://github.com/forezp/SpringCloudLearning)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Ali Technical Reference Atlas - R&D"</font></font>](http://techforum-img.cn-hangzhou.oss-pub.aliyun-inc.com/1523849261680/AliTech101_RD.pdf)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Ali Technical Reference Atlas - Algorithm"</font></font>](http://techforum-img.cn-hangzhou.oss-pub.aliyun-inc.com/1523848064814/AliTech101_Algorithms.pdf)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"2018 US Mission Review Technology New Year (Collection)" 70M</font></font>](http://dpurl.cn/n/1lqcX)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InfoQ "Architects" Monthly</font></font>](http://www.infoq.com/cn/architect/)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The Road to Architects</font></font>](https://www.w3cschool.cn/architectroad/)

### [](#纸质书)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Paper book</font></font>

#### [](#开发方面)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Development aspects</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Alibaba Java Development Handbook"</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jingdong</font> </font>](https://union-click.jd.com/jdc?d=bVKwZQ)[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taobao</font></font>](https://s.taobao.com/search?q=%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4Java%E5%BC%80%E5%8F%91%E6%89%8B%E5%86%8C)

#### [](#架构方面)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Architecture aspects</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Software Architect's 12 Practices: Technical Skills"</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jingdong</font> </font>](https://union-click.jd.com/jdc?d=gXvRd8)[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taobao</font></font>](https://s.taobao.com/search?q=%E8%BD%AF%E4%BB%B6%E6%9E%B6%E6%9E%84%E5%B8%88%E7%9A%8412%E9%A1%B9%E4%BF%AE%E7%82%BC%EF%BC%9A%E6%8A%80%E6%9C%AF%E6%8A%80%E8%83%BD%E7%AF%87)
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"The Beauty of Architecture"</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jingdong</font> </font>](https://union-click.jd.com/jdc?d=xJit5I)[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taobao</font></font>](https://s.taobao.com/search?q=%E6%9E%B6%E6%9E%84%E4%B9%8B%E7%BE%8E)
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Distributed Service Architecture"</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jingdong</font> </font>](https://union-click.jd.com/jdc?d=JS5Od9)[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taobao</font></font>](https://s.taobao.com/search?q=%E5%88%86%E5%B8%83%E5%BC%8F%E6%9C%8D%E5%8A%A1%E6%9E%B6%E6%9E%84)
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Talking Architecture"</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jingdong</font> </font>](https://union-click.jd.com/jdc?d=FHooH4)[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taobao</font></font>](https://s.taobao.com/search?q=%E8%81%8A%E8%81%8A%E6%9E%B6%E6%9E%84)
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Cloud native application architecture practice"</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jingdong</font> </font>](https://union-click.jd.com/jdc?d=orkJSj)[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taobao</font></font>](https://s.taobao.com/search?q=%E4%BA%91%E5%8E%9F%E7%94%9F%E5%BA%94%E7%94%A8%E6%9E%B6%E6%9E%84%E5%AE%9E%E8%B7%B5)
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"100 million-level traffic site architecture core technology"</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jingdong</font> </font>](https://union-click.jd.com/jdc?d=RnOSP5)[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taobao</font></font>](https://s.taobao.com/search?q=%E4%BA%BF%E7%BA%A7%E6%B5%81%E9%87%8F%E7%BD%91%E7%AB%99%E6%9E%B6%E6%9E%84%E6%A0%B8%E5%BF%83%E6%8A%80%E6%9C%AF)
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"This decade of Taobao technology"</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jingdong</font> </font>](https://union-click.jd.com/jdc?d=LwrDfD)[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taobao</font></font>](https://s.taobao.com/search?q=%E6%B7%98%E5%AE%9D%E6%8A%80%E6%9C%AF%E8%BF%99%E5%8D%81%E5%B9%B4)
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Transformation of Enterprise IT Architecture - Strategic Thinking of China-Taiwan Strategy and Architecture Combat"</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jingdong</font> </font>](https://union-click.jd.com/jdc?d=89pAEm)[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taobao</font></font>](https://s.taobao.com/search?q=%E4%BC%81%E4%B8%9AIT%E6%9E%B6%E6%9E%84%E8%BD%AC%E5%9E%8B%E4%B9%8B%E9%81%93)

#### [](#技术管理方面)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Technical management</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"CTO said"</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jingdong</font> </font>](https://union-click.jd.com/jdc?d=zhTZyr)[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taobao</font></font>](https://s.taobao.com/search?q=CTO%E8%AF%B4)
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Technology Management"</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jingdong</font> </font>](https://union-click.jd.com/jdc?d=LgRBUW)[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taobao</font></font>](https://s.taobao.com/search?q=%E6%8A%80%E6%9C%AF%E7%AE%A1%E7%90%86%E4%B9%8B%E5%B7%85)
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Netease Arabian Nights: The Reality of Internet Product Project Management"</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jingdong</font> </font>](https://union-click.jd.com/jdc?d=jcRz2r)[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taobao</font></font>](https://s.taobao.com/search?q=%E7%BD%91%E6%98%93%E4%B8%80%E5%8D%83%E9%9B%B6%E4%B8%80%E5%A4%9C%EF%BC%9A%E4%BA%92%E8%81%94%E7%BD%91%E4%BA%A7%E5%93%81%E9%A1%B9%E7%9B%AE%E7%AE%A1%E7%90%86%E5%AE%9E%E6%88%98)

#### [](#基础理论-1)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Basic theory</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">The beauty of mathematics</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jingdong</font> </font>](https://union-click.jd.com/jdc?d=ghIES2)[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taobao</font></font>](https://s.taobao.com/search?q=%E6%95%B0%E5%AD%A6%E4%B9%8B%E7%BE%8E)
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Programming Beads"</font> </font>[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jingdong</font> </font>](https://union-click.jd.com/jdc?d=YmhdEu)[<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Taobao</font></font>](https://s.taobao.com/search?q=%E7%BC%96%E7%A8%8B%E7%8F%A0%E7%8E%91)

#### [](#工具方面)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tools</font></font>

<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TODO</font></font>

#### [](#大数据方面)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Big data</font></font>

# [](#技术资源)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Technical resources</font></font>

## [](#开源资源)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open source resources</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Github</font></font>](https://github.com)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apache Software Foundation</font></font>](https://www.apache.org/index.html)

## [](#手册文档教程)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Manuals, Documents, Tutorials</font></font>

**<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">domestic:</font></font>**

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">W3Cschool</font></font>](http://w3cschool.cn)

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Runoob.com</font></font>](http://www.runoob.com/)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HTML, CSS, XML, Java, Python, PHP, design patterns, and other introductory manuals.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Love2.io</font></font>](https://love2.io/)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Many, many Chinese online e-books are a new open source technology document sharing platform.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gitbook.cn</font></font>](http://gitbook.cn/)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Paid e-books.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ApacheCN</font></font>](http://www.apachecn.org/)

    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AI, big data series Chinese documents.</font></font>

**<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">foreign:</font></font>**

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Quick Code</font></font>](http://www.quickcode.co/)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Free online technical tutorials.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gitbook.com</font></font>](http://gitbook.com)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">There are some Chinese e-books.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cheatography</font></font>](https://www.cheatography.com/)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cheat Sheets, a one-page document website.</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tutorialspoint</font></font>](https://www.tutorialspoint.com/index.htm)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Well-known tutorial website, providing high-quality introductory tutorials such as Java, Python, JS, SQL, big data.</font></font>

## [](#在线课堂)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Online class</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apprentice worry-free</font></font>](http://www.xuetuwuyou.com/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Geek time</font></font>](https://time.geekbang.org/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Segmentfault</font></font>](https://segmentfault.com/lives)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Stark College</font></font>](https://new.stuq.org/course/explore)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Niu Ke Network</font></font>](http://nowcoder.com)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Geek College</font></font>](https://www.jikexueyuan.com/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">51CTO College</font></font>](http://edu.51cto.com/)

## [](#会议活动)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">conference</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">QCon</font></font>](http://www.infoq.com/cn/qcon/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ArchSummit</font></font>](https://archsummit.com)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GITC Global Internet Technology Conference</font></font>](http://www.thegitc.com/)

**<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Event publishing platform:</font></font>**

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Activity line</font></font>](http://www.huodongxing.com/)

## [](#常用app)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Common APP</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Geek time</font></font>](https://time.geekbang.org)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">get</font></font>](https://www.igetget.com)

## [](#找工作)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">find a job</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Boss Direct Employment</font></font>](https://www.zhipin.com)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pulling the net</font></font>](https://www.lagou.com)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hunting</font></font>](https://www.liepin.com)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">100Offer</font></font>](https://cn.100offer.com/)

## [](#工具)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">tool</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Geek Search</font></font>](https://s.geekbang.org/)
    *   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Technical article search engine.</font></font>

## [](#代码托管)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Code hosting</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Coding</font></font>](https://coding.net)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Code cloud</font></font>](https://gitee.com/)

## [](#文件服务)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">File service</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Seven cattle</font></font>
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Shooting clouds again</font></font>

## [](#综合云服务商)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Comprehensive cloud service provider</font></font>

*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ali Cloud</font></font>
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tencent Cloud</font></font>
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Baidu cloud</font></font>
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sina Cloud</font></font>
*   <font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jinshan Yun</font></font>
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Amazon Cloud (AWS)</font></font>](https://amazonaws-china.com/cn/)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Google Cloud</font></font>](https://cloud.google.com/?hl=zh-cn)
*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Microsoft Cloud</font></font>](https://azure.microsoft.com/zh-cn/)

### [](#vps)<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">VPS</font></font>

*   [<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linode</font></font>](http://linode.com)

</article>
