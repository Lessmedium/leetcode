# `Go版本的一题多解（所有解）`

# 我的刷题步骤

## `1.新建刷题目录`
比如第 `1` 题 two-sum

`go run main.go -a=1`

比如第 `100` 题 same-tree

`go run main.go -a=100`

## `2.模板流`
个人建议刷完前50题后，完全刷一个系列的，比如我最近在刷 Tree，因为 Tree 是最简单的～

刷题过程中要整理好自己的解题模板

切记！！！！不要相信 `自己解题可以提高智商` 这种鬼话， 5分钟没思路直接看答案，千万别浪费时间

然后 `模板流` 一把嗖，目标是 `所有算法全是手！速！题！`

## `3.目录约定`  `生成 readme.md`

`分类` : `1 级目录`

`题名` : `2 级目录`

`算法` : `3-N 级目录`

执行 `go run main.go` 自动生成 `readme.md`

# 模板
- [Tree](https://github.com/temporaries/leetcode/tree/master/templates/tree)
    - [前序遍历](https://github.com/temporaries/leetcode/blob/master/templates/tree/preorder.go)
    - [中序遍历](https://github.com/temporaries/leetcode/blob/master/templates/tree/inorder.go)
    - [后序遍历](https://github.com/temporaries/leetcode/blob/master/templates/tree/postorder.go)
    - [前序遍历-Morris-链表](https://github.com/temporaries/leetcode/blob/master/templates/tree/postorder_morris_break.go)
    - [层次遍历](https://github.com/temporaries/leetcode/blob/master/templates/tree/bfs.go)

# 数据结构

---
- [Array](#Array)
- [LinkedList](#LinkedList)
- [Math](#Math)
- [Stack](#Stack)
- [String](#String)
- [Tree](#Tree)

---



## Array
|  #   | Title                                  | Acceptance  | Difficulty  | Solution         | Algorithm
| ---- | -------------------------------------- |  ---------- | ----------- |----------------- | ----------
| 0001 | [Two Sum                         ](https://leetcode-cn.com/problems/two-sum) | 47.6% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/array/0001.two-sum/hash_table/main.go)| hash table
| 0004 | [Median of Two Sorted Arrays     ](https://leetcode-cn.com/problems/median-of-two-sorted-arrays) | 36.8% | Hard | [Go](https://github.com/temporaries/leetcode/tree/master/array/0004.median-of-two-sorted-arrays/binary_search/main.go)| binary search
| 0011 | [Container With Most Water       ](https://leetcode-cn.com/problems/container-with-most-water) | 61.3% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/array/0011.container-with-most-water/two_pointer/main.go)| two pointer
| 0015 | [3Sum                            ](https://leetcode-cn.com/problems/3sum) | 25.5% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/array/0015.3sum/two_pointer/main.go)| two pointer
| 0016 | [3Sum Closest                    ](https://leetcode-cn.com/problems/3sum-closest) | 43.0% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/array/0016.3sum-closest/two_pointer/main.go)| two pointer
| 0018 | [4Sum                            ](https://leetcode-cn.com/problems/4sum) | 37.2% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/array/0018.4sum/two_pointer/main.go)| two pointer
| 0026 | [Remove Duplicates from Sorted Array](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-array) | 48.6% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/array/0026.remove-duplicates-from-sorted-array/two_pointer/main.go)| two pointer
| 0027 | [Remove Element                  ](https://leetcode-cn.com/problems/remove-element) | 57.4% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/array/0027.remove-element/two_pointer/main.go)| two pointer
| 0030 | [Substring with Concatenation of All Words](https://leetcode-cn.com/problems/substring-with-concatenation-of-all-words) | 29.2% | Hard | [Go](https://github.com/temporaries/leetcode/tree/master/array/0030.substring-with-concatenation-of-all-words/two_pointer/main.go)| two pointer
| 0033 | [Search in Rotated Sorted Array  ](https://leetcode-cn.com/problems/search-in-rotated-sorted-array) | 36.4% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/array/0033.search-in-rotated-sorted-array/binary_search/main.go)| binary search
| 0034 | [Find First and Last Position of Element in Sorted Array](https://leetcode-cn.com/problems/find-first-and-last-position-of-element-in-sorted-array) | 39.0% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/array/0034.find-first-and-last-position-of-element-in-sorted-array/binary_search/main.go)| binary search
| 0035 | [Search Insert Position          ](https://leetcode-cn.com/problems/search-insert-position) | 45.2% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/array/0035.search-insert-position/binary_search/main.go)| binary search
| 0036 | [Valid Sudoku                    ](https://leetcode-cn.com/problems/valid-sudoku) | 58.4% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/array/0036.valid-sudoku/dfs/main.go)| dfs
| 0037 | [Sudoku Solver                   ](https://leetcode-cn.com/problems/sudoku-solver) | 59.5% | Hard | [Go](https://github.com/temporaries/leetcode/tree/master/array/0037.sudoku-solver/dfs/main.go)| dfs
| 0041 | [First Missing Positive          ](https://leetcode-cn.com/problems/first-missing-positive) | 37.6% | Hard | [Go](https://github.com/temporaries/leetcode/tree/master/array/0041.first-missing-positive/bit_map/main.go)| bit map
| 0042 | [Trapping Rain Water             ](https://leetcode-cn.com/problems/trapping-rain-water) | 48.6% | Hard | [Go](https://github.com/temporaries/leetcode/tree/master/array/0042.trapping-rain-water/two_pointer/main.go)| two pointer

## LinkedList
|  #   | Title                                  | Acceptance  | Difficulty  | Solution         | Algorithm
| ---- | -------------------------------------- |  ---------- | ----------- |----------------- | ----------
| 0002 | [Add Two Numbers                 ](https://leetcode-cn.com/problems/add-two-numbers) | 36.6% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/linked_list/0002.add-two-numbers/main.go)| 
| 0019 | [Remove Nth Node From End of List](https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list) | 37.5% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/linked_list/0019.remove-nth-node-from-end-of-list/two_pointer/main.go)| two pointer
| 0021 | [Merge Two Sorted Lists          ](https://leetcode-cn.com/problems/merge-two-sorted-lists) | 59.7% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/linked_list/0021.merge-two-sorted-lists/main.go)| 
| 0023 | [Merge k Sorted Lists            ](https://leetcode-cn.com/problems/merge-k-sorted-lists) | 48.8% | Hard | [Go](https://github.com/temporaries/leetcode/tree/master/linked_list/0023.merge-k-sorted-lists/main.go)| 
| 0024 | [Swap Nodes in Pairs             ](https://leetcode-cn.com/problems/swap-nodes-in-pairs) | 64.3% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/linked_list/0024.swap-nodes-in-pairs/main.go)| 
| 0025 | [Reverse Nodes in k-Group        ](https://leetcode-cn.com/problems/reverse-nodes-in-k-group) | 56.2% | Hard | [Go](https://github.com/temporaries/leetcode/tree/master/linked_list/0025.reverse-nodes-in-k-group/main.go)| 

## Math
|  #   | Title                                  | Acceptance  | Difficulty  | Solution         | Algorithm
| ---- | -------------------------------------- |  ---------- | ----------- |----------------- | ----------
| 0007 | [Reverse Integer                 ](https://leetcode-cn.com/problems/reverse-integer) | 33.6% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/math/0007.reverse-integer/main.go)| 
| 0008 | [String to Integer (atoi)        ](https://leetcode-cn.com/problems/string-to-integer-atoi) | 19.1% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/math/0008.string-to-integer-atoi/main.go)| 
| 0009 | [Palindrome Number               ](https://leetcode-cn.com/problems/palindrome-number) | 57.1% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/math/0009.palindrome-number/main.go)| 
| 0012 | [Integer to Roman                ](https://leetcode-cn.com/problems/integer-to-roman) | 62.6% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/math/0012.integer-to-roman/main.go)| 
| 0013 | [Roman to Integer                ](https://leetcode-cn.com/problems/roman-to-integer) | 60.7% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/math/0013.roman-to-integer/main.go)| 
| 0029 | [Divide Two Integers             ](https://leetcode-cn.com/problems/divide-two-integers) | 19.3% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/math/0029.divide-two-integers/main.go)| 
| 0031 | [Next Permutation                ](https://leetcode-cn.com/problems/next-permutation) | 32.8% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/math/0031.next-permutation/main.go)| 
| 0292 | [Nim Game                        ](https://leetcode-cn.com/problems/nim-game) | 69.7% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/math/0292.nim-game/main.go)| 
| 0319 | [Bulb Switcher                   ](https://leetcode-cn.com/problems/bulb-switcher) | 44.6% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/math/0319.bulb-switcher/main.go)| 

## Stack
|  #   | Title                                  | Acceptance  | Difficulty  | Solution         | Algorithm
| ---- | -------------------------------------- |  ---------- | ----------- |----------------- | ----------
| 0020 | [Valid Parentheses               ](https://leetcode-cn.com/problems/valid-parentheses) | 40.9% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/stack/0020.valid-parentheses/main.go)| 
| 0032 | [Longest Valid Parentheses       ](https://leetcode-cn.com/problems/longest-valid-parentheses) | 29.7% | Hard | [Go](https://github.com/temporaries/leetcode/tree/master/stack/0032.longest-valid-parentheses/main.go)| 

## String
|  #   | Title                                  | Acceptance  | Difficulty  | Solution         | Algorithm
| ---- | -------------------------------------- |  ---------- | ----------- |----------------- | ----------
| 0003 | [Longest Substring Without Repeating Characters](https://leetcode-cn.com/problems/longest-substring-without-repeating-characters) | 32.9% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/string/0003.longest-substring-without-repeating-characters/main.go)| 
| 0005 | [Longest Palindromic Substring   ](https://leetcode-cn.com/problems/longest-palindromic-substring) | 28.5% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/string/0005.longest-palindromic-substring/main.go)| 
| 0006 | [ZigZag Conversion               ](https://leetcode-cn.com/problems/zigzag-conversion) | 46.7% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/string/0006.zigzag-conversion/main.go)| 
| 0010 | [Regular Expression Matching     ](https://leetcode-cn.com/problems/regular-expression-matching) | 26.0% | Hard | [Go](https://github.com/temporaries/leetcode/tree/master/string/0010.regular-expression-matching/main.go)| 
| 0014 | [Longest Common Prefix           ](https://leetcode-cn.com/problems/longest-common-prefix) | 36.2% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/string/0014.longest-common-prefix/main.go)| 
| 0017 | [Letter Combinations of a Phone Number](https://leetcode-cn.com/problems/letter-combinations-of-a-phone-number) | 52.5% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/string/0017.letter-combinations-of-a-phone-number/main.go)| 
| 0028 | [Implement strStr()              ](https://leetcode-cn.com/problems/implement-strstr) | 39.5% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/string/0028.implement-strstr/main.go)| 
| 0038 | [Count and Say                   ](https://leetcode-cn.com/problems/count-and-say) | 54.4% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/string/0038.count-and-say/main.go)| 
| 0043 | [Multiply Strings                ](https://leetcode-cn.com/problems/multiply-strings) | 41.6% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/string/0043.multiply-strings/main.go)| 
| 0415 | [Add Strings                     ](https://leetcode-cn.com/problems/add-strings) | 49.5% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/string/0415.add-strings/main.go)| 

## Tree
|  #   | Title                                  | Acceptance  | Difficulty  | Solution         | Algorithm
| ---- | -------------------------------------- |  ---------- | ----------- |----------------- | ----------
| 0022 | [Generate Parentheses            ](https://leetcode-cn.com/problems/generate-parentheses) | 73.3% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0022.generate-parentheses/dfs/catalan/main.go)| dfs.catalan
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0022.generate-parentheses/dfs/recursive/main.go)| dfs.recursive
| 0039 | [Combination Sum                 ](https://leetcode-cn.com/problems/combination-sum) | 68.4% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0039.combination-sum/dfs/recursive/main.go)| dfs.recursive
| 0040 | [Combination Sum II              ](https://leetcode-cn.com/problems/combination-sum-ii) | 60.1% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0040.combination-sum-ii/dfs/recursive/main.go)| dfs.recursive
| 0094 | [Binary Tree Inorder Traversal   ](https://leetcode-cn.com/problems/binary-tree-inorder-traversal) | 70.2% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0094.binary-tree-inorder-traversal/dfs/inorder/recursive/main.go)| dfs.inorder.recursive
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0094.binary-tree-inorder-traversal/dfs/inorder/stack/main.go)| dfs.inorder.stack
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0094.binary-tree-inorder-traversal/dfs/morris/break/main.go)| dfs.morris.break
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0094.binary-tree-inorder-traversal/dfs/morris/keep/main.go)| dfs.morris.keep
| 0095 | [Unique Binary Search Trees II   ](https://leetcode-cn.com/problems/unique-binary-search-trees-ii) | 61.4% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0095.unique-binary-search-trees-ii/dfs/catalan/main.go)| dfs.catalan
| 0096 | [Unique Binary Search Trees      ](https://leetcode-cn.com/problems/unique-binary-search-trees) | 64.8% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0096.unique-binary-search-trees/catalan/main.go)| catalan
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0096.unique-binary-search-trees/dp/main.go)| dp
| 0098 | [Validate Binary Search Tree     ](https://leetcode-cn.com/problems/validate-binary-search-tree) | 28.9% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0098.validate-binary-search-tree/bfs/main.go)| bfs
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0098.validate-binary-search-tree/dfs/inorder/recursive/main.go)| dfs.inorder.recursive
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0098.validate-binary-search-tree/dfs/inorder/stack/main.go)| dfs.inorder.stack
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0098.validate-binary-search-tree/dfs/preorder/recursive/main.go)| dfs.preorder.recursive
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0098.validate-binary-search-tree/dfs/preorder/stack/main.go)| dfs.preorder.stack
| 0099 | [Recover Binary Search Tree      ](https://leetcode-cn.com/problems/recover-binary-search-tree) | 54.9% | Hard | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0099.recover-binary-search-tree/dfs/inorder/recursive/main.go)| dfs.inorder.recursive
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0099.recover-binary-search-tree/dfs/inorder/stack/main.go)| dfs.inorder.stack
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0099.recover-binary-search-tree/dfs/morris/keep.go)| dfs.morris
| 0100 | [Same Tree                       ](https://leetcode-cn.com/problems/same-tree) | 56.5% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0100.same-tree/dfs/recursive/main.go)| dfs.recursive
| 0101 | [Symmetric Tree                  ](https://leetcode-cn.com/problems/symmetric-tree) | 50.0% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0101.symmetric-tree/dfs/recursive/main.go)| dfs.recursive
| 0102 | [Binary Tree Level Order Traversal](https://leetcode-cn.com/problems/binary-tree-level-order-traversal) | 60.9% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0102.binary-tree-level-order-traversal/bfs/queue/main.go)| bfs.queue
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0102.binary-tree-level-order-traversal/dfs/recursive/main.go)| dfs.recursive
| 0103 | [Binary Tree Zigzag Level Order Traversal](https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal) | 53.6% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0103.binary-tree-zigzag-level-order-traversal/bfs/queue/main.go)| bfs.queue
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0103.binary-tree-zigzag-level-order-traversal/dfs/recursive/main.go)| dfs.recursive
| 0104 | [Maximum Depth of Binary Tree    ](https://leetcode-cn.com/problems/maximum-depth-of-binary-tree) | 72.2% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0104.maximum-depth-of-binary-tree/dfs/main.go)| dfs
| 0105 | [Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode-cn.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal) | 64.1% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0105.construct-binary-tree-from-preorder-and-inorder-traversal/main.go)| 
| 0106 | [Construct Binary Tree from Inorder and Postorder Traversal](https://leetcode-cn.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal) | 66.9% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0106.construct-binary-tree-from-inorder-and-postorder-traversal/main.go)| 
| 0107 | [Binary Tree Level Order Traversal II](https://leetcode-cn.com/problems/binary-tree-level-order-traversal-ii) | 64.3% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0107.binary-tree-level-order-traversal-ii/bfs/queue/main.go)| bfs.queue
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0107.binary-tree-level-order-traversal-ii/dfs/recursive/main.go)| dfs.recursive
| 0108 | [Convert Sorted Array to Binary Search Tree](https://leetcode-cn.com/problems/convert-sorted-array-to-binary-search-tree) | 69.1% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0108.convert-sorted-array-to-binary-search-tree/dfs/recursive/main.go)| dfs.recursive
| 0109 | [Convert Sorted List to Binary Search Tree](https://leetcode-cn.com/problems/convert-sorted-list-to-binary-search-tree) | 70.3% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0109.convert-sorted-list-to-binary-search-tree/array/main.go)| array
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0109.convert-sorted-list-to-binary-search-tree/inorder/main.go)| inorder
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0109.convert-sorted-list-to-binary-search-tree/recursive/main.go)| recursive
| 0110 | [Balanced Binary Tree            ](https://leetcode-cn.com/problems/balanced-binary-tree) | 50.2% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0110.balanced-binary-tree/postorder/main.go)| postorder
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0110.balanced-binary-tree/top/main.go)| top
| 0111 | [Minimum Depth of Binary Tree    ](https://leetcode-cn.com/problems/minimum-depth-of-binary-tree) | 41.5% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0111.minimum-depth-of-binary-tree/bfs/main.go)| bfs
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0111.minimum-depth-of-binary-tree/dfs/main.go)| dfs
| 0112 | [Path Sum                        ](https://leetcode-cn.com/problems/path-sum) | 49.0% | Easy | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0112.path-sum/dfs/main.go)| dfs
| 0113 | [Path Sum II                     ](https://leetcode-cn.com/problems/path-sum-ii) | 58.7% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0113.path-sum-ii/dfs/main.go)| dfs
| 0114 | [Flatten Binary Tree to Linked List](https://leetcode-cn.com/problems/flatten-binary-tree-to-linked-list) | 67.5% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0114.flatten-binary-tree-to-linked-list/preorder.morris/main.go)| preorder.morris
| 0116 | [Populating Next Right Pointers in Each Node](https://leetcode-cn.com/problems/populating-next-right-pointers-in-each-node) | 53.9% | Medium | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0116.populating-next-right-pointers-in-each-node/bfs/main.go)| bfs
|  | [                                ](https://leetcode-cn.com/problems/) |  |  | [Go](https://github.com/temporaries/leetcode/tree/master/tree/0116.populating-next-right-pointers-in-each-node/dfs/main.go)| dfs