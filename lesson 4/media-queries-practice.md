# Requirements

Add styles to [markup](media-queries-practice.html)

## Breakpoints values

- Large Desktop: 1800px
- Medium Desktop: 1200px
- Tablet Landscape: 960px
- Tabled Portrait: 768px
- Mobile: 320px

## From large Desktop

- [х] 1 block -> 4 elements in a row: all equal width
- [х] 2 block -> 2 elements in a row: all equal width
- [х] 3 block -> 3 elements in a row: all 25% width
- [x] 4 block -> 3 elements in a row: 1 -> 25%, 2 -> 25% and 3 ->50%
- [x] 5 block -> 5 elements in a row: all equal width

## From medium desktop to large desktop

- [x] 1 block -> 2 elements in a row: all equal width, so it will have 2 rows width: 50%
- [x] 2 block -> 2 elements in a row: all equal width
- [x] 3 block -> 3 elements: 1 -> 50%, 2 -> 50% and last 100%
- [x] 4 block -> 3 elements in a row: 1 -> 35%, 2 -> 30% and 3 ->35%
- [x] 5 block -> 3 or 2 elements in a row, all 33% width, centered in center of parent block

## From Tablet Landscape to medium desktop

- [x] 1 block -> 2 elements in a row: all equal width, so it will have 2 rows width: 50%
- [x] 2 block -> 2 elements in a row: all equal width
- [x] 3 block -> 3 elements in a row: all equal width
- [x] 4 block -> 3 elements in a row: 1 -> 35%, 2 -> 30% and 3 ->35%
- [x] 5 block -> 2 elements in a row, all equal width, the last one should be 100% width

## From Tablet Portrait to Tablet Landscape

- [x] 1 block -> all elements width: 50%
- [x] 2 block -> all elements width: 50%
- [x] 3 block -> 1 element in a row, full width
- [x] 4 block -> 1 and second: 50% and last element 100% width
- [x] 5 block -> 2 elements in a row, 50% width, last one is 100% width

## From Mobile to Tablet Portrait

- [x] 1 block -> all elements width: 50%
- [x] 2 block -> all elements width: 50%
- [x] 3 block -> 1 element in a row, full width 100% for all
- [x] 4 block -> 1 element in a row, full width 100% for all
- [] 5 block -> all elements in 100% width