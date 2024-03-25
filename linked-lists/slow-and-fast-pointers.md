# Slow and Fast Pointers
- These are two pointers, `slow` and `fast`, both initially pointing to the head of the linked list.
- Traverse the list with the `slow` pointer moving **one** step at a time, while the `fast` pointer moves **two** steps at a time.

### Usage
1. **To check cycle**
   - The `fast` pointer will meet the `slow` pointer if there is a loop in the linked list
2. **To find middle node of the list**
   - When the `fast` pointer reaches the end of the list or has no next node, the `slow` pointer should be at the middle node of the list.
