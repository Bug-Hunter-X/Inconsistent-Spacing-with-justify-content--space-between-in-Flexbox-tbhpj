# Inconsistent Spacing with `justify-content: space-between` in Flexbox

This repository demonstrates a common issue encountered when using `justify-content: space-between` with flex items that don't have equal widths. The problem arises because `space-between` distributes space *between* the items, not necessarily making them evenly spaced.

## The Bug

The provided CSS code aims to create three items evenly spaced within a flex container. However, due to the nature of `space-between`, the result is inconsistent spacing if the items have varying widths.  The solution showcases how to achieve even spacing, even with unequal item widths.

## Solution

To obtain consistent spacing, you should consider using `justify-content: space-around` or a different layout approach that aligns with the desired outcome.