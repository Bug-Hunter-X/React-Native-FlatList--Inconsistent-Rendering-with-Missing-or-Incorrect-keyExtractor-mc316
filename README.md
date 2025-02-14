# React Native FlatList: Inconsistent Rendering with Missing or Incorrect `keyExtractor`

This repository demonstrates a common issue in React Native's `FlatList` component: inconsistent rendering caused by a missing or faulty `keyExtractor` function. The `keyExtractor` is essential for `FlatList` to efficiently update and render its items.  Without unique keys, `FlatList` may struggle to identify which items have changed, leading to incorrect updates or performance degradation.

The `bug.js` file shows an example of this problem. The `bugSolution.js` file provides the corrected implementation with a proper `keyExtractor` function.  The solution ensures that each item has a unique key, addressing the inconsistent rendering issues.